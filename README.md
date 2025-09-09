# Churn-Simple-Linear-Regression
Simple Linear Regression on Telco Churn data: predicting **Total Day Charge** from **Total Day Minutes** with near-perfect accuracy, validating billing transparency, improving revenue forecasting, and supporting customer strategy.

---

## 📌 Overview
This project is part of my **Data Analysis Internship at Codveda Technologies**.  
I built a **Simple Linear Regression** model on telecom churn data:  

- **Churn A (80%)** → model training  
- **Churn B (20%)** → model testing  

**Objective:** Predict **Total Day Charge** from **Total Day Minutes**.  

---

## 📂 Dataset
- **Churn A (80%)** → Training dataset (2,666 rows)  
- **Churn B (20%)** → Testing dataset (667 rows)  

**Key Variables:**  
- `Total day minutes` → Independent (X)  
- `Total day charge` → Dependent (y)  

---

## ⚙️ Workflow
1. Import libraries (`pandas`, `matplotlib`, `seaborn`, `sklearn`).  
2. Load datasets (Churn A & B).  
3. Select features: minutes (X), charges (y).  
4. Build regression model (`LinearRegression`).  
5. Predict charges for train & test sets.  
6. Evaluate with **R² and MSE**.  
7. Visualize results (scatter, line, residual plots).  
8. Draw business insights.  

---

## 📈 Results

### 🔹 Model Parameters
- **Intercept:** ~0.0006 → negligible baseline (no hidden fixed charges).  
- **Coefficient:** ~0.17 → charge increases by 0.17 per minute.  

### 🔹 Model Evaluation
| Dataset   | R² Score | MSE            |
|-----------|----------|----------------|
| Train (A) | ≈ 1.0    | 8.18 × 10⁻⁶    |
| Test (B)  | ≈ 1.0    | 8.24 × 10⁻⁶    |

📌 **Interpretation:** The model explains nearly all variation with minimal error.  

### 🔹 Visualizations
- **Scatter Plot:** Actual vs Predicted → perfect overlap on y=x line.  
- **Line Plot:** First 50 records → Actual & Predicted curves overlap.  
- **Residual Plot:** Random scatter around zero → unbiased predictions.  

---

## 📊 Key Insights
- Charges increase **linearly** at ~0.17 per minute.  
- Billing is **transparent** (no fixed charges).  
- Model is **accurate & generalizes** well (Train ≈ Test performance).  

---

## 💼 Business Implications
- **Telecom Operators:** Builds trust in billing & aids compliance.  
- **Finance/Banking Analysts:** Enables reliable revenue forecasting.  
- **Customer Strategy Teams:** Helps test tariff scenarios & discounts.  

---

## 📂 Project Structure

├── Churn_Simple_Linear_Regression.ipynb   # Google Colab Notebook with regression workflow  
├── data/                                  # Folder containing dataset(s)  
│   ├── churn-bigml-20.csv                 # Part 1 of churn dataset  
│   └── churn-bigml-80.csv                 # Part 2 of churn dataset  
├── README.md                              # Project summary

---

## 🔗 Link  

- **Open in Google Colab**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OcSpice/Churn-Simple-Linear-Regression/blob/main/Churn_Simple_Linear_Regression.ipynb)

- **LinkedIn Post:** Coming Soon  
- **Video Walkthrough:** Coming Soon
