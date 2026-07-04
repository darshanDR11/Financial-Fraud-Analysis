# Financial Fraud Detection Dashboard

An end-to-end **Business Intelligence** project built in **Power BI** to analyze financial transaction data and identify fraud patterns. The dashboard is designed to help fraud analysts, risk teams, and business stakeholders monitor fraudulent activities, identify high-risk payment channels, and support data-driven decision making.

---

## Project Overview

Financial fraud is one of the biggest challenges faced by banks and financial institutions. This project analyzes banking transaction data to uncover fraud trends, identify suspicious transaction patterns, and evaluate risk across different countries, payment methods, merchant categories, and devices.

The project focuses on transforming raw transaction data into interactive dashboards that provide actionable business insights.

---

## Business Objectives

- Monitor overall fraud performance.
- Identify fraud trends over time.
- Analyze high-risk countries and payment methods.
- Detect fraud patterns across merchant categories.
- Investigate transaction behavior associated with fraud.
- Support business decisions through interactive dashboards.

---

## Dashboard Overview

### 1. Executive Fraud Overview

This dashboard provides a high-level summary of fraud performance for executives and decision makers.

#### KPIs

- Total Transactions
- Fraud Rate
- Success Rate
- Customers Affected
- Most Common Fraud Type
- Highest-Risk Payment Method

#### Visuals

- Fraud Trend by Month
- Top 5 Countries by Fraud Count
- Top Fraud Types
- Fraud Activity Heatmap (Hour × Weekday)
- Fraud Transactions by Payment Method (%)

#### Business Questions Answered

- Is fraud increasing over time?
- Which countries experience the highest fraud?
- Which fraud types are most common?
- Which payment methods contribute the most fraud?
- During which hours does fraud occur most frequently?

---

### 2. Fraud Investigation Dashboard

This dashboard helps fraud analysts investigate characteristics associated with fraudulent transactions.

#### KPIs

- Total Fraudulent Transactions
- Fraud Rate
- Highest-Risk Device
- Highest-Risk Country
- Highest Fraud Type
- Highest-Risk Payment Method

#### Visuals

- Fraud Rate by Merchant Category (%)
- Monthly Fraud Trend
- Fraud Transactions by Fraud Type
- Fraud Transactions by Device Type (%)
- Top 5 Countries by Fraud Count

#### Business Questions Answered

- Which merchant categories have the highest fraud rate?
- Which devices are associated with the highest fraud?
- Which countries require additional fraud monitoring?
- Which fraud types occur most frequently?
- How has fraud changed over time?

---

### 3. Risk Analysis Dashboard

This dashboard focuses on identifying high-risk channels and transaction patterns to support fraud prevention strategies.

#### KPIs

- Highest-Risk Merchant Category
- Highest-Risk Payment Method
- Highest-Risk Device
- Highest-Risk Country

#### Visuals

- Merchant Category Fraud Rate
- Payment Method Fraud Rate
- Device Type Fraud Rate
- Country-wise Fraud Rate
- Transaction Status Analysis

#### Business Questions Answered

- Which merchant categories are most vulnerable?
- Which payment methods require stronger security?
- Which countries show the highest fraud rate?
- Which transaction channels are high risk?

---

## Power BI Features

- Interactive Navigation
- Dynamic KPI Cards
- Drill-Down Capability
- Cross Filtering
- Custom Navigation Buttons
- Dynamic Slicers
- Responsive Dashboard Layout
- Professional Dashboard Design
- Business-Oriented Visualizations

---

## Data Cleaning

The dataset was prepared using Power Query before building the dashboards.

Cleaning steps included:

- Removed duplicate records
- Verified data types
- Renamed columns
- Removed unnecessary fields
- Validated missing values
- Created calculated columns where required

---

## DAX Measures

Some of the key DAX measures used in the project include:

- Total Transactions
- Fraud Transactions
- Fraud Rate
- Success Rate
- Customers Affected
- Highest Fraud Type
- Highest-Risk Payment Method

---

## Key Business Insights

- Credit Cards contribute the largest share of fraudulent transactions.
- Phishing is the most common fraud type.
- Mobile devices account for the highest percentage of fraud transactions.
- Fraud activity is concentrated during specific hours of the day.
- Certain merchant categories experience significantly higher fraud rates.
- Fraud distribution varies considerably across countries.
- Fraud trends fluctuate over time, indicating seasonal or behavioral patterns.
- Merchant category and payment method play a significant role in fraud occurrence.

---

## Dashboard Preview

### Executive Fraud Overview

<img width="1358" height="840" alt="Screenshot 2026-07-04 074011" src="https://github.com/user-attachments/assets/0ecb0098-b372-4dd7-9fa4-f7db5abaac30" />

---

### Fraud Investigation Dashboard

<img width="1327" height="833" alt="Screenshot 2026-07-04 073957" src="https://github.com/user-attachments/assets/f0441e1a-ced4-4814-ae97-bc86f98a7656" />

---

## Project Structure

```
Financial-Fraud-Dashboard
│
├── Dataset
│   └── financial_fraud_dataset.csv
│
├── Power BI
│   └── Financial_Fraud_Dashboard.pbix
│
├── Dashboard Images
│   ├── Executive_Overview.png
│   ├── Fraud_Investigation.png
│   └── Risk_Analysis.png
│
├── README.md
└── LICENSE
```

---

## Tools Used

- Microsoft Power BI
- Power Query
- DAX

---

## Dataset

**Domain:** Banking & Financial Services

**Type:** Financial Transaction Fraud Detection

The dataset contains banking transaction records with fraud indicators, customer information, payment methods, merchant categories, device types, transaction details, and geographical information.

---

## Skills Demonstrated

- Business Intelligence
- Data Visualization
- Dashboard Design
- Power BI
- Power Query
- DAX
- KPI Development
- Business Analytics
- Financial Fraud Analysis
- Data Storytelling

---

## Future Enhancements

- Real-time fraud monitoring
- Fraud prediction using Machine Learning
- Customer risk scoring
- Automated fraud alert dashboard
- Real-time streaming dashboard

---

## Author

**Darshan Dudhat**

If you found this project useful, consider giving it a star.
