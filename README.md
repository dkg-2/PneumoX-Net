
# 🩺 PneumoX-Net - Chest X-ray Pneumonia Detection Model

[![Hugging Face Spaces](https://img.shields.io/badge/Live%20Demo-Hugging%20Face-blue?logo=huggingface)](https://huggingface.co/spaces/dkg-2/PneumoX-Net)

PneumoX-Net is a deep learning-powered diagnostic tool that classifies **Pneumonia** vs **Normal** chest X-rays. It is designed to aid early detection and medical decision-making, especially in resource-constrained areas.

---

## 🧠 Model Overview

PneumoX-Net is based on **MobileNetV2**, a lightweight convolutional neural network fine-tuned on a curated dataset of chest X-rays. It performs binary classification with high diagnostic accuracy.

---

## 📊 Evaluation Metrics

| Metric       | Score   |
|--------------|---------|
| **Accuracy** | 96.18%  |
| **Precision**| 97.60%  |
| **Recall**   | 99.12%  |
| **F1-Score** | 97.37%  |
| **AUC**      | 99.25%  |
| **Log Loss** | 0.1388  |

> ✅ **High Recall** ensures few false negatives, which is critical for medical screening tools.

---

## 📦 Dataset

- **Name**: Chest X-ray Images (Pneumonia)
- **Source**: [Kaggle - Paul Mooney](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Description**: A labeled dataset containing 5,863 chest X-ray images (JPEG) categorized into:
  - `PNEUMONIA`
  - `NORMAL`

---

## 🛠 Technology Stack

- 🔹 **Deep Learning**: TensorFlow / Keras
- 🔹 **Architecture**: MobileNetV2 (Transfer Learning)
- 🔹 **Image Processing**: OpenCV, Pillow (PIL)
- 🔹 **Visualization**: Matplotlib, Seaborn
- 🔹 **Deployment**: Gradio + Hugging Face Spaces

---

## 🔗 Resources

- 📓 **Model Training Notebook (Colab)**:  
  👉 [Open in Colab](https://colab.research.google.com/drive/1pwfrmO31SE7bxQdCDwPcoQJqxJjpi1st?usp=sharing)

- 🧪 **Live Demo (Hugging Face)**:  
  👉 [Try PneumoX-Net](https://huggingface.co/spaces/dkg-2/PneumoX-Net)

---


## 💻 Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/dkg-2/PneumoX-Net.git
cd PneumoX-Net
pip install -r requirements.txt
python app/app.py

