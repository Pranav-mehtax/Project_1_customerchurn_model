# Project_1_customerchurn_model
Customer Churn Prediction using Machine Learning (Logistic Regression, Decision Tree, Random Forest) with EDA, model evaluation, and business insights
# Customer Churn Prediction System

#  Overview
Customer churn is a major concern for businesses, as acquiring new customers is often more expensive than retaining existing ones.  
This project aims to predict whether a customer is likely to churn using machine learning techniques and derive actionable insights to improve customer retention.

---

# Objectives
- Predict customer churn using machine learning models
- Identify key factors influencing churn
- Compare multiple models for performance
- Provide business-driven insights and recommendations

---

# Dataset
The dataset contains customer information such as:
- Demographics (e.g., tenure)
- Account details (e.g., charges)
- Services subscribed

**Target Variable:**
- `Churn` (Yes / No)

---

## Project Workflow

###  1. Data Preprocessing
- Converted data types (e.g., `TotalCharges` to numeric)
- Handled missing values using imputation
- Encoded categorical variables using one-hot encoding
- Applied feature scaling using StandardScaler

---

###  2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution (class imbalance)
- Visualized relationships between features and churn
- Used boxplots and heatmaps for insights

---

### 3. Outlier Detection
- Used IQR (Interquartile Range) method to detect outliers
- Carefully evaluated whether removal was appropriate for each feature

---

### 4. Model Building
Implemented and compared multiple models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

### 5. Model Evaluation
Models were evaluated using:
- Confusion Matrix
- Precision, Recall, F1-score
- Cross-validation

---

## 📈 Results
- Logistic regression achieved the best performance among all models
- F1-score was used as the primary metric due to class imbalance

---

## Key Insights
- Customers with **low tenure** are more likely to churn  
- Higher **monthly charges** increase churn probability  
- Certain services and contract types strongly influence churn  

---

## Business Recommendations
- Provide incentives to new customers to improve retention  
- Offer flexible pricing for high-charge customers  
- Target high-risk customers using predictive models  

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## How to Run the Project

```bash
# Clone the repository
git clone https://github.com/Pranav-mehtax/Project_1_customerchurn_model
.git

# Navigate to project folder
cd customer-churn-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
