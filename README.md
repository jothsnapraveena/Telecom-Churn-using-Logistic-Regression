# **Telecom Churn Prediction**

## 🌟 Project Overview
This project aims to predict customer churn for a telecom company, enabling targeted retention strategies to reduce churn rates and improve revenue. The model analyzes customer data, including demographics, service usage, and billing information, to identify at-risk customers.

## 🔍 Key Features
- **Churn Prediction Model**: Built using logistic regression to identify customers likely to discontinue services.
- **Feature Selection**: Evaluated multicollinearity using **Variance Inflation Factor (VIF)** to identify key predictors:
- **Model Optimization**: Balanced sensitivity (**61.68%**) and specificity (**84.69%**) using **ROC curve analysis**.

## 🛠️ Technology Stack
- **Programming Language**: Python
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Tools**: Jupyter Notebook

## 📊 Dataset
- Dataset of **10,000 customers** with the following key features:
  - **Customer Demographics**: Gender, SeniorCitizen, Partner, Dependents
  - **Service Usage**: InternetService, StreamingTV, TechSupport, etc.
  - **Billing Details**: MonthlyCharges, TotalCharges, PaymentMethod
  - **Target Variable**: Churn (whether a customer has churned or not)

## ⚙️ Implementation
1. **Data Preprocessing**:
   - Handled missing values and encoded categorical variables.
   - Scaled numerical features to ensure uniformity in model training.
2. **Feature Engineering**:
   - Analyzed multicollinearity using **VIF** to select impactful predictors.
3. **Model Training**:
   - Trained a logistic regression model on the processed dataset.
   - Optimized the cutoff threshold using **ROC curve analysis**.
4. **Model Evaluation**:
   - **Accuracy**: 78.34%
   - **Sensitivity**: 61.68%
   - **Specificity**: 84.69%
   - **Confusion Matrix**:
     ```
     [[1294,  234],
      [ 223,  359]]
     ```

## ✅ Results
- Correctly identified **359 churned customers** (True Positives) while minimizing false positives.
- Delivered actionable insights to target at-risk customers effectively.

## 📈 Business Impact
- Helps telecom companies reduce churn rates by targeting high-risk customers with retention strategies.
- Increases customer lifetime value and boosts revenue through proactive interventions.
