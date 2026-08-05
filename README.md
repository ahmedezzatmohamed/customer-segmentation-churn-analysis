# 📊 Customer Segmentation & Customer Churn Analysis

An end-to-end data analytics project that explores customer purchasing behavior using **RFM Analysis**, **Customer Segmentation**, and **Churn Prediction**. The project combines data cleaning, exploratory analysis, machine learning, and an interactive dashboard to help businesses identify high-value customers, understand customer behavior, and reduce churn.

---

## 🚀 Project Objectives

* Analyze customer purchasing patterns.
* Identify high-value customer segments using RFM analysis.
* Group customers with K-Means clustering.
* Predict customers who are likely to churn.
* Build an interactive dashboard for business stakeholders.

---

## 📁 Project Structure

```
Customer-Segmentation-Churn-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_rfm_analysis.ipynb
│   ├── 04_customer_segmentation.ipynb
│   └── 05_churn_prediction.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── dashboard/
│   └── app.py
│
├── requirements.txt
└── README.md
```

---

## 📈 Features

* Customer data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* RFM (Recency, Frequency, Monetary) Analysis
* Customer Segmentation using K-Means Clustering
* Customer Churn Prediction using Machine Learning
* Interactive dashboard built with Streamlit and Plotly
* Business recommendations based on analytical insights

---

## 🛠️ Tech Stack

**Programming**

* Python

**Libraries**

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Plotly
* Streamlit

**Machine Learning**

* K-Means Clustering
* Logistic Regression

---

## 📊 Dataset

This project uses a public e-commerce transaction dataset containing customer purchase history, including:

* Invoice Number
* Customer ID
* Purchase Date
* Quantity
* Unit Price
* Country

---

## 📌 Dashboard Overview

The dashboard provides:

* Executive KPI Summary
* Customer Segmentation Analysis
* RFM Score Distribution
* Customer Cluster Comparison
* Churn Risk Analysis
* Individual Customer Churn Prediction

---

## ▶️ Running the Project

```bash
git clone https://github.com/ahmedezzatmohamed/customer-segmentation-churn-analysis.git

cd customer-segmentation-churn-analysis

pip install -r requirements.txt

streamlit run dashboard/app.py
```

---

## 👨‍💻 Author

**Ahmed Mohamed**

Computer Science & Business Student at Minerva University

* Python
* SQL
* Data Analytics
* Power BI
* Machine Learning

LinkedIn:
https://linkedin.com/in/ahmedkhozeim

---

## 📄 License

This project is licensed under the MIT License.
