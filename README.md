# NIFTY 50 Correction & Recovery Analytics

## 📊 Data-Driven Market Correction & Recovery Analysis

A Power BI financial-market analytics project designed to analyze historical NIFTY 50 corrections, drawdowns, recovery timelines and post-recovery market performance.
The project studies major market corrections and crises from 2008 onwards and transforms historical market data into an interactive analytical dashboard.
The objective is not to predict market bottoms, but to understand how markets behaved during previous corrections and how long they took to recover.
---
## 🎯 Project Objective
Market corrections are a normal part of long-term investing.
However, investors often struggle to answer questions such as:
- How deep was a historical correction?
- How long did the market take to recover?
- When was the previous All-Time High?
- What was the lowest point after the ATH?
- How many days did recovery take?
- When did NIFTY create a new ATH after recovery?
- What was the gain from the correction low to the next peak?
- How frequently do different levels of corrections occur?
- What can historical corrections teach us about disciplined investing?

This project attempts to answer these questions using historical NIFTY 50 data and Power BI.

---

## 📈 Dashboard Features

### 1. Correction Detection

The dashboard can analyze multiple correction levels:

- 5%
- 10%
- 15%
- 20%
- 25%
- 30%
- 35%
- 40%
- 45%
- 50%
- 55%

This allows the user to study market corrections at different levels of severity.

---

### 2. All-Time High Analysis

The dashboard identifies:

- Previous All-Time High
- ATH date
- Correction from ATH
- Current market value
- Current correction percentage

---

### 3. Drawdown Analysis

The project measures the depth of historical market declines from previous peaks.

Key metrics include:

- ATH value
- ATH date
- Lowest value after ATH
- Lowest point date
- Fall percentage
- Drawdown duration

---

### 4. Recovery Analysis

After a correction, the dashboard tracks the recovery process.

It analyzes:

- Recovery date
- Number of recovery days
- Peak after recovery
- New ATH date
- Gain from correction low to new peak
- Total duration of the correction/recovery cycle

---

## 📊 Major Market Events Analyzed

The dashboard currently analyzes major NIFTY 50 market corrections including:

| Period | Market Event |
|---|---|
| 2008 | Global Financial Crisis |
| 2010 | Euro Debt Crisis |
| 2013 | Taper Tantrum |
| 2015 | China Slowdown |
| 2018 | IL&FS Crisis |
| 2020 | COVID-19 Crash |
| 2021 | Rate Hike Correction |
| 2024 | NIFTY Correction |
| 2026 | Current Correction |

---

## 🔎 Example Analysis

The dashboard provides a historical correction table containing metrics such as:

- Crash / Correction Name
- ATH
- ATH Date
- ATL after ATH
- ATL Date
- Fall %
- Recovery Date
- Recovery Days
- Peak after Recovery
- New Peak Date
- Gain from ATL to New Peak
- Total Duration

This converts historical market movements into measurable analytical insights.

---

## 🛠️ Tools & Technologies

### Data & ETL

- Microsoft Excel
- Power Query
- Folder-based data ingestion
- Data cleaning and transformation

### Data Visualization & Analytics

- Microsoft Power BI
- DAX
- Power BI Interactive Visuals
- Dynamic Slicers
- KPI Cards
- Time-Series Analysis
- Conditional Analysis

### Version Control

- GitHub

---

## 🔄 Data Automation Workflow

The project follows a folder-based data automation approach.

```text
Historical / Fresh Excel Files
            ↓
       Automation Folder
            ↓
        Power Query
            ↓
     Data Transformation
            ↓
      Data Model in Power BI
            ↓
        DAX Measures
            ↓
   Interactive Power BI Dashboard
