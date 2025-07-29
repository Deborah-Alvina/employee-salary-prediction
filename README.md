# **Employee Salary Prediction**
A machine learning-based project that predicts employee salary categories (&lt;=50K or >50K) using an XGBoost classifier, leveraging demographic and work-related features.

## **Overview**
**Employee Salary Prediction** focuses on classifying employee salaries into two categories based on demographic and work-related attributes such as age, education, occupation, and hours worked per week. The project leverages data preprocessing, exploratory data analysis (EDA), and the XGBoost algorithm to identify the key factors influencing salary levels and provide accurate predictions. The model is trained and evaluated using well-established machine learning metrics including accuracy, precision, recall, F1-score, and Matthews correlation coefficient (MCC) to assess its effectiveness.

## **Features**
- **Data Preprocessing**: Cleans the dataset, handles missing values, and encodes categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualizes patterns and relationships between features and salary categories using plots and heatmaps.
- **Feature Impact**: Identifies influential attributes that contribute most to salary prediction.
- **XGBoost Classification**: Trains a high-performance gradient boosting model for binary classification of salaries.
- **Performance Evaluation**: Measures accuracy, precision, recall, F1-score, and MCC for robust evaluation.
- **Confusion Matrix Visualization**: Provides insights into classification results and error distribution.

## **Technologies Used**
- **Python**: Primary language for implementation.
- **Pandas**: Data cleaning, handling missing values, and manipulation.
- **Matplotlib & Seaborn**: Data visualization (countplots, boxplots, heatmaps) for EDA.
- **Scikit-learn**: Data preprocessing, train-test split, and evaluation metrics.
- **XGBoost**: Gradient boosting algorithm used to build the predictive salary model.
