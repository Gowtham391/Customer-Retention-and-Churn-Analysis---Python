# Customer Retention and Churn Analysis

A machine learning project analyzing customer churn patterns and building predictive models to identify customers at risk of leaving.

## 📊 Project Overview

This project uses simulated telecom customer data to:
- Analyze factors influencing customer churn
- Build predictive models to identify at-risk customers
- Compare multiple machine learning algorithms
- Visualize churn patterns and model performance

## 🔧 Technologies Used

- **Python 3.x**
- **Libraries:**
  - pandas - Data manipulation
  - numpy - Numerical operations
  - scikit-learn - Machine learning models
  - matplotlib - Data visualization

## 📁 Dataset

Simulated dataset with 1,500 customer records containing:
- **Customer Demographics:** Gender, Senior Citizen status, Partner, Dependents
- **Services:** Phone Service, Internet Service type
- **Account Info:** Tenure, Monthly Charges, Total Charges
- **Target Variable:** Churn (Yes/No)

## 🤖 Models Implemented

1. **Logistic Regression**
   - Accuracy: 75%
   - Good baseline model

2. **Random Forest Classifier**
   - 150 estimators
   - Accuracy: 72%
   - Better recall for minority class

## 📈 Key Findings

- Dataset contains 25% churn rate (375 churned customers)
- Both models show strong precision for non-churned customers
- Challenge: Identifying churned customers (class imbalance)
- Feature importance visualization helps understand key drivers

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib
```

### Running the Analysis
1. Clone this repository
2. Open `Customer Retention and Churn Analysis Lab.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis

## 📊 Visualizations

The project includes:
- Feature importance chart showing top predictors of churn
- Model performance comparisons
- Distribution analysis of key variables

## 🎯 Model Performance

| Model | Accuracy | Precision (Churn) | Recall (Churn) |
|-------|----------|-------------------|----------------|
| Logistic Regression | 75% | 0.00 | 0.00 |
| Random Forest | 72% | 0.13 | 0.02 |

*Note: Class imbalance presents challenges for predicting churned customers*

## 💡 Future Improvements

- Address class imbalance using SMOTE or class weights
- Hyperparameter tuning for better performance
- Add more advanced models (XGBoost, Neural Networks)
- Feature engineering to create more predictive variables
- Cross-validation for more robust evaluation

## 📝 Author

Created as part of a Business Analytics learning project

## 📄 License

This project is open source and available for educational purposes.

---

**Note:** This analysis uses simulated data for demonstration purposes. The insights and patterns may differ with real-world customer data.
