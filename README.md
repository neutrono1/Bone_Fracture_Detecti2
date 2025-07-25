#  Bone Fracture Detection using YOLOv8

This project detects and classifies different types of bone fractures from X-ray images using the **YOLOv8 deep learning model**. It is trained on a custom dataset of medical X-rays and can identify multiple fracture types accurately.

---

* Features
- ✅ Detects **7 different types of fractures**.
- ✅ Built on the **YOLOv8 state-of-the-art object detection model**.
- ✅ Trained on a **medical X-ray dataset** with over 4,000 images.
- ✅ Easy to use for both training and inference.

---

*Dataset Details
- **Total Images:** ~4,148
  - **Train:** 3,631 images
  - **Validation:** 348 images
  - **Test:** 169 images
- **Classes (`nc: 7`):**
  1. `elbow positive`
  2. `fingers positive`
  3. `forearm fracture`
  4. `humerus fracture`
  5. `humerus`
  6. `shoulder fracture`
  7. `wrist positive`

*Dataset folder structure:
BoneFractureYolo8/
├── train/
│ ├── images/
│ └── labels/
├── valid/
│ ├── images/
│ └── labels/
└── test/
├── images/
└── labels/


*Project Structure
graphql
Copy code
Bone_Fracture_Detecti2/
├── BoneFractureYolo8/          # Dataset (train, valid, test)
├── runs/                       # Training & detection results (auto-generated)
│   └── detect/
├── YOLOV8.ipynb                # Notebook for training & testing
├── data.yaml                   # Dataset configuration
├── yolo11n.pt                  # YOLO pretrained weight file
└── yolov8n.pt                  # YOLO pretrained weight file
