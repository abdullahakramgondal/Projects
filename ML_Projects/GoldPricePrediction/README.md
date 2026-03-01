# 🪙 Gold Price Prediction (Time Series Regression)

## 📌 Project Overview
This project focuses on predicting **gold prices** using historical time-based
data. Unlike standard regression problems, this project emphasizes **time
dependency**, sequence awareness, and proper feature construction.

The main objective is to understand **how time-series data should be handled
differently** from non-time-series datasets in Machine Learning.

---

## 🧠 Problem Statement
Given historical gold price data, the task is to predict future prices based on
past observations.

This is a **time-series regression problem**, where the order of data matters
and random data splitting can lead to misleading results.

---

## 📂 Dataset Understanding
Key characteristics of the dataset:
- Sequential, time-ordered data
- Strong dependency on past values
- No random relationship between rows

Because of this:
- Shuffling the data is **not appropriate**
- Temporal patterns must be preserved

---

## ⚙️ Technologies & Tools Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 🔄 Data Preparation & Feature Engineering
- Data was kept in **chronological order**
- **Lag features** were created (e.g., previous day prices)
- These lag features allowed the model to learn temporal patterns
- No random train-test split was used

This step was critical to convert time-series data into a supervised learning
format.

---

## 🧩 Modeling Approach
### Phase 1: Baseline Model
- A simple regression model was used as a baseline
- Helped establish reference performance

### Phase 2: Lag-Based Modeling
- Lag features were added to capture time dependency
- Demonstrated that **feature engineering can outperform model complexity**

---

## 📊 Evaluation Metrics
Model performance was evaluated using:
- **R² Score** – overall trend fitting
- **RMSE (Root Mean Squared Error)** – magnitude of prediction errors

RMSE was treated as the most important metric to detect **large error jumps**,
even when R² appeared acceptable.

---

## ✅ Key Insights & Learnings
- Time-series data requires a different ML strategy
- Lag features are often more powerful than advanced models
- Random splitting breaks temporal learning
- RMSE reveals risk hidden behind good R² values
- Simple models can perform very well with the right data representation

---

## 📌 Notes
- This project emphasizes **respecting data structure**
- Focus remained on reasoning, not algorithm complexity

---

## 🚀 Future Improvements
- Try rolling window features
- Add trend and seasonality components
- Explore advanced time-series models

---

## 👤 Author
Abdullah Akram  
Aspiring Machine Learning Engineer
