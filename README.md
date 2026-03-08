# 🌿 Automated Weed Detection for Precision Agriculture
[![Model: YOLOv8](https://img.shields.io/badge/Model-YOLOv8n-00FFAA?style=for-the-badge&logo=ultralytics)](https://github.com/ultralytics/ultralytics)
[![Data: Roboflow](https://img.shields.io/badge/Dataset-Roboflow-6706CE?style=for-the-badge&logo=roboflow)](https://roboflow.com)
[![Accuracy: 97.5%](https://img.shields.io/badge/mAP50-97.5%25-green?style=for-the-badge)](https://github.com/yourusername)

---

## ⚡ Project Overview
This project implements a high-performance **YOLOv8-based** computer vision model designed to detect weeds in agricultural fields. Trained on data sourced from **Roboflow**, the model is optimized for both accuracy and speed, making it suitable for real-time deployment on autonomous farming equipment.

### ✨ Key Highlights
- **Target:** Distinguishing between crops and invasive weed species.
- **Efficiency:** Ultra-lightweight (5.96 MB) for edge device compatibility.
- **Robustness:** Trained with Blur, CLAHE, and MedianBlur augmentations to handle varying field conditions.

---

## 📊 Performance Benchmarks
The **YOLOv8n** model achieved exceptional results during evaluation:

| Metric | Score | Description |
| :--- | :--- | :--- |
| **mAP50** 🏆 | `0.9757` | Mean Average Precision at 0.5 IoU |
| **Precision** 🎯 | `0.9362` | Ability to avoid false positives |
| **Recall** 🔍 | `0.9597` | Ability to find all relevant objects |
| **Inference** ⚡ | `4.86 ms` | Processing speed per image |
| **Model Size** 📦 | `5.96 MB` | Final weights file size |

---



## 🛠️ Tech Stack
<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Ultralytics-00FFAA?style=for-the-badge&logo=github&logoColor=black" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</div>

---

## 🚀 Pipeline Workflow

```mermaid
graph LR
    A[Field Images] --> B{Roboflow}
    B --> C[Augmentation]
    C --> D[YOLOv8 Training]
    D --> E[Validation]
    E --> F[Inference Deployment]
    style F fill:#00FFAA,stroke:#333,stroke-width:2px
