# Arabic License Plate Detection using YOLOv8

This project implements an Automated License Plate Recognition (ALPR) system specifically designed for Arabic license plates (with a focus on Egyptian plates) using the **YOLOv8** architecture.

## 📌 Project Overview

The goal of this notebook is to detect and identify Arabic characters and numbers on vehicle license plates. It leverages a custom dataset from Roboflow and uses the state-of-the-art YOLOv8 model for high-accuracy object detection.

## 🚀 Features

* **YOLOv8 Integration:** Uses the `ultralytics` framework for training and inference.
* **Dataset Management:** Automatic downloading and setup of the "Arabic-Plates" dataset via the Roboflow API.
* **Visualization:** Includes custom functions for displaying detection results directly within the notebook environment.
* **Comprehensive Pre-processing:** Handles library version conflicts (specifically for `numpy` and `supervision`) to ensure environment stability.

## 🛠️ Technology Stack

* **Model:** YOLOv8 (Ultralytics)
* **Language:** Python 3
* **Libraries:** `cv2` (OpenCV), `pandas`, `numpy`, `supervision`, `roboflow`
* **Platform:** Kaggle/Google Colab

## 📂 Dataset Information

The project uses the **Arabic License Plate Dataset** hosted on Roboflow:

* **Workspace:** `alpr-system`
* **Project:** `arabic-plates`
* **Format:** YOLOv8

## 🔧 Installation & Setup

1. **Clone the repository:**
```bash
git clone <your-repository-link>

```


2. **Install dependencies:**
The notebook includes commands to install the necessary packages:
```python
pip install ultralytics supervision roboflow

```


3. **API Configuration:**
Ensure you have your Roboflow API key ready to download the dataset within the notebook.

## 📊 Results

The notebook includes test results on various Egyptian license plate styles, including:

* Private vehicle plates.
* Truck license plates.
* Older generation plates.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

---

**Author:** [Ashraqt Tamer]

