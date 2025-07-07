# 🧠 Brain Tumor Detection – ResNet50, EfficientNetB0, and MobileNetV2 Models

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Framework](https://img.shields.io/badge/Framework-TensorFlow%2FKeras-orange)
![Models](https://img.shields.io/badge/Models-ResNet50%2CEfficientNetB0%2CMobileNetV2-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

![Brain Tumor Banner](https://www.mathewsopenaccess.com/userfiles/images/Psychiatry/Figure%146(2).png)

This project extends a well-structured notebook originally created by **Ruslan Klymentiev**, which explores CNN-based classification of brain MRI scans.

In my version, I implemented and compared **three different pretrained CNN models**: **ResNet50**, **EfficientNetB0**, and **MobileNetV2**, using transfer learning and fine-tuning strategies to improve classification performance.

---

## 🔍 Key Highlights

- Applied and compared ResNet50, EfficientNetB0, and MobileNetV2 architectures
- Used transfer learning with layer freezing and custom top layers
- Handled class imbalance with SMOTE and focal loss techniques
- Added training visualizations and performance metrics (accuracy, F1-score, etc.)

---

## 🧠 Dataset

- Brain MRI Images for Brain Tumor Detection  
- [Kaggle Dataset Link](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Note on Model Files

> The `.h5` model weights are **not included** due to GitHub’s 100MB limit.  
> To use them:
> - Let `tensorflow.keras.applications` automatically download them during runtime
> - Or download manually from: [Keras Applications GitHub](https://github.com/keras-team/keras-applications/releases)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/abdulrahmanzahir/Brain-Tumor-Detection
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Abdulrahman_brain_tumor_detection.ipynb
   ```

3. Run all cells after ensuring the dataset is properly located and model files are accessible.

---

## 🙏 Acknowledgements

- Original notebook author: [Ruslan Klymentiev](https://www.kaggle.com/ruslankl)
- Dataset: [Navoneel Chakrabarty](https://www.kaggle.com/navoneel)
- Current version and models implemented by: **Abdulrahman Zahir**

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
Used and adapted for educational purposes with full attribution to original authors.
