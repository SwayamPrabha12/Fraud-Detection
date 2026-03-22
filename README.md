# 🛡️ Fraud Intelligence: Transaction Risk & Behavioral Analytics Dashboard

---

## 1. Fraud Detection

**🛡️ Fraud Intelligence Dashboard: Monitoring Transaction Risk, Fraud Trends & Behavioral Patterns**
An interactive Power BI dashboard designed to analyze digital transactions, detect fraud patterns, and provide actionable insights for financial risk management.

---

## 2. Description / Purpose

The Fraud Intelligence Dashboard is a data-driven Power BI solution that enables financial institutions to monitor, analyze, and interpret digital transaction data. It helps identify fraud trends, high-risk behaviors, and suspicious activities through intuitive visualizations and real-time insights.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

*  **Power BI Desktop** – Main platform for building interactive dashboards
*  **Power Query** – Data cleaning, transformation, and preprocessing
*  **DAX (Data Analysis Expressions)** – Used for KPIs, calculated fields, and logic
*  **Data Modeling** – Relationships created for efficient filtering and aggregation
*  **Microsoft Excel** – Primary data source for transaction dataset
*  **File Formats** – `.pbix` (development), `.png` (dashboard preview)

---

## 4. Data Source

**Source:** Kaggle – Credit Card Fraud Detection Dataset

The dataset contains detailed digital transaction records including:

* Transaction amount
* Time of transaction
* Location data
* Transaction type (UPI, card, wallet, etc.)
* Fraud flag indicators

Additional references include reports from RBI, World Bank, and Statista for contextual understanding of fraud trends.

---

## 5. Features / Highlights

### 🔴 Business Problem

With the rapid rise of digital payments (UPI, wallets, online banking), fraud cases have increased significantly. However, organizations face challenges such as:

* Lack of real-time fraud monitoring
* Poor visibility into fraud trends
* Difficulty identifying high-risk transactions
* Complex systems with low interpretability

This leads to financial loss, operational risk, and reduced customer trust.

---

### 🎯 Goal of the Dashboard

To develop an interactive and visual analytics tool that:

* Tracks transaction and fraud activity in real time
* Identifies high-risk transactions using risk scoring
* Analyzes fraud trends across time, location, and transaction types
* Enables decision-makers to take data-driven actions
* Simplifies complex fraud detection into visual insights

---

### 📊 Walkthrough of Key Visuals

#### 🔹 KPI Cards (Top Section)

* Total Transactions: **50K**
* Total Amount: **1.25bn**
* Fraud Transactions: **7K**
* Fraud Amount: **169.8M**
* Fraud Rate: **13.57%**
* High Risk Transactions: **15K**

---

#### 🔹 Fraud by Transaction Type (Bar Chart)

* Compares fraud occurrences across:

  * Net Banking
  * Credit Card
  * Wallet
  * Debit Card
  * UPI
* Helps identify which payment mode is most vulnerable

---

#### 🔹 Fraud by Location (Donut Chart)

* City-wise fraud distribution (Kolkata, Pune, Mumbai, etc.)
* Enables geographic risk analysis

---

#### 🔹 Transactions by Time Category (Stacked Bar)

* Time segments:

  * Morning
  * Afternoon
  * Evening
  * Night
* Highlights behavioral fraud patterns across time

---

#### 🔹 Fraud by Merchant Category (Horizontal Bar)

* Categories include:

  * Retail
  * Entertainment
  * Healthcare
  * Travel
  * Food
  * Electronics
* Identifies high-risk business sectors

---

#### 🔹 Fraud Trend by Quarter (Line Chart)

* Tracks fraud changes across Q1–Q4
* Helps in seasonal trend analysis

---

#### 🔹 Night Fraud Analysis (Line Chart)

* Focused view of fraud occurring at night
* Detects unusual or suspicious timing patterns

---

### 💡 Algorithm & Logic Used

* Transactions with **risk score > 0.7 → High Risk**
* Sudden spikes in amount → **Anomaly detection**
* Late-night transactions → **Behavioral risk analysis**
* Location inconsistencies → **Fraud indicators**

👉 Focus is on **interpretable analytics**, not black-box models.

---

### 🚀 Business Impact & Insights

* 📉 **Fraud Reduction:** Early detection of high-risk transactions
* 📊 **Better Decision Making:** Clear visual insights for analysts
* 🌍 **Geographic Risk Analysis:** Identify fraud-prone regions
* ⏱️ **Behavioral Insights:** Detect unusual time-based activities
* 🏦 **Operational Efficiency:** Faster response to fraud incidents

---

## 6. Screenshots / Demo

### 📊 Dashboard Preview

![Image](https://github.com/SwayamPrabha12/Fraud-Detection/blob/main/SnapShot_FraudDetection.png)


---

## 7. Conclusion

The Fraud Intelligence Dashboard provides a powerful and intuitive solution for monitoring digital payment fraud. By transforming complex transaction data into meaningful visual insights, it enhances fraud detection capabilities and supports informed decision-making.

This project demonstrates how data visualization bridges the gap between raw data and actionable intelligence, improving financial security and trust in digital ecosystems.

---

## 8. Future Scope

*  Real-time data streaming integration
*  Machine Learning-based fraud prediction
*  Automated alert systems for high-risk transactions
*  Geo-spatial fraud mapping
*  User-level behavioral profiling

---

## 9. References

* Kaggle – Credit Card Fraud Dataset
* RBI – Banking Fraud Reports
* IEEE Research Papers on Fraud Detection
* Microsoft Power BI Documentation
* World Bank Digital Payment Reports
* Statista Fraud Statistics
* Investopedia – Financial Risk Concepts

---
