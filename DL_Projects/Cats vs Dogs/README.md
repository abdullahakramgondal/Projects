Cats vs Dogs Image Classification (Deep Learning)
📌 Project Overview

This project focuses on building a Deep Learning image classification system
to distinguish between Cats and Dogs using Convolutional Neural Networks (CNN).
The primary goal of this project was not just achieving accuracy, but
experimenting, controlling overfitting, and improving generalization
through a structured, multi-phase approach.

🧠 Problem Statement

Given an input image, the model should correctly classify whether the image
contains a Cat or a Dog.
This is a binary image classification problem commonly used to evaluate
real-world deep learning pipelines and model improvement strategies.

📂 Dataset Structure

The dataset followed a standard image classification directory structure:
train/
cats/
dogs/

test/
cats/
dogs/
Images were labeled based on their respective folders.

⚙️ Technologies & Tools Used

Python
NumPy
TensorFlow / Keras
ImageDataGenerator
Convolutional Neural Networks (CNN)
Transfer Learning
Jupyter Notebook

🧪 Model Development — 4 Phase Approach
Phase 1: Baseline CNN Model

Built a simple CNN from scratch
Used convolution, pooling, and dense layers
Established a baseline performance
Observed signs of overfitting
➡ Purpose: Understand raw model behavior without controls

Phase 2: Regularization & Training Control

Added Dropout layers to reduce overfitting
Implemented Early Stopping to prevent unnecessary training
Improved model stability and validation performance

➡ Purpose: Control model complexity and learning behavior

Phase 3: Data Augmentation

Applied real-time data augmentation using ImageDataGenerator
Techniques included rotation, flipping, and zooming
Helped the model generalize better on unseen data

➡ Purpose: Simulate real-world image variations

Phase 4: Transfer Learning

Used a pre-trained CNN model as a feature extractor
Fine-tuned higher layers for Cats vs Dogs classification
Achieved improved performance with fewer training epochs

➡ Purpose: Leverage learned visual features from large-scale datasets

📊 Model Evaluation

Evaluated using accuracy, precision, recall, and confusion matrix
Confusion matrix helped analyze:
Misclassification patterns
False positives vs false negatives
Allowed better understanding beyond accuracy alone

✅ Results

Through phased improvements, the model showed consistent gains in
generalization and stability.
The final model demonstrated strong performance on unseen test data,
highlighting the effectiveness of structured experimentation.

🚀 Key Learnings

Importance of baseline models before optimization
Managing overfitting using dropout and early stopping
Impact of data augmentation on generalization
Practical benefits of transfer learning
Why confusion matrix matters more than accuracy alone

📌 Notes

Dataset images are not included due to size limitations
Focus of this repository is on learning workflow and model evolution

👤 Author

Abdullah Akram
Aspiring Machine Learning & Deep Learning Engineer
