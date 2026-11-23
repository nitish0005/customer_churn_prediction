
# Customer Churn Prediction

## 1. Project Overview
This project focuses on predicting customer churn using machine learning.
It uses the IBM Telco Customer Churn dataset to identify customers who
are likely to discontinue their telecommunications services.

## 2. Objectives
- Explore and understand customer data.
- Clean and preprocess the dataset.
- Build an ETL pipeline using Python and PySpark.
- Apply machine learning classification algorithms.
- Evaluate and compare model performance.
- Identify customers who are likely to churn.

## 3. Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Apache PySpark
- Machine Learning

## 4. Dataset
IBM Telco Customer Churn dataset.

Original records: 7,043
Original columns: 21

## 5. Project Workflow
1. Data collection
2. Data exploration
3. Data cleaning
4. Data transformation
5. Feature engineering
6. Model training
7. Model evaluation
8. Model comparison

## 6. Machine Learning Models
- Logistic Regression
- Random Forest
- Balanced Logistic Regression

## 7. Model Results

| Model | Accuracy | Churn Recall |
|---|---:|---:|
| Logistic Regression | 80.52% | 54.32% |
| Random Forest | 78.14% | 54.32% |
| Balanced Logistic Regression | 74.94% | 81.34% |

The original Logistic Regression achieved the highest overall
accuracy, while Balanced Logistic Regression achieved the
highest churn recall.

## 8. Project Structure
- data/raw: Original dataset
- data/processed: Cleaned and transformed datasets
- outputs/models: Saved model parameters
- outputs: Model comparison results
- 01_data_exploration.ipynb: Exploratory data analysis
- 02_etl_pipeline.ipynb: ETL and machine learning pipeline

## 9. Conclusion
The project demonstrates how PySpark and machine learning
can be used to analyse customer data and predict churn.
The results show the trade-off between overall accuracy
and identifying customers likely to leave.
