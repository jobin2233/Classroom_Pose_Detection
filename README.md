# Classroom_Pose_Detection

## 📌 Project Overview

**Classroom Pose Detection** is a real-time deep learning project developed to detect and classify various student postures in a classroom environment using **YOLOv8**. The primary objective is to identify and monitor student behavior based on their pose. The model can accurately recognize the following four classroom-specific postures:

- **Sitting**
- **Standing**
- **Sleeping**
- **Hand Raised**

This application can be beneficial for educational analytics, student engagement tracking, and automated classroom monitoring.

---

## 🎯 Key Features

- Real-time pose detection using **YOLOv8**.
- Custom dataset consisting of real classroom images.
- 4-class object detection (sitting, standing, sleeping, hand raise).
- Easy-to-use training pipeline with **Roboflow**-generated annotations.
- Modular and scalable codebase for future enhancements.

---

## 📁 Dataset

We created a **custom dataset** by capturing around **1500 real-world images** of students in a classroom across the four pose categories. The dataset was annotated using **Roboflow**, with bounding boxes manually drawn for each pose.

### 🔗 Download Dataset

You can access and download the dataset from the following Google Drive link:

📂 [Classroom Pose Dataset - Google Drive](https://drive.google.com/drive/folders/1fjD33hU4HZNw2_rbA6y2N3DtG2XfMg4V)

The dataset is organized into:

- `train/`
- `val/`
- `test/`

---

## 🧠 Model & Architecture

- **Model**: YOLOv8 (You Only Look Once - Version 8)
- **Framework**: [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- **Annotations**: Roboflow (YOLO format)

We used transfer learning with YOLOv8 pre-trained weights, then fine-tuned the model on our custom dataset.

---

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Classroom_Pose_Detection.git
cd Classroom_Pose_Detection
