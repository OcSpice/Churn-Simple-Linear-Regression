# Churn-Simple-Linear-Regression
Simple Linear Regression on Telco Churn data: predicting day charges from call minutes with near-perfect accuracy, validating billing transparency, improving revenue forecasting, and supporting customer strategy.

---

# Level 2 Task 1 – Simple Linear Regression  

---

## 📌 Overview  
This project is part of my **Data Analysis Internship at Codveda Technologies**.  

I performed a **Simple Linear Regression** using the **Churn A (80%)** dataset to build the model and the **Churn B (20%)** dataset to evaluate it.  

**Objective:** Predict **Total Day Charge** (dependent variable) from **Total Day Minutes** (independent variable).  

---

## Dataset  
- **Churn A (80%)** → model building  
- **Churn B (20%)** → model evaluation  

Key Columns used:  
- `Total day minutes` → Independent variable (X)  
- `Total day charge` → Dependent variable (y)  

---

## Workflow  
This task followed a supervised learning workflow using the provided split:  
- **Churn A (80%)** → regression model building  
- **Churn B (20%)** → model performance evaluation  
- **Model fitting** → linear regression line between minutes and charges  
- **Evaluation** → metrics (R², MSE)  
- **Visualization & Interpretation** → scatterplot, regression line, residuals  

---

## 🔎 Steps in Analysis
1. **Data Cleaning**  
   - Handled missing values (Age, Cabin, Embarked).  
   - Dropped irrelevant index columns.  
   - Standardized categorical values for consistency.  

2. **Survival Distribution**  
   - Plotted how many passengers survived vs. not survived.  

3. **Demographic Analysis**  
   - Compared survival by gender and age groups.  

4. **Socioeconomic Analysis**  
   - Examined class (Pclass) and fare against survival rates.  

5. **Embarkation Analysis**  
   - Analyzed survival rates by port of embarkation (C, Q, S).  

6. **Visualizations**  
   - Used histograms, bar charts, and boxplots for clarity.

---

## Results  

### Model Parameters  
- **Intercept:** ~0.0006 (nearly zero, no hidden fixed charge)  
- **Coefficient:** ~0.17 → each additional minute adds ~0.17 to the charge  

### Model Evaluation  
- **R² Score:** ≈ 1.0 → almost perfect fit  
- **MSE:** ≈ 0 → negligible error  

### Visualizations  
- **Regression Plot:** Scatterplot of actual values with regression line fit  
- **Residual Plot:** Residuals scattered randomly around zero → no systematic error  

---

## 📊 Key Insights  
- **Linear Relationship:** Charges increase by ~0.17 per minute of usage.  
- **Model Accuracy:** R² ≈ 1.0 and MSE ≈ 0 → nearly perfect predictions.

- **Intercept Analysis:** No hidden fixed charges (intercept negligible).

---

## 💼 Business Implications
Validates billing transparency, enables accurate revenue forecasting, and supports predictable pricing strategies.  

---

## 📂 Project Structure

├── Churn_Simple_Linear_Regression.ipynb   # Google Colab Notebook with regression workflow  
├── data/                                  # Folder containing dataset(s)  
│   ├── churn-bigml-20.csv                 # Part 1 of churn dataset  
│   └── churn-bigml-80.csv                 # Part 2 of churn dataset  
├── README.md                              # Project documentation

---

## 🔗 Links  
- **Open in Google Colab**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OcSpice/Sentiment-Dataset-EDA/blob/main/Churn_Simple_Linear_Regression.ipynb)  

- **LinkedIn Post:** Coming Soon  
- **Video Walkthrough:** Coming Soon
