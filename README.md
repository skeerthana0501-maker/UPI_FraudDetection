# Credit Card Fraud Detection Using Statistical Analysis

## Project Overview

This project focuses on identifying fraudulent credit card transactions using statistical analysis techniques. The objective is to analyze transaction behavior, detect suspicious patterns, identify fraud indicators, and generate business recommendations that can help financial institutions improve fraud monitoring systems.

The project was completed as part of an internship task involving data exploration, statistical analysis, visualization, hypothesis testing, and fraud signal identification.

---

## Dataset Information

The dataset contains **500,000 credit card transactions** with information related to transaction amount, transaction type, customer behavior, location, device usage, and fraud status.

### Dataset Features

* Transaction_ID
* Customer_ID
* Transaction_Date
* Amount
* Merchant_Category
* Merchant_ID
* Card_Type
* Transaction_Type
* Country
* Is_International
* Is_Chip
* Is_Pin_Used
* Distance_From_Home
* Hour_of_Day
* Device_Type
* Fraud_Flag

### Dataset Summary

| Metric                  |   Value |
| ----------------------- | ------: |
| Total Transactions      | 500,000 |
| Legitimate Transactions | 492,500 |
| Fraudulent Transactions |   7,500 |
| Fraud Percentage        |   1.50% |

---

## Project Phases

### Phase 1 – Data Exploration and Cleaning

* Dataset inspection
* Missing value analysis
* Duplicate record detection
* Fraud distribution analysis

### Phase 2 – Descriptive Statistical Analysis

* Mean
* Median
* Standard Deviation
* Quartile Analysis
* Distribution Analysis

### Phase 3 – Outlier Detection

* Interquartile Range (IQR) Method
* Detection of abnormal transaction values

### Phase 4 – Pattern Analysis

* Transaction Amount vs Fraud
* Time of Day vs Fraud
* Device Type vs Fraud
* Correlation Heatmap
* Data Visualization

### Phase 5 – Hypothesis Testing

* Independent Two-Sample T-Test
* Statistical significance analysis

### Phase 6 – Statistical Fraud Signals

* High Value Transactions
* Late Night Transactions
* Far From Home Transactions
* Web Transactions

### Phase 7 – Business Insights

* Fraud indicators
* Suspicious customer behavior
* Risk assessment
* Fraud prevention recommendations

---

## Key Findings

* Fraudulent transactions represented only **1.5%** of the dataset.
* High-value transactions were identified as major fraud indicators.
* Transactions occurring far from home showed elevated risk.
* Late-night transaction activity exhibited suspicious behavior patterns.
* Web-based transactions accounted for a significant portion of potential fraud activity.
* Transaction amount alone was not statistically significant in differentiating fraud from non-fraud transactions based on hypothesis testing.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook / VS Code

---

## Project Structure

```text
Fraud_Analysis/
│
├── Fraud_Analysis.ipynb
├── dataset.csv
├── Credit_Card_Fraud_Report.pdf
├── README.md
└── images/
```

---

## Results

The analysis successfully identified multiple fraud indicators using statistical techniques. The findings demonstrate that combining transaction amount, location behavior, transaction timing, and device usage provides stronger fraud detection capabilities than relying on a single variable.

---

## Author

Keerthana
B.Tech Information Technology

---

## Project Report

Refer to the attached PDF report for detailed analysis, visualizations, statistical results, and business recommendations.
