#Brain Tumor Segmentation using U-Net & PyTorch

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C)
![License](https://img.shields.io/badge/License-MIT-green)

An end-to-end Deep Learning project for automated brain tumor segmentation on MRI scans using a custom **U-Net** architecture implemented in **PyTorch**.

---

## 📌 Project Overview
Accurate identification of brain lesions plays a critical role in computer-aided medical diagnosis. This project leverages the **U-Net** architecture to perform binary semantic segmentation on brain MRI images to isolate tumor regions from surrounding tissues.

---

## 🛠️ Tech Stack
* **Deep Learning Framework:** PyTorch
* **Data Processing & CV:** OpenCV, NumPy, Pandas
* **Visualization:** Matplotlib
* **Environment:** Google Colab (T4 GPU)

---

## 📊 Dataset
* **Dataset:** [Kaggle Brain MRI Segmentation Dataset](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation)
* **Content:** Brain MRI scans along with ground-truth binary masks indicating tumor regions.

---

## 🏗️ Architecture & Implementation
* **Encoder (Contracting Path):** Feature extraction via double convolution blocks with BatchNorm, ReLU, and MaxPool2d.
* **Bottleneck:** High-level feature representation layer.
* **Decoder (Expanding Path):** Transposed convolutions paired with **Skip Connections** to maintain spatial resolution.

---

## 📈 Quantitative Results
* **Dice Similarity Coefficient:** `55.81%`
* **IoU (Intersection over Union) Score:** `52.39%`

---

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone [https://github.com/hananeaouragh-ops/Brain-Tumor-Segmentation-UNet.git](https://github.com/hananeaouragh-ops/Brain-Tumor-Segmentation-UNet.git)
