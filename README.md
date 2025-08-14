# Customer Churn Prediction

This project predicts customer churn using machine learning techniques in Python.  
It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and model training with evaluation metrics.

## 📂 Dataset
The dataset used (`churn.csv`) contains customer demographic and account information, along with a churn indicator (`Exited`).

## 📊 Project Workflow
1. **Understanding the dataset**  
   - Loading the dataset with Pandas  
   - Checking data types, missing values, and structure  

2. **Data preprocessing**  
   - Dropping irrelevant columns (`RowNumber`, `CustomerId`, `Surname`)  
   - Encoding categorical variables (`Geography`, `Gender`) using LabelEncoder  
   - Scaling numerical features  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of features  
   - Correlation heatmap  
   - Churn rate visualization by demographics  

4. **Model training**  
   - Decision Tree Classifier with hyperparameter tuning  
   - Evaluation using accuracy, confusion matrix, and classification report  

## 🛠️ Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/churn-prediction.git
