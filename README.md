# Weapon Detection using YOLOv5

This project focuses on training a YOLOv5 model to detect weapons such as **guns, knives, bombs, and swords** using the **SOHAs Weapon Detection Dataset**.  
The model is developed and tested using **Google Colab**, **PyTorch**, and **OpenCV** for visualization and performance evaluation.

---

## Project Overview

The goal of this project is to enhance security and surveillance systems using AI-based real-time weapon detection.  
The trained YOLOv5 model can identify weapons in images or video streams, providing a foundation for intelligent security solutions.

### Key Features
- Detects **guns, knives, bombs, and swords** with high accuracy.  
- Built using the **YOLOv5** deep learning architecture.  
- Integrated with **OpenCV** for real-time object detection.  
- Compatible with custom datasets using YOLO annotation format.  
- Easily exportable to **TensorFlow Lite** for lightweight use cases.

---

## Dataset

- **Dataset:** SOHAs Weapon Detection Dataset  
- **Classes:** Gun, Knife 
- **Format:** YOLO annotation format (`.txt` label files with bounding boxes).  
- **Purpose:** Designed for AI-based weapon detection and security applications.  
- **Usage:** Used for both training and testing to evaluate model accuracy.

---

## Technologies Used

- **YOLOv5** (PyTorch)
- **OpenCV**  
- **NumPy**  
- **Matplotlib**  
- **Google Colab / Jupyter Notebook**

---

## Results

The YOLOv5 model demonstrates reliable performance in detecting weapons in various environments and lighting conditions.  
Example outputs include bounding boxes and confidence scores for each detected weapon type.
