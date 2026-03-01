# 🚗 Car Price Prediction (Machine Learning)

## 📌 Project Overview
This project focuses on building a **Machine Learning regression model**
to predict the **selling price of used cars** based on multiple features
such as year, present price, kilometers driven, fuel type, transmission,
seller type, and ownership.

The primary goal of this project is to learn **how to approach a real-world
non-time-series regression problem in an industry-oriented way**, rather
than just applying advanced models blindly.

---

## 🧠 Problem Statement
Given historical data of used cars, the task is to **estimate the selling
price of a car** based on its attributes.

This is a **regression problem** where understanding feature impact and
error magnitude is more important than achieving a high score.

---

## 📂 Dataset Understanding
The dataset contains:
- Numerical features (Year, Present Price, Kms Driven)
- Categorical features (Fuel Type, Seller Type, Transmission, Owner)
- Target variable: **Selling Price**

Special attention was required due to:
- Rare categories (e.g., CNG fuel type)
- Ownership outliers (multiple owners)
- Feature scale differences

---

## ⚙️ Technologies & Tools Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Data Preprocessing & Feature Engineering
- Categorical variables were encoded
- Rare categories were merged to avoid noisy learning
- Ownership feature was simplified to reduce outlier impact
- Focus was placed on **clean, meaningful features** rather than complexity

---

## 🧩 Modeling Approach
### Phase 1: Baseline Model
- **Linear Regression** was used as a baseline
- Established a reference performance for comparison

### Phase 2: Regularized Model
- **Lasso Regression** was applied
- Helped in:
  - Feature selection
  - Reducing the impact of less important variables
  - Improving model interpretability

> Scaling was applied for Lasso Regression, as required by regularization.

---

## 📊 Evaluation Metrics
Model performance was evaluated using:
- **R² Score** – overall fit
- **MAE (Mean Absolute Error)** – average prediction error
- **RMSE (Root Mean Squared Error)** – penalty for large mistakes

RMSE was given special importance to detect **large error jumps**, even
when R² appeared strong.

---

## ✅ Key Insights & Learnings
- Simple models can perform very well with the right approach
- Feature engineering has more impact than choosing advanced models
- Lasso Regression is effective for feature importance analysis
- RMSE is critical for understanding real-world prediction risk
- Handling rare categories improves generalization

---

## 📌 Notes
- This project emphasizes **thinking like an ML engineer**, not just coding
- Focus was on interpretability, stability, and business relevance

---

## 🚀 Future Improvements
- Try ElasticNet for balanced regularization
- Add cross-validation comparison for robustness
- Explore interaction features

---

## 👤 Author
Abdullah Akram  
Aspiring Machine Learning Engineer
