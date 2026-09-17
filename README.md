# Customer Churn Prediction

## 📌 Project Overview

Customer churn is an important business problem because losing existing customers can affect revenue and long-term growth.

This project uses **Data Analysis and Machine Learning** to analyze customer behavior and predict whether a customer is likely to churn. The project includes data cleaning, exploratory data analysis, preprocessing, Logistic Regression modeling, model evaluation, and feature importance analysis.

## 🎯 Objectives

* Understand customer data and behavior
* Clean and preprocess the dataset
* Perform Exploratory Data Analysis (EDA)
* Identify patterns related to customer churn
* Build a Machine Learning classification model
* Evaluate model performance
* Analyze important features affecting churn prediction

## 📊 Dataset

The project uses customer-level telecommunications data containing information about customer demographics, services, contract details, charges, and churn status.

After data preparation, the analysis used **7,032 customer records and 20 features**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔄 Project Workflow

1. Importing Libraries
2. Loading the Dataset
3. Understanding the Dataset
4. Data Cleaning
5. Exploratory Data Analysis
6. Data Preprocessing
7. Feature Selection
8. Train-Test Split
9. Logistic Regression Model
10. Model Evaluation
11. Feature Importance
12. Business Insights
13. Final Conclusion

## 🧹 Data Cleaning & Preprocessing

The dataset was prepared before model development by checking and handling:

* Missing values
* Duplicate records
* Data types
* Unnecessary columns
* Categorical variables
* Numerical and categorical feature transformation

The prepared dataset was then divided into training and testing sets.

**Training Set:** 5,625 records
**Testing Set:** 1,407 records

## 📈 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand customer characteristics and identify patterns associated with churn.

The analysis explored customer-related variables such as:

* Tenure
* Monthly Charges
* Total Charges
* Contract type
* Customer services
* Churn status

Visualizations were created using **Matplotlib** and **Seaborn** to understand relationships between customer features and churn.

## 🤖 Machine Learning Model

A **Logistic Regression** classification model was implemented to predict customer churn.

The model was trained using the prepared customer features and evaluated on the test dataset.

### Model Performance

| Metric          |  Score |
| --------------- | -----: |
| Accuracy        | 79.39% |
| Churn Precision |    63% |
| Churn Recall    |    56% |
| Churn F1-Score  |    59% |

The evaluation metrics provide an understanding of how effectively the model identifies customers who are likely to churn.

## ⭐ Feature Importance

Feature importance analysis was performed to understand which customer characteristics contributed most to the churn prediction.

Important features identified in the analysis include:

* Tenure
* Monthly Charges
* Contract
* Total Charges

These features provide useful context for understanding customer churn patterns.

## 📸 Project Screenshots

### Exploratory Data Analysis

![EDA](eda.png)

### Churn Analysis

![Churn Analysis](churn_analysis.png)

### Model Evaluation

![Model Evaluation](model_evaluation.png)

### Feature Importance

![Feature Importance](feature_importance.png)

> Screenshot filenames should match the actual files uploaded to this repository.

## 💡 Business Insights

This project can help businesses:

* Identify customers who may be at risk of churn
* Understand customer behavior and churn patterns
* Identify important customer characteristics
* Develop targeted customer retention strategies
* Improve customer engagement
* Reduce potential customer loss

## 📌 Key Takeaways

* Customer behavior can be analyzed using Exploratory Data Analysis.
* Machine Learning can be used to predict potential customer churn.
* Logistic Regression achieved **79.39% accuracy** on the test dataset.
* Tenure, Monthly Charges, Contract, and Total Charges were among the important features identified in the analysis.

## 📝 Conclusion

This project demonstrates an end-to-end Data Science workflow for customer churn prediction, from data cleaning and exploratory analysis to Machine Learning model development and evaluation.

The project shows how customer data can be transformed into predictive insights that can support data-driven customer retention strategies.

## 👩‍💻 Author

**Shabeena Bano**

Aspiring Data Scientist | Python | SQL | Statistics | Machine Learning

GitHub: [shabeenabano](https://github.com/shabeenabano)
