# Real-Time-Payment-Fraud-Detection-Risk-Monitoring-Analysis
📊 Enterprise fraud intelligence dashboard built with Power BI &amp; Microsoft Fabric — real-time monitoring of fraud rate, transaction trends, risk categories &amp; geographic hotspots across banks, payment methods &amp; device types.

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=30&duration=3000&color=F7C200&center=true&vCenter=true&width=900&lines=Power+BI+Project;Real-Time+Fraud+Detection;Interactive+Risk+Analytics;FinTech+Dashboard" />
</p>


# 🛡️ Payment Fraud Detection & Risk Monitoring

### *Turning transaction noise into fraud intelligence — before damage is done*

<br>

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://fabric.microsoft.com/)
[![Fluent 2](https://img.shields.io/badge/Theme-Fluent%202-5C2D91?style=for-the-badge&logo=microsoft&logoColor=white)]()
[![Canvas](https://img.shields.io/badge/Canvas-1920×1080-FF6B6B?style=for-the-badge)]()
[![Pages](https://img.shields.io/badge/Report%20Pages-3-00C49F?style=for-the-badge)]()
[![Visuals](https://img.shields.io/badge/Total%20Visuals-80+-orange?style=for-the-badge)]()
[![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge)]()

<br>

> **"Every fraudulent transaction leaves a fingerprint. This dashboard finds it."**

<img width="870" height="487" alt="Screenshot 2026-05-01 201255" src="https://github.com/user-attachments/assets/612d1748-b82f-410f-9016-1e41d8c1e7b7" />

</div>

---

## 📖 What Is This?

This is a **production-grade Power BI intelligence platform** built for financial institutions to detect, monitor, and respond to payment fraud in real time. It's not just a dashboard — it's a **three-layer analytical system** that moves from macro KPIs all the way down to individual risk profiling.

Built on **Microsoft Fabric** with the **Fluent 2 design system**, this report was engineered for:

- 🔴 **Real-time fraud detection** at the transaction level
- 📍 **Geographic fraud mapping** by location
- 🏦 **Multi-bank comparison** of fraud exposure
- 📱 **Device-type forensics** on fraud vectors
- ⚠️ **Risk category scoring** and segmentation
- 📅 **Month-over-month trend tracking** with dual-axis analysis

---

## ⚡ Quick Stats at a Glance

| Attribute | Detail |
|-----------|--------|
| 📄 **Report Pages** | 3 (Insights · Fraud Analysis · Risk Analysis) |
| 📊 **Total Visuals** | 80+ across all pages |
| 🔢 **Unique Chart Types** | 19 distinct visual types |
| 📏 **Canvas Resolution** | 1920 × 1080 px (Full HD) |
| 🎨 **Theme** | Microsoft Fluent 2 (CY26SU03) |
| 🧮 **Measures Tracked** | 10 calculated DAX measures |
| 📐 **Dimensions** | 13 data dimensions |
| 🎛️ **Interactive Slicers** | 7 slicers + 2 advanced filter panels |
| 🔘 **Action Buttons** | 3 page-navigation buttons |
| 🖼️ **Embedded Icons** | 10 custom fraud-domain icons |

---

## 🗺️ Dashboard Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│              POWER BI FRAUD INTELLIGENCE PLATFORM               │
├─────────────────┬──────────────────────┬────────────────────────┤
│   PAGE 1        │      PAGE 2          │       PAGE 3           │
│   📊 Insights   │  🚨 Fraud Analysis   │   ⚠️ Risk Analysis     │
│                 │                      │                        │
│  Executive KPIs │  Fraud forensics     │  Risk profiling        │
│  Volume trends  │  Pattern detection   │  Exposure scoring      │
│  Geographic map │  Bank comparison     │  High-risk flagging    │
│  Method funnel  │  Device breakdown    │  Predictive signals    │
└─────────────────┴──────────────────────┴────────────────────────┘
         │                  │                       │
         ▼                  ▼                       ▼
  [Total Transactions] [Fraud Transactions]  [High Risk Txns]
  [Total Amount]       [Fraud Amount]        [Fraud Amount %]
  [Avg Transactions]   [Fraud Rate %]        [Risk Category]
```

---

## 📊 Page-by-Page Breakdown

### ━━━ PAGE 1 · 📊 Insights ━━━
> *Executive command center — the 50,000-foot view of payment fraud*

This is the **first page** users land on, designed for speed-to-insight. It answers: **"What is happening across our entire payment ecosystem right now?"**

**KPI Cards (Top Strip)**

| Card | Measure | Purpose |
|------|---------|---------|
| 💳 Total Transactions | `Total Transactions` | Volume baseline |
| 💰 Fraud Amount | `Fraud Amount` | Total monetary loss |
| 📈 Avg Transactions | `Avg Transactions` | Normal volume benchmark |
| 🔴 High Risk Transactions | `High Risk Transactions` | Critical exposure count |
| 💵 Total Amount | `Total Amount` | Full transaction value |

**Charts & Analysis Panels**

| Visual | Type | Dimensions Used | Insight Generated |
|--------|------|-----------------|-------------------|
| Monthly Fraud Volume | Line Chart | Month → Fraud Transactions | Surge detection over time |
| Monthly Fraud Amount | Line Chart | Month → Fraud Amount | Monetary trend tracking |
| Transaction Volume Trend | Line Chart | Month → Total Transactions | Baseline vs anomaly |
| Avg Transactions Trend | Line Chart | Month → Avg Transactions | Moving average signal |
| High Risk Monthly Trend | Line Chart | Month → High Risk Transactions | Escalation tracking |
| Payment Method Funnel | **Funnel Chart** | Payment Method → Total Transactions | Channel entry-point analysis |
| Location Fraud Map | **Map Visual** | Location | Geographic hotspot identification |
| Transaction Amount by Month | **Treemap** | Month → Transaction Amount | Proportional volume visualization |

---

### ━━━ PAGE 2 · 🚨 Fraud Analysis ━━━
> *Forensic deep-dive — where fraud lives, breathes, and moves*

This page answers: **"Who is committing fraud, through which channels, and on which devices?"**

**KPI Cards**

| Card | Measure |
|------|---------|
| 🚨 Fraud Transactions | `Fraud Transactions` |
| 💸 Fraud Amount | `Fraud Amount` |
| 📊 Fraud Rate % | `Fraud Rate %` |
| ⚠️ High Risk Transactions | `High Risk Transactions` |

**Charts & Analysis Panels**

| Visual | Type | Dimensions | Business Question Answered |
|--------|------|------------|---------------------------|
| Fraud by Bank | **Horizontal Bar Chart** | Bank Name → Fraud Transactions | Which institution carries highest fraud burden? |
| Fraud by Device Type | **Pie Chart** | Device Type → Fraud Transactions | Mobile vs desktop vs other attack vectors |
| Previous Fraud × Transaction Type | **Ribbon Chart** | Previous Fraud Count + Transaction Type → Fraud Transactions | Do repeat offenders use the same transaction types? |
| Location × Device Type Combo | **Line + Stacked Column Combo** | Location + Device Type → Fraud Amount & Transactions | Multi-dimensional geographic + device analysis |
| Fraud Amount Trend | Line Chart | Month → Fraud Amount | Monetary loss evolution |
| Fraud Rate % Trend | Line Chart | Month → Fraud Rate % | Detection rate benchmarking |
| Fraud Count Trend | Line Chart | Month → Fraud Transactions | Volume of incidents |
| Total Amount Trend | Line Chart | Month → Total Amount | Full portfolio exposure |

**Slicer Controls (Page 2)**

| Slicer | Field | Use Case |
|--------|-------|----------|
| 🏦 Bank Filter | `Bank_Name` | Isolate specific institution |
| 🌍 International Flag | `Is_International` | Toggle domestic vs cross-border |

---

### ━━━ PAGE 3 · ⚠️ Risk Analysis ━━━
> *Predictive risk layer — flagging tomorrow's fraud today*

This page answers: **"Which transactions and segments carry the highest unresolved risk?"**

**KPI Cards**

| Card | Measure |
|------|---------|
| 🔴 High Risk Transactions | `Sum(High Risk Transactions)` |
| 📊 Avg Transactions | `Avg Transactions` |
| 💸 Fraud Amount | `Fraud Amount` |
| 📉 Fraud Amount % | `Fraud Amount %` |

**Charts & Analysis Panels**

| Visual | Type | Dimensions | Risk Insight |
|--------|------|------------|--------------|
| Risk Category Table | **Table** | Risk Category | Full risk-level segmentation |
| Previous Fraud Count Donut | **Donut Chart** | Previous Fraud Count → Risk Category Count | Recidivist profiling |
| Payment Method × Risk | **Scatter Chart** | Payment Method × Total Amount × Risk Category × Fraud Count | Multi-variable risk mapping |
| Fraud Txns × Fraud Amount% | **Dual-Axis Line** | Month → Fraud Transactions + Fraud Amount % | Volume-to-value correlation |
| Fraud Amount% Trend | Line Chart | Month → Fraud Amount % | Proportional loss trajectory |
| High Risk Trend | Line Chart | Month → Sum(High Risk Transactions) | Risk escalation monitoring |
| Transaction Type Waterfall | **Waterfall Chart** | Transaction Type → Fraud Transactions (breakdown: High Risk) | Incremental fraud contribution by type |

**Slicer Controls (Page 3)**

| Slicer | Field |
|--------|-------|
| 📅 Year | `Year` |
| 🏦 Bank Name | `Bank_Name` |
| 🔁 Previous Fraud Count | `Previous_Fraud_Count` |
| ⚠️ High Risk Transactions (Advanced) | `High Risk Transactions` |
| 👤 Account Age Months | `Account_Age_Months` |

---

## 🧩 Full Data Model

### 📐 Dimensions

```
┌──────────────────────────────────────────────────────────────┐
│                     FACT TABLE DIMENSIONS                    │
├─────────────────────┬────────────────────────────────────────┤
│ Field               │ Description                            │
├─────────────────────┼────────────────────────────────────────┤
│ Bank_Name           │ Financial institution name             │
│ Transaction_Type    │ Wire / ACH / POS / Online / ATM etc.  │
│ Payment_Method      │ Card / UPI / Net Banking / Wallet      │
│ Device_Type         │ Mobile / Desktop / Tablet / ATM        │
│ Location            │ City or region of transaction origin   │
│ Risk Category       │ Low / Medium / High / Critical         │
│ Is_International    │ Boolean — cross-border transaction flag │
│ Previous_Fraud_Count│ Historical fraud events per entity     │
│ Account_Age_Months  │ Customer account tenure in months      │
│ Month               │ Calendar month (time dimension)        │
│ Year                │ Calendar year (time dimension)         │
└─────────────────────┴────────────────────────────────────────┘
```

### 📏 Calculated DAX Measures

```dax
-- Core Fraud KPIs
[Fraud Transactions]    = COUNT of confirmed fraud events
[Fraud Amount]          = SUM of monetary value of fraudulent transactions
[Fraud Amount%]         = [Fraud Amount] / [Total Amount]
[Fraud Rate%]           = [Fraud Transactions] / [Total Transactions]

-- Volume Metrics
[Total Transactions]    = COUNT of all transactions in scope
[Total Amount]          = SUM of all transaction values
[Avg Transactions]      = AVERAGE transaction count per period

-- Risk Metrics
[High Risk Transactions] = COUNT of transactions classified HIGH risk
```

### Embedded Icon Library

| Icon | File Reference | Semantic Meaning |
|------|----------------|-----------------|
| 🚨 | `alaram` | Alert / warning signal |
| 🛡️ | `anti-corruption` | Anti-fraud protection |
| 🏷️ | `discount` | Anomalous discount fraud |
| ⚠️ | `fraud-alert` | Active fraud flag |
| 🔒 | `lockers` | Account security lock |
| 💰 | `money-bag` | Total monetary value |
| ❌ | `no-money` | Loss / write-off event |
| 💳 | `transaction` | Transaction event marker |

---

### Connect Your Data Source

1. Go to **Home → Transform Data → Data Source Settings**
2. Update connection string to your data warehouse / database
3. Click **Close & Apply**
4. Hit **Refresh** to pull live data

---

## 🎯 Who Is This For?

| Persona | Primary Pages | Key Questions Answered |
|---------|--------------|----------------------|
| 🔍 Fraud Analyst | Page 2 | Which channels and devices are fraud entry points? |
| 📊 Risk Officer | Page 3 | Which segments are highest risk right now? |
| 👔 CFO / Executive | Page 1 | What is the total fraud exposure this month? |
| 🏛️ Compliance Officer | Pages 1 & 2 | What is our fraud rate vs regulatory benchmarks? |
| 🤖 Data Scientist | Page 3 | How does model risk scoring map to actual fraud? |
| 🏦 Bank Operations | All pages | How does our bank compare to peers? |

---


## 📄 License

```
MIT License — use freely, contribute openly, credit kindly.
See LICENSE file for full terms.
```

---

<div align="center">


