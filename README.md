# 💰 Microfinance Loan Repayment Prediction

A machine learning classification project that predicts whether a customer will **repay a short-term microfinance loan within 5 days**.

The project uses customer recharge behavior, previous loan information, and account-related features to identify patterns associated with loan repayment.

## 📌 Project Overview

Microfinance institutions need to assess the likelihood that borrowers will repay their loans on time.

This project applies machine learning classification techniques to predict repayment behavior and compare different models.

### Objectives

- Clean and prepare the dataset
- Perform exploratory data analysis
- Analyze customer and loan-related patterns
- Perform feature engineering
- Preprocess numerical and categorical data
- Train multiple classification models
- Compare model performance
- Tune the best-performing model
- Evaluate predictions using multiple classification metrics

## 📊 Problem Statement

The goal is to predict whether a customer will repay a microfinance loan within **5 days** based on historical customer and account information.

This is a **binary classification problem**.

## 🔍 Exploratory Data Analysis

The dataset was analyzed to understand relationships between customer behavior and loan repayment.

The analysis included:

- Distribution of repayment outcomes
- Customer recharge behavior
- Previous loan information
- Numerical feature distributions
- Missing-value analysis
- Correlation analysis
- Comparison of features across repayment classes

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

- Data cleaning
- Handling missing values
- Feature selection
- Encoding categorical variables
- Preparing numerical features
- Splitting the data into training and testing sets

## ⚙️ Feature Engineering

Feature engineering was performed to extract useful information from customer and loan-related variables.

Features include information related to:

- Recharge activity
- Previous loan behavior
- Account history
- Customer transaction patterns

## 🤖 Machine Learning Models

The following classification models were implemented:

1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Gradient Boosting**
5. **XGBoost**

These models were compared to evaluate different approaches to the classification problem.

## 📈 Model Evaluation

The models were evaluated using:

### Accuracy

Measures the overall proportion of correctly classified observations.

### Precision

Measures how many predicted repayers were actually repayers.

### Recall

Measures how many actual repayers were correctly identified.

### Log Loss

Measures the quality of predicted probabilities. Lower values indicate better performance.

## 🏆 Model Selection

Among the tested models, **Random Forest performed best** based on the evaluation performed in this project.

The Random Forest model was therefore selected for further hyperparameter tuning.

## 🔧 Hyperparameter Tuning

Random Forest was further optimized using **RandomizedSearchCV**.

Multiple combinations of hyperparameters were evaluated using cross-validation to identify a better-performing configuration.

## 💻 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🔄 Project Workflow

Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Data Preprocessing
      ↓
Train/Test Split
      ↓
Model Training
      ↓
Model Comparison
      ↓
Hyperparameter Tuning
      ↓
Final Model Evaluation
## 📁 Project Structure
Microfinance-Loan-Repayment-Prediction/
│
├── Loan_Repayment_Prediction.ipynb
├── README.md
└── .gitignore
## 🚀 How to Run
1. Clone the repository
git clone https://github.com/sakshamsharma0407/Microfinance-Loan-Repayment-Prediction.git
2. Navigate to the project
cd Microfinance-Loan-Repayment-Prediction
3. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter
4. Launch Jupyter Notebook
jupyter notebook

Open the notebook and run the cells sequentially.

## 🎯 Future Improvements
Add a detailed model-performance comparison table
Add confusion matrix visualizations
Analyze false positives and false negatives
Add feature-importance analysis
Compare ROC-AUC and PR-AUC
Create a Streamlit prediction interface
Deploy the final model
Improve the project structure by separating preprocessing and training code
## 👨‍💻 Author

Saksham Sharma

B.Tech Computer Science Engineering Student

Interested in Machine Learning, Data Science, DSA, and Software Development.

## 📜 License

This project is intended for educational and portfolio purposes.
