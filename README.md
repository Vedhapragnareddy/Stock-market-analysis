
# Stock-market-analysis
Analysis of historical stock market data (2010-2025) using Power BI to identify long-term trends, sector volatility, and average closing prices for key stocks.
=======
# 📈 NASDAQ Stock Market Analysis: Trends, Volatility, and Volume (2010 – 2025)

## Project Overview

This repository contains the source files for the **"Stock_Market_analysis_Group_Project"** Power BI report, developed by **Al Rousan Team 2** for the **CIS 570: Business Intelligence** course at **Colorado State University**.

The project performs an end-to-end data pipeline, from ingestion and cleaning to modeling and visualization, to analyze historical NASDAQ stock price data. The primary goal is to identify patterns, volatility trends, and market behavior before and after the onset of the COVID-19 pandemic.

### Project Deliverables:

* **Power BI Project Files (.pbip):** The full, version-controlled source code for the report and semantic model.
* **Analysis Report:** A detailed document outlining the methodology, results, and limitations (See external document: `Group Project Report.docx`).

---

## 🛠️ Technology & Methodology

* **Primary Tool:** Microsoft Power BI Desktop (using the `.pbip` project format).
* **Data Sources:** A blended dataset combining initial data from **Kaggle** with supplementary historical data extracted from **Yahoo Finance** via a custom **Python script** (using the `yfinance` package).
* **Data Scope:** Daily trading data for **10 high-profile NASDAQ stocks**, spanning over 15 years, from **January 1, 2010, to April 25, 2025**.
* **Data Model:** A **Star Schema** architecture utilizing a central fact table (`stocks_combined`) linked to dimension tables (`DateTable` and `StockSectors`).
* **Key Metrics:** DAX-based measures for **7-Day Average Close**, **Daily Return %**, and **Annualized Volatility**.

---

## ❓ Business Questions Guiding the Analysis

The report was designed to answer the following key questions of practical relevance to investors and analysts:

* How have different stocks' short-term average prices evolved over time?
* Which stocks showed the highest and lowest volatility from 2010 to 2025?
* Which stocks were most actively traded post-COVID?
* What were the peak performance periods (Max 7-Day Avg Close) of individual stocks?
* Which sectors performed best in terms of average price growth?
* How has market activity (volume) trended year over year?

---

## 💡 Key Findings

The analysis consistently highlights the divergence between growth-oriented and defensive sectors, especially in the post-COVID-19 environment.

| Finding | Details and Supporting Visual |
| :--- | :--- |
| **Dominance of Growth Stocks** | **Tesla (TSLA)** and **Nvidia (NVDA)** showed exponential price growth, particularly after 2020. The **Automotive** and **Technology** sectors held the highest average prices across the entire period. |
| **Risk-Return Trade-Off** | **NVDA** and **TSLA** topped the volatility rankings, consistently showing values around **30%**. This confirms that high growth was correlated with high price fluctuation and risk. |
| **Market Stability** | The **Healthcare** (JNJ, PFE) and **Consumer Staples** (KO) sectors exhibited the lowest volatility, with **Johnson & Johnson (JNJ)** showing the lowest at roughly **12%**. These stocks served as stable, defensive investments. |
| **Post-COVID Volume Spike** | The average daily trading volume across the NASDAQ saw a dramatic surge around **2020**, peaking at nearly **91 million** shares. This was fueled by market uncertainty, stimulus measures, and a lasting increase in investor participation. |
| **Peak Timing** | Most individual stock peaks (Max 7-Day Avg Close) were concentrated between 2020 and 2022, confirming that the post-COVID market surge was the window of highest short-term performance. |

---

## 👥 Group Members

This project was completed for Dr. Hamed Qahri-Saremi by **Al Rousan Team 2** on **May 12, 2025**:

* **Mohd Saif**
* **Vedha Maramreddy**

---

## 🚀 How to View the Report

1.  **Clone or Download** this repository content.
2.  **Install** Power BI Desktop (latest version recommended for `.pbip` support).
3.  **Open** the file named `Stock_Market_analysis_Group_Project.pbip` within Power BI Desktop.
4.  The entire report, including the data model and all DAX measures, will load for interactive exploration.
6c0e94a (Finalize README and add PBIP source files)
