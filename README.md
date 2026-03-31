# Deep-Learning-Freshness-classification-model
A convolutional neural network (CNN) was developed to classify binary images and distinguish between "fresh" and "spoiled" food. This model is based on TensorFlow/Keras. the model achieved high accuracy in determining freshness, demonstrating its effectiveness in applying deep learning techniques to quality control and reducing food waste.
# 🧠 Product Freshness Classification Using Deep Learning

### Convolutional Neural Network Model for Image-Based Quality Assessment | Quality 4.0

---

## 📌 Overview

This repository contains a Convolutional Neural Network (CNN) model designed to classify product freshness from images. The project applies computer vision and deep learning techniques to automate quality control, supporting modern Quality 4.0 practices.

... ---

## 🎯 Objectives

* Building a model for classifying images (fresh and non-fresh)
* Quality control processes using artificial intelligence
* Cause and effect
* Supporting the digital transformation of quality systems

---

## 🧩Model Architecture

The model was created using **Sequential CNN**:

* Conv2D (32 filters) → ReLU
* Max Bowling 2D
* Conv2D (64 filters) → ReLU
* Max Bowling 2D
* Conv2D (128 filters) → ReLU
* Max Bowling 2D
* Flattening
* Dense (512) → ReLU
* Leakage (0.5)
* Output layer (X-ray)

---

## ⚙️ Training Configuration

* **Enhancer:** Adam
* **Loss Function:** Binary Entropy
* **Metrics:** Resolution
* **Number of Stages:** 10

---

## 📁 Project Structure

```bash


├── data/ # Dataset (Training/Verification)
├── model/ # Saved Models
├── notebook/ # Jupyter Notebooks
└── README.md


---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/freshness-classification.git
cd freshness-classification

```

### 2. Install the Dependencies

```bash
pip install -r requirements.txt

```

### 3. Train the Model

```bash
python train.py

```

---

## 🌐 Quality 4.0 Contribution

This project complies with Quality 4.0 4.0** Through:

* 🔍 Enable **data-driven quality decisions**
* 🤖 Automate inspection processes
* 📈 Support continuous improvement through data learning
* 🔗 Integrable with smart electronics (IoT/Smart Manufacturing)

---

## 📊 Applications

* Food freshness detection
* Agriculture monitoring
* Supply chain quality monitoring
* Smart factories

---

## ⚠️ Limitations

* Relies on data quality (dataset)
* Requires retraining when changing product types
* Data quality improvement

---

## 🔮 Future work

* Classification by degree of corruption
* Deployment (web/mobile application)

---

## 👨‍💻 Author
Yusha Alhussein
---
