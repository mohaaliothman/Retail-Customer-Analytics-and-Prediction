# Retail Customer Intelligence & Cancellation Risk Analytics

## 🌐 Interactive Dashboard
👉 [View Power BI Dashboard](https://drive.google.com/drive/folders/16qwJRlQRE4lx2JG_ZxTfp0RyPTNqa4h9?usp=sharing)

---

# 📌 Project Overview

This project analyzes e-commerce retail transaction data to uncover customer behavior patterns, sales trends, cancellation risks, and business opportunities using Business Intelligence and Machine Learning techniques.

The project combines:
- Data Cleaning & Transformation (Excel)
- Interactive Business Intelligence Dashboards (Power BI)
- Predictive Analytics & Customer Segmentation (Python)

The goal is to transform raw retail data into actionable business insights that support data-driven decision-making.

---

# 🎯 Project Objectives

- Analyze historical sales performance
- Explore customer purchasing behavior
- Identify high-value customer segments
- Detect cancellation trends and business risks
- Build predictive analytics models for cancellation risk
- Support business decision-making through interactive dashboards

---

# 🧱 Project Structure

```bash
Retail-Customer-Analytics-and-Prediction/
│
├── Dashboard/
│   └── retail_dashboard.pbix
│
├── Data/
│   ├── raw_data.xlsx
│   ├── clean_orders.csv
│   ├── cancelled_orders.csv
│   ├── customer_segments.csv
│   └── cancellation_predictions_real.csv
│
├── Models/
│   ├── customer_segmentation.ipynb
│   ├── cancellation_prediction.ipynb
│   └── feature_importance.csv
│
├── Images/
│   ├── overview.png
│   ├── customer_analysis.png
│   ├── time_analysis.png
│   ├── cancellation_analysis.png
│   ├── segmentation.png
│   └── predictive_analytics.png
│
├── Executive_Summary.pdf
├── README.md
```
---

👉 [For data not found, click here](https://drive.google.com/drive/folders/16qwJRlQRE4lx2JG_ZxTfp0RyPTNqa4h9?usp=sharing)

# 📊 Dashboard Pages

## 1. Executive Overview
- Total Revenue, Orders, and Customers
- Revenue trends over time
- Top-performing countries and products
- Key business KPIs

## 2. Customer Analysis
- Top customers by revenue
- Customer purchasing behavior
- Customer segmentation analysis
- Revenue contribution by segment

## 3. Time & Sales Analysis
- Monthly and daily sales trends
- Peak purchasing hours
- Weekday vs weekend performance
- Seasonal purchasing behavior

## 4. Cancellation Analysis
- Cancellation trends over time
- Countries with highest cancellations
- Products contributing to cancelled revenue
- Cancellation risk distribution

## 5. Predictive Analytics
- Cancellation risk prediction
- Feature importance analysis
- Risk-level classification
- Machine learning insights

---

# 🤖 Machine Learning Models

## 1. Customer Segmentation

Using:
- RFM Analysis
- K-Means Clustering

Customer groups:
- VIP Customers
- Loyal Customers
- Regular Customers
- At-Risk Customers
- Low-Value Customers

### Segmentation Performance
- Silhouette Score: ~0.59

---

## 2. Cancellation Risk Prediction

Using:
- Random Forest Classification

### Model Performance
- Accuracy: ~71%
- Balanced dataset using downsampling techniques
- Feature engineering applied before training

### Most Important Features
- Month
- Purchase Hour
- Total Price
- Order Quantity

---

# 📈 Key Business Insights

- Revenue exceeded **17M**
- The UK generated the majority of revenue and cancellations
- Sales activity peaks around **12 PM**
- Weekday sales outperform weekend sales
- Cancellation activity increases significantly during December
- A small group of VIP customers contributes a large share of revenue
- Temporal and transactional patterns strongly influence cancellations

---

# 🛠 Tools & Technologies

- Power BI
- Microsoft Excel
- Python
- Pandas
- Scikit-learn
- DAX

---

# 📷 Dashboard Preview

## Executive Overview
![Overview](Images/overview.png)

## Customer Analysis
![Customer Analysis](Images/customer_analysis.png)

## Time Analysis
![Time Analysis](Images/time_analysis.png)

## Cancellation Analysis
![Cancellation Analysis](Images/cancellation_analysis.png)

## Predictive Analytics
![Predictive Analytics](Images/predictive_analytics.png)

---

# ⚠️ Limitations

- Dataset is limited to historical retail transactions
- External economic and operational factors were not included
- Predictive models cannot guarantee future outcomes
- Customer behavior may evolve over time

---

# 🚀 Future Improvements

- Integrate forecasting models
- Deploy real-time analytics pipelines
- Improve recommendation systems
- Build advanced customer lifetime value models
- Integrate machine learning directly into Power BI

---

# 👤 Author

**Mohammad Ali Othman**  
Data Science Student | BI & Data Analytics Enthusiast
