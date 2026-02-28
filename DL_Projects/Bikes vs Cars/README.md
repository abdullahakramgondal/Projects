# Car vs Bike Image Classification (Deep Learning)

## 📌 Project Overview
This project focuses on building a Deep Learning image classification model
to distinguish between **Cars** and **Bikes** using Convolutional Neural Networks (CNN).

The goal of this project is not just accuracy, but to understand the **complete
end-to-end Deep Learning workflow**, including data loading, preprocessing,
model training, and evaluation.

---

## 🧠 Problem Statement
Given an input image, the model should correctly classify whether the image
contains a **Car** or a **Bike**.

This is a **binary image classification** problem commonly encountered in
real-world computer vision applications such as:
- Traffic monitoring
- Automated surveillance
- Smart transportation systems

---

## 📂 Dataset Structure
The dataset was organized into the following directory structure:

train/
- car/
- bike/

test/
- car/
- bike/

Each folder contains labeled images corresponding to its class.

---

## ⚙️ Technologies & Tools Used
- Python
- NumPy
- TensorFlow / Keras
- ImageDataGenerator
- Convolutional Neural Networks (CNN)
- Jupyter Notebook

---

## 🔄 Data Preprocessing
- Images were resized to a fixed shape
- Pixel values were normalized (rescaling)
- Training and validation data were loaded using `ImageDataGenerator`
- Real-time data augmentation was applied to improve generalization

---

## 🧩 Model Architecture
The CNN model consists of:
- Convolutional layers for feature extraction
- MaxPooling layers to reduce spatial dimensions
- Flatten layer to convert features into a vector
- Dense (Fully Connected) layers for classification
- Sigmoid activation for binary output

---

## 📊 Model Training
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy
- Trained for multiple epochs to observe learning behavior

---

## ✅ Results
The model successfully learned visual patterns distinguishing cars from bikes
and achieved good accuracy on the validation dataset.

This project demonstrates how a **simple CNN architecture** can effectively
solve a binary image classification problem.

---

## 🚀 Key Learnings
- Understanding image data pipelines
- Working with ImageDataGenerator
- CNN layer-by-layer intuition
- Avoiding unnecessary complexity
- Importance of data preprocessing in Deep Learning
- Confusion Matrix working, understanding and importance
---

## 📌 Notes
- Dataset images are not included due to size limitations
- This repository focuses on code, architecture, and learning workflow

---

📎 Future Improvements
- Use transfer learning (MobileNet / ResNet)
- Experiment with different augmentation strategies

---

## 👤 Author
Abdullah Akram  
Aspiring Machine Learning & Deep Learning Engineer
