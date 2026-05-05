# Real-Time-Payment-Fraud-Detection-Risk-Monitoring-Analysis
Enterprise fraud intelligence dashboard built with Power BI &amp; Microsoft Fabric — real-time monitoring of fraud rate, transaction trends, risk categories &amp; geographic hotspots across banks, payment methods &amp; device types.

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=30&duration=3000&color=F7C200&center=true&vCenter=true&width=900&lines=Power+BI+Project;Real-Time+Fraud+Detection;Interactive+Risk+Analytics;FinTech+Dashboard" />
</p>


# 🛡️ Payment Fraud Detection & Risk Monitoring

### *Turning transaction noise into fraud intelligence — before damage is done*


> **"Every fraudulent transaction leaves a fingerprint. This dashboard finds it."**



---


<div align="center">

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/CSV-Data-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
<img src="https://img.shields.io/badge/Records-500-blue?style=for-the-badge" />

---

```
██████╗  █████╗ ██╗   ██╗███╗   ███╗███████╗███╗   ██╗████████╗
██╔══██╗██╔══██╗╚██╗ ██╔╝████╗ ████║██╔════╝████╗  ██║╚══██╔══╝
██████╔╝███████║ ╚████╔╝ ██╔████╔██║█████╗  ██╔██╗ ██║   ██║   
██╔═══╝ ██╔══██║  ╚██╔╝  ██║╚██╔╝██║██╔══╝  ██║╚██╗██║   ██║   
██║     ██║  ██║   ██║   ██║ ╚═╝ ██║███████╗██║ ╚████║   ██║   
╚═╝     ╚═╝  ╚═╝   ╚═╝   ╚═╝     ╚═╝╚══════╝╚═╝  ╚═══╝   ╚═╝   
```


> **Detect. Analyze. Prevent.** — A real-time fraud intelligence system built for financial institutions across India, powered by interactive Power BI dashboards and advanced risk scoring.

<br/>

[![FraudPulse](https://img.shields.io/badge/🔴%20FraudPulse-Live%20Fraud%20Feed-red?style=flat-square)](/)
[![RiskLens](https://img.shields.io/badge/🟡%20RiskLens-Risk%20Analytics-orange?style=flat-square)](/)
[![Insights](https://img.shields.io/badge/🔵%20Insights-Executive%20View-blue?style=flat-square)](/)

</div>

---


## 🎯 Project Overview

This project is a **three-page interactive Power BI dashboard** designed to monitor, detect, and analyze payment fraud in real time across major Indian cities and financial institutions. It combines raw transactional data with risk-scoring logic to surface high-risk patterns across banks, payment channels, device types, and geographic regions.

```
┌─────────────────────────────────────────────────────────────────────┐
│                    SYSTEM ARCHITECTURE                              │
│                                                                     │
│  📂 Raw CSV Data  ──►  🔄 Power BI Data Model  ──►  📊 Dashboards   │
│                                                                     │
│  500 Transactions        DAX Measures               3 Report Pages  │
│  12 Attributes           Risk Scoring               Interactive      │
│  Multi-Year Data         Category Logic             Slicers          │
└─────────────────────────────────────────────────────────────────────┘
```

**Dashboards at a glance:**
- **Insights** — Executive overview: payment method splits, monthly trends, location & device heat
- **FraudPulse** — Deep fraud breakdown: bank-wise, device-wise, location map, payment method
- **RiskLens** — Risk category analysis: fraud by risk level, transaction type waterfall, monthly fraud % trends

---

## 📊 KPI Summary — The Numbers That Matter

<div align="center">

| KPI | Value | Indicator |
|-----|-------|-----------|
| 💰 **Total Transactions** | `500` | All records across 2022–2025 |
| 🚨 **Fraud Transactions** | `50` | Confirmed fraudulent cases |
| 📉 **Fraud Rate** | `10.00%` | 1 in every 10 transactions |
| 💵 **Total Transaction Volume** | `₹1.27 Crore` | Aggregate amount |
| 🔴 **Fraud Amount** | `₹1,27,070` | Sum of fraudulent transaction values |
| 📊 **Fraud Amount %** | `0.10%` | Fraud value as % of total volume |
| ⚡ **High Risk Transactions** | `440` | Risk Score > 0.7 OR Previous Fraud Flag |
| 📈 **Avg Transaction Value** | `₹2,540` | Per-transaction mean amount |

</div>

> 🔍 **Key Insight:** While fraud accounts for only 10% of transactions by count, the concentration in high-risk accounts and repeat offenders suggests targeted intervention can significantly reduce exposure.

---

## 🗺️ Location-Wise Fraud Analysis

Fraud is mapped across **5 major Indian cities**, revealing geographic clusters of risk.

```
📍 CITY-WISE FRAUD DISTRIBUTION (out of 50 total fraud cases)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Mumbai      ████████████████████████████  14 frauds  (28.0%)
  Bangalore   ██████████████████████        11 frauds  (22.0%)
  Delhi       ████████████████████          10 frauds  (20.0%)
  Hyderabad   ██████████████████             9 frauds  (18.0%)
  Chennai     ████████████                   6 frauds  (12.0%)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

| City | Total Transactions | Fraud Cases | Fraud Rate |
|------|--------------------|-------------|------------|
| 🟥 Mumbai | 113 | 14 | **12.39%** |
| 🟧 Bangalore | 110 | 11 | **10.00%** |
| 🟨 Delhi | 84 | 10 | **11.90%** |
| 🟩 Hyderabad | 95 | 9 | **9.47%** |
| 🟦 Chennai | 98 | 6 | **6.12%** |

> ⚠️ **Mumbai & Delhi** show the highest fraud rates — these cities require enhanced real-time monitoring and stricter authentication rules.

---

## 🏦 Bank-Wise Fraud Breakdown

Analysis of fraud distribution across **5 major Indian banks**, helping identify institutional vulnerabilities.

```
🏦 BANK FRAUD LEADERBOARD (fraud transactions)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🔴 HDFC Bank       ██████████████  14 cases  (28%)
  🟠 SBI             ██████████      10 cases  (20%)
  🟡 Kotak Mahindra  █████████        9 cases  (18%)
  🟢 Axis Bank       █████████        9 cases  (18%)
  🔵 ICICI Bank      ████████         8 cases  (16%)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

| Bank | Total Transactions | Fraud Cases | Fraud Rate |
|------|--------------------|-------------|------------|
| 🔴 HDFC Bank | 110 | 14 | **12.73%** |
| 🔵 ICICI Bank | 80 | 8 | **10.00%** |
| 🟢 Axis Bank | 110 | 9 | **8.18%** |
| 🟡 Kotak Mahindra | 92 | 9 | **9.78%** |
| 🟠 SBI | 108 | 10 | **9.26%** |

> 💡 **HDFC Bank** leads in absolute fraud volume. Considering its high transaction count, a targeted fraud-prevention protocol is recommended.

---

## 📱 Device Type Analysis

Fraud does not discriminate by device — but patterns help profile attacker behaviour.

```
📱 FRAUD BY DEVICE TYPE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Mobile   ████████████████████████  21 cases  (42%)
  Desktop  ████████████████████      17 cases  (34%)
  Tablet   ████████████              12 cases  (24%)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

| Device | Total Transactions | Fraud Cases | Fraud % |
|--------|--------------------|-------------|---------|
| 📱 Mobile | 175 | 21 | **12.00%** |
| 💻 Desktop | 170 | 17 | **10.00%** |
| 📟 Tablet | 155 | 12 | **7.74%** |

**Cross-location device fraud heatmap (from dashboard):**

| Location | Desktop | Mobile | Tablet |
|----------|---------|--------|--------|
| Delhi | High | Medium | Low |
| Mumbai | High | High | Medium |
| Bangalore | Medium | High | Low |
| Chennai | Low | Medium | Low |
| Hyderabad | Low | High | Very Low |

> 📊 **Mobile devices** account for 42% of all fraud — likely due to SIM swapping, phishing apps, and insecure networks. Consider **device fingerprinting** and **step-up authentication** for mobile sessions.

---

## 💳 Payment Method Intelligence

```
💳 PAYMENT METHOD — TOTAL vs FRAUD BREAKDOWN
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Method       Total Txns   Fraud Cases   Fraud Rate
  ─────────────────────────────────────────────────
  UPI          109          8             7.34%   🟢 Lowest
  Wallet       105          10            9.52%   🟡
  Debit Card   105          12            11.43%  🔴 Highest
  Credit Card   97           9             9.28%   🟡
  Net Banking   84           11            13.10%  🔴 High Risk
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

> 💡 **UPI** is the safest payment method (7.34% fraud rate), while **Net Banking** and **Debit Card** show elevated risk. This aligns with known attack vectors: credential stuffing on Net Banking portals and card skimming for Debit Cards.

---

## ⚠️ High Risk Transactions

Risk is categorized using a composite **Risk Score** and transaction history.

```
🎯 RISK SCORE DISTRIBUTION (all 500 transactions)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🟢 Low Risk   (Score < 0.40)   ████████████████████  204  (40.8%)
  🟡 Medium     (0.40 – 0.70)    ████████████████████  145  (29.0%)
  🔴 High Risk  (Score > 0.70)   ████████████████████  151  (30.2%)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ⚡ High Risk Transactions Flagged in Dashboard: 440
```

**High Risk Fraud by Transaction Type (ATM / POS / Online):**

| Transaction Type | High Risk (0) | High Risk (1) | Net Change |
|-----------------|---------------|----------------|------------|
| ATM | 21 | -1 | ⬇ Decrease |
| POS | 16 | +1 | ⬆ Increase |
| Online | 13 | -4 | ⬇ Decrease |

> 🛡️ **440 transactions** were flagged as high risk across the dashboard — these are candidates for real-time block/challenge workflows.

---

## 🔁 Previous Fraud Count Analysis

Repeat offenders are a major signal in fraud detection. The **Previous_Fraud_Flag** field identifies customers with a prior fraud history.

```
🔁 PREVIOUS FRAUD FLAG vs CURRENT FRAUD
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  No Prior Fraud  (Flag = 0)   Total: 423  →  39 became fraud  (9.22%)
  Prior Fraud     (Flag = 1)   Total:  77  →  11 became fraud  (14.29%)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  📌 Customers with prior fraud history are 55% MORE likely to commit fraud again
```

**Fraud Transactions by Previous Fraud Count & Transaction Type (Dashboard View):**

| Previous Fraud Count | ATM | Online | POS |
|----------------------|-----|--------|-----|
| 0 | 2 | 4 | 2 |
| 1 | 4 | 6 | 2 |
| 2 | 6 | 5 | 4 |
| 3 | 2 | 1 | 3 |
| 4 | 3 | 2 | 2 |

> 🔎 **Count 2 (repeat fraudsters)** shows the highest activity across all transaction types — a critical segment for proactive account suspension or enhanced verification.

---

## 🌍 Domestic vs International Transactions

```
🌐 INTERNATIONAL TRANSACTION FILTER (Dashboard Slicer)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🇮🇳 Domestic   (Is_International = No)    ──► Baseline fraud rate: 10%
  ✈️  International (Is_International = Yes) ──► Higher anomaly risk flag
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

The dashboard provides a **live slicer** on the FraudPulse page to isolate international transactions. International transactions present elevated risk due to:

- Cross-border jurisdiction complexity
- Unfamiliar merchant categories
- Higher average transaction amounts
- Time-zone mismatches triggering velocity alerts

> ✈️ Filtering by `Is_International = Yes` allows fraud analysts to instantly scope all cross-border exposure and apply stricter review thresholds.

---

## 🏪 Merchant Category Intelligence

```
🛒 FRAUD BY MERCHANT CATEGORY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Entertainment   ██████████████  14 cases  (28%)  🔴 Highest
  Travel          ████████████    11 cases  (22%)  🟠
  E-commerce      ██████████       9 cases  (18%)  🟡
  Food            ██████████       9 cases  (18%)  🟡
  Retail          ██████           7 cases  (14%)  🟢 Lowest
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

| Category | Total | Fraud | Rate |
|----------|-------|-------|------|
| 🎬 Entertainment | 104 | 14 | **13.46%** |
| ✈️ Travel | 100 | 11 | **11.00%** |
| 🛒 E-commerce | 104 | 9 | **8.65%** |
| 🍕 Food | 87 | 9 | **10.34%** |
| 🏪 Retail | 105 | 7 | **6.67%** |

> 🎭 **Entertainment & Travel** are hotspots — typically high-value, impulsive purchases that fraudsters exploit. Card-not-present (CNP) fraud is dominant here.

---

## 📅 Monthly Transaction Trends

The **Sum of Transaction Amount by Month** treemap reveals seasonal fraud patterns.

```
📅 MONTHLY FRAUD TRANSACTION TREND (Descending Order)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  August      ████████████████████████████  Peak month
  June        ████████████████████████
  May         ████████████████████
  April       ████████████████
  March       █████████████
  October     ████████████
  September   ████████████
  December    ███████████
  July        ██████████
  January     █████████
  February    ████████
  November    ██████            Lowest fraud month
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**Key Observations:**
- 📈 **Q2 (April–June)** and **mid-year (August)** see fraud spikes — aligning with festive shopping seasons and travel peaks
- 📉 **November & February** show the lowest fraud activity
- The **Fraud Amount%** line chart on RiskLens tracks monetary risk alongside transaction count

---

## 🖥️ Dashboard Pages

### Page 1 — 📊 Insights (Executive Overview)

> *The command center for leadership and risk officers*

| Visual | Description |
|--------|-------------|
| 🔢 Total Transactions KPI | 500 total, sparkline trend |
| 💰 Fraud Amount KPI | ₹1,27,070 with declining trend |
| ⚡ High Risk KPI | 440 flagged transactions |
| 📈 Avg Transactions KPI | ₹2,540 per transaction |
| 📊 Total Transactions by Payment Method | Horizontal bar — UPI leads at 177 |
| 🌊 Fraud Transactions by Prev Fraud Count & Type | Sankey-style stream chart |
| 🗓️ Sum of Transaction Amount by Month | Treemap with month-level granularity |
| 🗺️ Location & Device Type Fraud | Combo bar + line chart per city |
| 🎛️ Slicers | Bank Name, Account Age (Months), High Risk flag |

<img width="870" height="487" alt="Screenshot 2026-05-01 201255" src="https://github.com/user-attachments/assets/53e2cc34-38c5-4a52-a342-1170be194bda" />

---

### Page 2 — 🔴 FraudPulse (Live Fraud Intelligence)

> *Real-time fraud analyst workbench*

| Visual | Description |
|--------|-------------|
| 🔢 Total Transactions | 500 |
| 🚨 Fraud Transactions | 50 confirmed |
| % Fraud Rate | 10.00% |
| 💵 Total Amount | ₹1.27M |
| 🗺️ Fraud by Location | Bing Maps pin drop across India |
| 🏦 Fraud by Bank | Horizontal bar — Kotak leads |
| 💳 Fraud by Payment Method | Column chart |
| 📱 Fraud by Device Type | Donut chart — Mobile 44% |
| 🎛️ Slicers | Bank Name, Transaction Type (ATM/Online/POS), Is_International |

<img width="869" height="486" alt="Screenshot 2026-05-05 110659" src="https://github.com/user-attachments/assets/13f0faed-5fcb-4785-851b-82015a5b5a5b" />

---

### Page 3 — 🟡 RiskLens (Risk Category Deep Dive)

> *Quantitative risk stratification for fraud prevention teams*

| Visual | Description |
|--------|-------------|
| ⚡ High Risk Transactions | 440 flagged |
| 💰 Fraud Amount | ₹1,27,070 |
| % Fraud Amount | 0.10% |
| 📈 Avg Transactions | ₹2,540 |
| 📊 Total Amount & Fraud by Risk Category + Payment | Bubble/scatter visual |
| 🍩 Fraud Amount by Risk Category (Prev Fraud Count) | Donut — Count 0 leads at 24.6% |
| 📉 Fraud Transactions by Type & High Risk | Waterfall chart (ATM/POS/Online) |
| 📅 Fraud Transactions & Fraud Amount% by Month | Dual-axis line chart |
| 🎛️ Slicers | Risk Category (Low/Medium), Year (2023/2024/2025), Previous Fraud Count |

<img width="871" height="488" alt="Screenshot 2026-05-05 110556" src="https://github.com/user-attachments/assets/b98be1a3-9bbc-4e58-a846-3a49f12cfa39" />

---

## 📁 Dataset Schema

**File:** `Fraud_Detection__Raw_Data.csv` | **Rows:** 500 | **Columns:** 12

| Column | Type | Description |
|--------|------|-------------|
| `Transaction_ID` | String | Unique transaction identifier (T100000–T100499) |
| `Date` | Date | Transaction date (2022–2025) |
| `Customer_ID` | String | Unique customer identifier |
| `Amount` | Float | Transaction amount in INR |
| `Payment_Method` | Categorical | UPI / Wallet / Debit Card / Credit Card / Net Banking |
| `Merchant_Category` | Categorical | Retail / Entertainment / E-commerce / Travel / Food |
| `Location` | Categorical | Mumbai / Bangalore / Delhi / Hyderabad / Chennai |
| `Device_Type` | Categorical | Mobile / Desktop / Tablet |
| `Bank_Name` | Categorical | HDFC / SBI / Kotak Mahindra / Axis / ICICI |
| `Previous_Fraud_Flag` | Binary | 0 = No prior fraud, 1 = Prior fraud history |
| `Risk_Score` | Float (0–1) | Composite risk score from rule engine |
| `Fraud_Label` | Binary | **Target variable** — 0 = Legitimate, 1 = Fraud |

---

## 🚀 Getting Started

### Prerequisites
```bash
✅ Power BI Desktop (latest version recommended)
✅ Microsoft Excel / Python (for CSV preprocessing)
✅ Git (for version control)
```

### Installation & Setup

```bash
1. Clone this repository
   git clone https://github.com/your-username/payment-fraud-detection.git

 2. Navigate to the project folder
cd payment-fraud-detection

 3. Open Power BI project
  → Double-click Power_BI_Project.pbix in Power BI Desktop
    OR open Power BI Desktop → File → Open → Power_BI_Project.pbix

 4. Refresh data source (if needed)
     → Home → Refresh  (point to Fraud_Detection__Raw_Data.csv)

```

### Repository Structure

```
📦 payment-fraud-detection/
│
├── 📊 Power_BI_Project.pbix       # Main Power BI dashboard file
├── 📄 Power_BI_Dashboard.pdf      # Static export of all 3 dashboard pages
├── 📂 Fraud_Detection__Raw_Data.csv  # Source dataset (500 records, 12 columns)
└── 📖 README.md                   # This file
```

---

<div align="center">

---

### 🔐 Built for Financial Intelligence. Designed for Action.

*Three dashboards. One mission: Zero Fraud.*

**Insights** `→` **FraudPulse** `→` **RiskLens**

---

![Made with Power BI](https://img.shields.io/badge/Made%20with-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data](https://img.shields.io/badge/Dataset-500%20Records-blue?style=for-the-badge)
![Fraud Rate](https://img.shields.io/badge/Fraud%20Rate-10%25-red?style=for-the-badge)
![Cities](https://img.shields.io/badge/Cities-5%20Major%20Indian%20Cities-orange?style=for-the-badge)

</div>
