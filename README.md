# Loan Default Prediction

This project aims to predict the probability of loan default for each customer using machine learning techniques, helping financial institutions make data-driven approval decisions and assess customer risk profiles.

## 📊 Problem Statement

Financial institutions face challenges in identifying which customers are most likely to default on their loans. By predicting default probability, they can reduce financial risk and improve loan portfolio quality.

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost, Random Forest
- Matplotlib, Seaborn

## 🚀 Project Workflow

1️⃣ **Data Cleaning & EDA**  
- Handled missing values and outliers
- Analyzed distributions and correlations

2️⃣ **Feature Engineering**  
- Label encoding for categorical columns
- Scaling of numerical columns
- Feature importance analysis

3️⃣ **Model Building**  
- Trained Random Forest and XGBoost classifiers
- Evaluated using confusion matrix, classification report, ROC-AUC score

4️⃣ **Risk Probability Calculation**  
- Predicted default probability for each customer
- Created new columns: `default_probability`, `risk_assessment`, `business_decision`

5️⃣ **Business Decision Support**  
- Customers classified into Low, Medium, and High Risk
- Provided approval or reject recommendations

## ✅ Key Results

- **ROC-AUC Score**: 0.95 (XGBoost)
- High recall for default class (important to catch risky customers)

## 💼 Business Impact

- Enables data-driven loan approval
- Helps reduce bad debt and optimize risk strategy
- Supports compliance and credit risk management

## 📄 Files Included

- `loan_default_prediction.ipynb`: Main Jupyter notebook with full analysis and modeling
- `README.md`: Project summary and workflow
- [Optional] Data file (if included)

---

## 📬 Contact

If you'd like to discuss this project or explore potential collaborations, feel free to reach out!

---

