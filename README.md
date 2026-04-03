# week-8-retail-sales-capstone
# 📊 Customer Churn Analysis Project

## 📌 Overview

This project analyzes customer churn behavior using a telecom dataset.
The goal is to understand customer patterns and predict churn using data analysis and machine learning.

---

## 📁 Dataset

The dataset includes the following features:

* CustomerID
* Tenure
* MonthlyCharges
* TotalCharges
* Contract
* PaymentMethod
* PaperlessBilling
* SeniorCitizen
* Churn

---

## 🧹 Data Cleaning

* Removed extra spaces from column names
* Converted `TotalCharges` to numeric format
* Handled missing values

---

## 📊 Data Visualization

The following visualizations were created:

* Correlation Heatmap
* Churn Count Plot
* Tenure vs Total Charges Scatter Plot
* Monthly Charges Distribution
* Contract vs Churn
* Payment Method vs Churn

---

## 🤖 Machine Learning Models

### 🔹 Linear Regression

Used to predict:

* **Total Charges** based on Tenure and Monthly Charges

### 🔹 Logistic Regression (Optional)

Used to predict:

* **Churn (Yes/No)**

---

## 📈 Results

* Strong relationship found between tenure, monthly charges, and total charges
* Customers with higher monthly charges are more likely to churn
* Contract type significantly affects churn behavior

---

## 🔍 Insights

* Long-term customers generate more revenue
* High-paying customers are at higher risk of churn
* Month-to-month contracts have higher churn rates
* Electronic payment methods show higher churn

---

## 📂 Project Structure

```
statistical_analysis.ipynb
business_data.csv
predictions.csv
insights.txt
customer_churn_report.pdf
requirements.txt
README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```
git clone <your-repo-link>
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook:

```
jupyter notebook
```

---

## 🏁 Conclusion

This project helps in understanding customer behavior and provides insights to reduce churn and improve customer retention.

