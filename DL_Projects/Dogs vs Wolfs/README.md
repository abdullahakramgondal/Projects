# Dogs vs Wolves Image Classification (Deep Learning)

## 📌 Project Overview
This project focuses on building a **Deep Learning image classification model**
to distinguish between **Dogs** and **Wolves** using Convolutional Neural Networks (CNN).

The primary objective was not only to achieve accuracy, but to **understand how
model complexity, regularization, data augmentation, and transfer learning
affect real-world decision making**.

---

## 🧠 Problem Statement
Given an input image, the model should correctly classify whether the image
contains a **Dog** or a **Wolf**.

This is a challenging **binary image classification** problem because:
- Dogs and wolves share very similar visual patterns
- Small errors can lead to incorrect real-world decisions
- Threshold tuning is critical to control misclassifications

---

## 📂 Dataset Structure
The dataset was organized as follows:

train/
- dog/
- wolf/

test/
- dog/
- wolf/

---

## ⚙️ Technologies & Tools Used
- Python  
- NumPy  
- TensorFlow / Keras  
- ImageDataGenerator  
- Convolutional Neural Networks (CNN)  
- Transfer Learning  
- Threshold Tuning  
- Jupyter Notebook  

---

## 🧪 Model Development Phases (Core Learning)

### 🔹 Phase 1: Baseline CNN
- Built a simple CNN model from scratch
- Used basic convolution and pooling layers
- Goal: establish a baseline and observe underfitting/overfitting behavior

---

### 🔹 Phase 2: Regularization & Training Control
- Added **Dropout layers** to reduce overfitting
- Applied **Early Stopping** to prevent unnecessary training
- Improved model stability and generalization

---

### 🔹 Phase 3: Data Augmentation
- Applied real-time augmentation using `ImageDataGenerator`
- Included rotations, zoom, shifts, and flips
- Helped the model generalize better on unseen images

---

### 🔹 Phase 4: Transfer Learning
- Implemented **Transfer Learning** using a pre-trained CNN
- Leveraged learned visual features from large-scale datasets
- Fine-tuned top layers for Dogs vs Wolves classification
- Achieved improved feature representation with fewer training samples

---

## 🎯 Threshold Tuning (Key Highlight)
Instead of relying on default prediction thresholds:
- Model probability outputs were analyzed
- Multiple threshold values were tested (e.g., 0.2, 0.3, 0.4, 0.5)
- Confusion matrices were evaluated at each threshold

This allowed:
- Better control over false positives and false negatives
- Threshold selection based on **problem sensitivity**, not just accuracy

---

## 📊 Model Evaluation
Evaluation focused on:
- Accuracy
- Precision
- Recall
- Confusion Matrix

Special attention was given to:
- False Negatives (missing a wolf)
- False Positives (misclassifying a dog as a wolf)

---

## ✅ Results
The final model demonstrated improved robustness across all phases.

Transfer learning combined with threshold tuning provided better
control over classification behavior compared to a simple CNN baseline.

---

## 🚀 Key Learnings
- Building models in phases improves understanding and reliability
- Regularization techniques are essential in deep learning
- Data augmentation significantly improves generalization
- Transfer learning is powerful for limited datasets
- Threshold tuning is critical for high-risk classification problems

---

## 📌 Notes
- Dataset images are not included due to size limitations
- This project emphasizes **model behavior and decision control**
rather than raw accuracy

---

## 👤 Author
Abdullah Akram  
Aspiring Machine Learning & Deep Learning Engineer
