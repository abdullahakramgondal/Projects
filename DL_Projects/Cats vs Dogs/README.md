# Cats vs Dogs Image Classification (Deep Learning)

## 📌 Project Overview
This project focuses on building a **Deep Learning image classification model**
to distinguish between **Cats** and **Dogs** using Convolutional Neural Networks (CNN).

The goal of this project is not just accuracy, but to understand the **complete
end-to-end Deep Learning workflow**, including data loading, preprocessing,
model training, evaluation, and improvement strategies.

---

## 🧠 Problem Statement
Given an input image, the model should correctly classify whether the image
contains a **Cat** or a **Dog**.

This is a **binary image classification** problem commonly used to benchmark
computer vision pipelines and model generalization techniques.

---

## 📂 Dataset Structure
The dataset was organized into the following directory structure:

train/
- cats/
- dogs/

test/
- cats/
- dogs/

Each folder contains labeled images corresponding to its class.

---

## ⚙️ Technologies & Tools Used
- Python  
- NumPy  
- TensorFlow / Keras  
- ImageDataGenerator  
- Convolutional Neural Networks (CNN)  
- Transfer Learning  
- Jupyter Notebook  

---

## 🧪 Model Development Strategy (4 Phases)

### Phase 1: Baseline CNN
- Built a simple CNN model from scratch
- Established baseline performance
- Observed overfitting behavior

---

### Phase 2: Regularization & Training Control
- Added **Dropout layers** to reduce overfitting
- Used **Early Stopping** to prevent unnecessary training
- Improved validation stability

---

### Phase 3: Data Augmentation
- Applied real-time data augmentation using `ImageDataGenerator`
- Improved generalization on unseen images
- Reduced dependency on limited training data

---

### Phase 4: Transfer Learning
- Used a pre-trained CNN model as a feature extractor
- Fine-tuned top layers for Cats vs Dogs classification
- Achieved better performance with fewer epochs

---

## 📊 Model Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- Confusion Matrix

The confusion matrix provided deeper insights into:
- False positives
- False negatives
- Class-wise performance

---

## ✅ Results
The model showed consistent improvement across all four phases.

The final model demonstrated strong generalization performance on test data,
highlighting the effectiveness of a **step-by-step model improvement approach**.

---

## 🚀 Key Learnings
- Importance of starting with a baseline model
- How dropout and early stopping control overfitting
- Impact of data augmentation on model robustness
- Practical benefits of transfer learning
- Why confusion matrix is more informative than accuracy alone

---

## 📌 Notes
- Dataset images are not included due to size limitations
- This repository focuses on **learning process and experimentation**, not just results

---

## 👤 Author
Abdullah Akram  
Aspiring Machine Learning & Deep Learning Engineer
