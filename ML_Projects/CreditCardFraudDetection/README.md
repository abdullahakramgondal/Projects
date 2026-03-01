# 💳 Credit Card Fraud Detection (Machine Learning)

## 📌 Project Overview
This project focuses on building a **Machine Learning classification model**
to detect **fraudulent credit card transactions** from highly imbalanced data.

The primary objective is **not achieving high accuracy**, but learning how to:
- Handle extreme class imbalance
- Select the right evaluation metrics
- Make decisions based on **business risk**

This project follows an **industry-style ML workflow**, emphasizing reasoning
over blind model usage.

---

## 🧠 Problem Statement
Given transaction-level data, the task is to correctly classify whether a
transaction is **Legitimate (0)** or **Fraudulent (1)**.

This is a **high-risk classification problem**, where:
- Missing a fraud (False Negative) is very costly
- Incorrectly flagging a legit transaction (False Positive) is inconvenient
but manageable

---

## 📂 Dataset Understanding
Key characteristics of the dataset:
- Extremely imbalanced classes  
  - Legit transactions ≈ 99.8%
  - Fraud transactions ≈ 0.2%
- Numerical features only
- Target column: **Class**

This imbalance makes **accuracy a misleading metric**.

---

## ⚙️ Technologies & Tools Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔄 Data Preparation Strategy
- Dataset was split using **stratified sampling** to preserve class ratios
- No artificial balancing (undersampling) was applied to avoid fake reality
- Focus remained on **real-world data distribution**

---

## 🧩 Modeling Approach
### Phase 1: Baseline Model
- **Logistic Regression** was used as a simple, interpretable baseline
- Served as a reference point for all evaluations

### Phase 2: Confusion Matrix Analysis
- Model performance was evaluated using a **confusion matrix**
- Clear separation of:
  - True Positives
  - False Positives
  - False Negatives
  - True Negatives

Special focus was placed on **False Negatives**, as missing fraud is the
highest business risk.

---

## 🎯 Evaluation Metrics (Business-Oriented)
Instead of accuracy, the following metrics were prioritized:
- **Recall** – ability to catch fraud cases
- **Precision** – correctness of fraud predictions
- **Confusion Matrix** – full error breakdown

Accuracy was intentionally **de-emphasized** due to class imbalance.

---

## 🔧 Threshold Tuning
- Default threshold (0.5) was adjusted using `predict_proba`
- Multiple thresholds (0.1 – 0.4) were tested
- Trade-offs between Recall and Precision were analyzed

This step demonstrated that **model output probabilities are more important
than raw predictions**.

---

## ✅ Key Insights & Learnings
- Accuracy can be useless in imbalanced classification problems
- Recall is critical when the cost of missing positives is high
- Threshold tuning is a powerful alternative to complex models
- Confusion matrix provides deeper insight than any single metric
- Business context must guide model decisions

---

## 📌 Notes
- This project emphasizes **decision-making under risk**
- The model is treated as a **decision-support system**, not a final authority

---

## 🚀 Future Improvements
- Cost-sensitive learning
- Ensemble models for better recall control
- Monitoring data drift in production

---

## 👤 Author
Abdullah Akram  
Aspiring Machine Learning Engineer
