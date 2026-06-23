# Customer Churn Prediction

Machine learning project focused on predicting telecom customer churn and identifying high-risk customers for retention campaigns.

## Business Problem

Customer churn directly impacts recurring revenue and customer acquisition costs. The goal of this project is to identify customers likely to leave so retention efforts can be targeted more effectively.

## Key Results

- Best Model: Ensemble Classifier
- ROC-AUC: **0.701**
- Multiple models evaluated, including Logistic Regression, Random Forest, XGBoost, LightGBM, and CatBoost
- Customer risk segmentation developed for retention targeting
- SHAP analysis used to interpret model predictions

## Project Workflow

### 1. Data Understanding
- Dataset loading and merging
- Missing value assessment
- Duplicate analysis
- Target distribution analysis

### 2. Exploratory Data Analysis
- Revenue patterns
- Customer usage behavior
- Service quality metrics
- Correlation analysis

### 3. Feature Engineering
- Revenue-per-minute metrics
- Overage features
- Equipment age indicators

### 4. Data Preprocessing
- Missing value imputation
- Categorical encoding
- Feature scaling
- Train-test split

### 5. Model Development
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Ensemble Model

### 6. Model Evaluation
- ROC-AUC comparison
- Confusion Matrix
- ROC Curve Analysis
- Feature Importance

### 7. Model Interpretation
- Feature Importance Analysis
- SHAP Explainability

### 8. Customer Segmentation
- Risk-based customer groups
- Retention targeting framework

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- SHAP
- Matplotlib
- Seaborn

## Business Impact

The final solution demonstrates how machine learning can support proactive customer retention strategies by identifying customers at elevated churn risk and providing interpretable insights into the factors driving churn.
