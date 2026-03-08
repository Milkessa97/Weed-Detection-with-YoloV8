# 🌿 SmartAg: Automated Weed Detection 
[![YOLOv8](https://img.shields.io/badge/Model-YOLOv8-00FFAA?style=for-the-badge&logo=ultralytics)](https://github.com/ultralytics/ultralytics)
[![Roboflow](https://img.shields.io/badge/Data-Roboflow-6706CE?style=for-the-badge&logo=roboflow)](https://roboflow.com)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

<p align="center">
  <img src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov8/banner-yolov8.png" width="800" alt="YOLOv8 Banner">
</p>

---

## ⚡ Quick Vision
This project leverages the power of **Computer Vision** to automate the identification of weeds in agricultural fields. By utilizing a custom-trained **YOLOv8** architecture, we provide a high-speed, high-accuracy solution to help farmers optimize herbicide use and improve crop yields.

### 🎯 Features
- 🚀 **Real-time Inference:** Optimized for edge deployment.
- 📊 **Precision Agriculture:** High mAP scores on weed-specific datasets.
- 🔄 **Augmented Training:** Robust against lighting and soil variations.

---

## 🛠️ Tech Stack & Tools
<div align="left">
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=PyTorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-%235C3EE8.svg?style=flat-square&logo=OpenCV&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-%23150458.svg?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Colab-%23F9AB00.svg?style=flat-square&logo=googlecolab&logoColor=white" />
</div>

---

## 📈 Performance Dashboard
We compared the **Nano** and **Small** versions of YOLOv8. Here’s how they stacked up:

| Model | mAP50 🏆 | Precision 🎯 | Recall 🔍 | Latency ⚡ |
| :--- | :---: | :---: | :---: | :---: |
| **YOLOv8n** | `0.945` | `0.898` | `0.899` | **1.1ms** |
| **YOLOv8s** | `0.948` | `0.916` | `0.887` | **2.5ms** |

---

## 🚀 Getting Started

### 1. Installation
```bash
# Clone the repository
git clone [https://github.com/yourusername/weed-detection.git](https://github.com/yourusername/weed-detection.git)

# Install dependencies
pip install ultralytics opencv-python pandas
