# 📞 Telecom Churn Analysis & Prediction

This project presents a comprehensive approach to understanding and predicting customer churn in the telecom industry. It combines SQL-based ETL pipelines, Power BI dashboards for visual analytics, and Python-based machine learning models to identify at-risk customers and provide actionable business insights.

---

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [ETL Pipeline](#etl-pipeline)
- [Churn Analysis Dashboard](#churn-analysis-dashboard)
- [Churn Prediction Model](#churn-prediction-model)
- [Prediction Dashboard](#prediction-dashboard)
- [Key Insights](#key-insights)
- [Tech Stack](#tech-stack)
- [Installation & Usage](#installation--usage)
- [Screenshots](#screenshots)

---

## 📌 Project Overview

Customer churn is a critical metric for telecom companies. This project aims to:

- Analyze historical churn data to uncover trends and patterns
- Build a predictive model to identify customers likely to churn
- Visualize insights and predictions using Power BI dashboards
- Enable data-driven decision-making for customer retention strategies

---

## 🔄 ETL Pipeline

**Tools Used**: SQL Server Management Studio (SSMS)

**Steps**:
1. Import raw CSV data into SQL Server
2. Clean and transform data into structured tables
3. Create views for Power BI consumption
4. Ensure data integrity and normalization

---

## 📈 Churn Analysis Dashboard

Built in Power BI, this dashboard provides:

- Churn rate by contract type, payment method, tenure, and internet service
- Heatmap of churn across different states
- Breakdown of churn categories (e.g., Competitor, Price, Dissatisfaction)
- KPIs: Total Customers, New Joiners, Churn Rate

---

## 🤖 Churn Prediction Model

**Language**: Python  
**Algorithm**: Random Forest Classifier

**Steps**:
- Data preprocessing: Label encoding, missing value handling
- Feature selection: Tenure, services, contract type, payment method
- Model training and evaluation: Accuracy, precision, recall, F1-score
- Output: Churn probability and customer risk classification

---

## 📊 Prediction Dashboard

Power BI dashboard visualizing model predictions:

- Total predicted churners
- Churn distribution by gender, age group, marital status, tenure
- Customer-level risk matrix with revenue, referrals, and refund data

---

## 💡 Key Insights

- Long-term contracts and credit card payments reduce churn
- Fiber optic users show higher churn rates
- Bundled services (security, streaming) improve retention
- Competitor-driven churn dominates—pricing and loyalty programs needed

---

## 🧰 Tech Stack

- **Languages**: Python, SQL
- **Libraries**: Pandas, Scikit-learn
- **Tools**: Power BI, SQL Server
- **Model**: Random Forest

---

## Screenshots

![Screenshot]([https://via.placeholder.com/468x300?text=App+Screenshot+Here](https://github.com/Lavnish-s-s/telecom-customer-churn-analysis-and-prediction/blob/main/Images/PredicitonDashboard.png))
![Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

---

## 🛠️ Installation & Usage

### Clone the Repository

```bash
git clone https:///github.com/Lavnish-s-s/telecom-customer-churn-analysis-and-prediction.git
cd telecom-customer-churn-analysis-and-prediction
