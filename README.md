# E-Commerce Product Delivery Prediction

## 📌 Project Overview

This project focuses on predicting whether an e-commerce product will be delivered on time or not using Machine Learning.

The project is based on an international e-commerce company specializing in electronic products. The objective is to analyze customer, product, warehouse, and shipment-related factors that may influence delivery performance and build classification models to predict delivery timeliness.

The project follows an end-to-end Data Science workflow, including data exploration, preprocessing, visualization, model development, and performance evaluation.

## 🎯 Objectives

* Predict whether an order will reach the customer on time.
* Identify factors that influence delivery performance.
* Perform Exploratory Data Analysis (EDA) to understand the dataset.
* Preprocess categorical and numerical features for Machine Learning.
* Build and compare multiple classification models.
* Evaluate model performance using appropriate metrics.
* Generate business insights that can help improve logistics and customer satisfaction.

## 📊 Dataset

The dataset contains **10,999 records and 12 columns** related to e-commerce orders.

### Features

| Feature             | Description                     |
| ------------------- | ------------------------------- |
| ID                  | Unique order identifier         |
| Warehouse_block     | Warehouse location/block        |
| Mode_of_Shipment    | Mode used for shipment          |
| Customer_care_calls | Number of customer care calls   |
| Customer_rating     | Customer rating                 |
| Cost_of_the_Product | Cost of the product             |
| Prior_purchases     | Number of previous purchases    |
| Product_importance  | Importance level of the product |
| Gender              | Customer gender                 |
| Discount_offered    | Discount offered                |
| Weight_in_gms       | Product weight in grams         |
| Reached.on.Time_Y.N | Target variable                 |

### Target Variable

`Reached.on.Time_Y.N`

* **1** → Product reached on time
* **0** → Product did not reach on time

## 🔍 Exploratory Data Analysis

EDA was performed to understand the distribution of the data and identify patterns related to delivery performance.

The analysis includes:

* Dataset structure and data types
* Missing-value analysis
* Duplicate-value check
* Descriptive statistics
* Target-variable distribution
* Categorical-feature analysis
* Numerical-feature distributions
* Shipment-mode analysis
* Customer-rating analysis
* Product-importance analysis
* Discount analysis
* Weight analysis
* Correlation analysis
* Relationship between important features and delivery outcome

Visualizations were created using **Matplotlib** and **Seaborn**.

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Loaded the dataset using Pandas.
* Checked the dataset structure and data types.
* Checked for missing values and duplicate records.
* Separated input features and target variable.
* Encoded categorical variables.
* Prepared numerical features for modelling.
* Split the dataset into training and testing sets.
* Applied feature scaling where required.

## 🤖 Machine Learning Models

Since the target variable has two possible outcomes, this project is treated as a **binary classification problem**.

The following Machine Learning algorithms were considered/evaluated:

* **Logistic Regression**
* **Decision Tree Classifier**
* **Random Forest Classifier**
* **K-Nearest Neighbors (KNN)**

The models were compared based on their performance on the test dataset.

## 📈 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Classification Report

A comparison of model performance was used to identify the most suitable model for predicting delivery timeliness.

## 💡 Business Benefits

### Delivery Optimization

The model can help identify factors associated with delivery delays and support better logistics planning.

### Customer Satisfaction

Predicting delivery timeliness can help businesses set realistic delivery expectations and improve customer experience.

### Operational Insights

Understanding customer, product, warehouse, and shipment patterns can support better resource allocation and operational decision-making.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Machine Learning

## 📁 Project Structure

```text
Ecommerce-product-Delivery-Prediction/
│
├── Ecommerce_Delivery_Prediction.ipynb
├── README.md
└── E_Commerce.xlsx
```

> **Note:** The dataset file should only be uploaded if you have permission from the institute to redistribute it. Otherwise, use the dataset link provided by the institute.

## 🚀 Project Workflow

```text
Data Collection
      ↓
Data Exploration
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Encoding & Scaling
      ↓
Train-Test Split
      ↓
Machine Learning Model Development
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Business Insights
```

## 📌 Conclusion

This project demonstrates how Machine Learning can be applied to an e-commerce delivery problem to predict whether orders are likely to reach customers on time.

By combining data preprocessing, exploratory analysis, visualization, and classification algorithms, the project provides insights into delivery performance and demonstrates a practical application of Data Science in e-commerce logistics.

## 👩‍💻 Author

**Pavitra Rane**

AI & Data Science Learner

**Skills demonstrated:**
Python | Pandas | NumPy | EDA | Data Preprocessing | Data Visualization | Machine Learning | Scikit-learn | Jupyter Notebook
