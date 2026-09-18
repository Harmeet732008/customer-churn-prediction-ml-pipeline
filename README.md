# Customer Churn Prediction ML Pipeline

An end-to-end Machine Learning project for predicting **customer churn** using a structured data preprocessing and classification pipeline.

The project demonstrates how raw, inconsistent customer data can be cleaned, transformed, analyzed, and used to build a machine learning model for a practical business problem.

## 📌 Project Overview

Customer churn occurs when customers stop using a company's products or services.

For an online retail business such as **SmartKart**, identifying customers who are likely to churn can help management understand customer behavior and support data-driven retention strategies.

This project builds a complete ML workflow from **raw customer data to churn prediction and model evaluation**.

## 🎯 Business Objective

The primary objective is to:

* Clean and prepare customer data
* Identify important customer attributes
* Handle missing and invalid values
* Prepare features for machine learning
* Build a customer churn classification model
* Evaluate model performance using appropriate metrics
* Demonstrate how machine learning can support customer-retention analysis

## 🧠 Machine Learning Approach

The project uses **Logistic Regression** as the classification algorithm.

### Pipeline

```text
Raw Customer Data
       ↓
Data Collection
       ↓
Data Inspection
       ↓
Data Cleaning
       ↓
Data Preprocessing
       ↓
Feature Selection
       ↓
Train/Test Split
       ↓
Logistic Regression
       ↓
Churn Prediction
       ↓
Model Evaluation
```

## 📊 Dataset

The project uses a deliberately messy SmartKart customer dataset containing **100 customer records**.

The dataset includes:

| Feature         | Description                               |
| --------------- | ----------------------------------------- |
| `Customer_ID`   | Unique customer identifier                |
| `Age`           | Customer age                              |
| `Monthly_Spend` | Customer's monthly spending               |
| `Complaints`    | Number of customer complaints             |
| `Churn`         | Target variable indicating customer churn |

The dataset contains realistic data-quality issues such as:

* Missing values
* Duplicate records
* Unnecessary whitespace
* Incorrect data types
* Invalid values
* Outliers

## 🧹 Data Cleaning

The preprocessing stage addresses the identified data-quality problems.

Key steps include:

* Removing duplicate records
* Removing unnecessary whitespace
* Converting columns into appropriate data types
* Handling invalid age values
* Handling negative spending values
* Handling missing values using median-based imputation
* Preparing the dataset for machine learning

## 🤖 Model

### Logistic Regression

Logistic Regression is used to predict whether a customer belongs to the churn or non-churn class.

The model is suitable for this project because the target variable represents a binary classification problem.

## 📈 Model Evaluation

The model is evaluated using classification performance metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

These metrics provide different perspectives on how effectively the model identifies customer churn.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Repository Structure

```text
customer-churn-prediction-ml-pipeline/
│
├── SmartKart_Churn_Prediction_ML_Pipeline.ipynb
├── SmartKart_dirty_100_rows.csv
├── README.md
└── requirements.txt
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction-ml-pipeline.git
```

### 2. Navigate to the project

```bash
cd customer-churn-prediction-ml-pipeline
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
SmartKart_Churn_Prediction_ML_Pipeline.ipynb
```

## 💼 Business Relevance

Customer churn prediction is a common application of machine learning in industries such as:

* E-commerce
* Retail
* Banking
* FinTech
* Telecom
* Subscription businesses
* Customer-service platforms

A churn prediction system can provide businesses with an analytical signal for identifying customers who may require further investigation or retention efforts.

## ⚠️ Limitations

This project is primarily a learning and demonstration project.

The dataset contains only 100 records and is intentionally created with data-quality issues. Therefore, model performance should **not** be interpreted as production-level performance.

A real-world implementation would require:

* A larger customer dataset
* More behavioral features
* Proper feature engineering
* Cross-validation
* Hyperparameter tuning
* Model monitoring
* Regular retraining
* Business validation

## 🔍 Key Learning Outcomes

Through this project, the following concepts are demonstrated:

* Data understanding
* Data cleaning
* Missing-value handling
* Outlier handling
* Feature preparation
* Classification
* Logistic Regression
* Model evaluation
* Business-oriented machine learning
* End-to-end ML pipeline development

## 👨‍💻 Project

**SmartKart — Customer Churn Prediction**

Built as an applied Machine Learning project demonstrating the use of Python and ML techniques to address a practical customer-retention problem.
