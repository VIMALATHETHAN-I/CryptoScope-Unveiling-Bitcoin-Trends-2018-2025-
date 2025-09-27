<h1 align="center">📊CryptoScope: Unveiling Bitcoin Trends (2018–2025)</h1>


**CryptoScope** is a comprehensive Python-based analysis project that explores **Bitcoin’s price, trading activity, volatility, and patterns** from **January 2018 to September 2025**. The project leverages **Python libraries** like Pandas, NumPy, Matplotlib, and Seaborn to clean data, analyze trends, and visualize insights.

---

## 🔍 Project Overview

Bitcoin is a highly volatile and cyclical cryptocurrency. Understanding its price dynamics, trading behavior, and volatility patterns is essential for traders, analysts, and enthusiasts. This project performs a **deep exploratory data analysis (EDA)** on Bitcoin’s historical trading data to identify trends, anomalies, and correlations.

**What i did:**
- Handled high-frequency (15-minute interval) Bitcoin data.
- Identifid missing timestamps and clean the dataset.
- Analyzed price trends, volume, trades, and volatility.
- Discovered seasonality patterns, correlations, and anomalies.
- Visualized findings with intuitive charts and plots.
- Derived actionable insights for traders and analysts.

---

## 🧹 Data Cleaning & Preprocessing

1. **Convert Timestamps:**  
   - Converted `Open time` and `Close time` to **datetime** objects for time-based analysis.

2. **Remove Duplicates & Handle Missing Data:**  
   - Identified missing timestamps in the 15-minute interval data and removed duplicates.
   - Reindexed the dataset to include missing intervals.
   - Interpolated price columns using **time-based interpolation** and volume/trade columns using **linear interpolation**.

3. **Drop Unnecessary Columns:**  
   - Removed irrelevant columns like `Ignore` for cleaner analysis.

4. **Final Verification:**  
   - Checked for missing values, validated data types, and recomputed `Close time` for consistency.

---

## 📈 Exploratory Data Analysis (EDA)

- **Price Analysis:**  
  - Daily closing price trends, 7-day & 30-day moving averages.
  - Identified bull & bear market cycles and crossovers.

- **Volatility Analysis:**  
  - Daily returns and 30-day rolling volatility.
  - Identified periods of high risk and market instability.

- **Volume & Trades:**  
  - Average trading volume per hour, number of trades over time.
  - Revealed peak trading hours and market adoption patterns.

- **Seasonality Patterns:**  
  - Hour-of-day, day-of-week, and monthly trends in trading activity.

- **Correlation Analysis:**  
  - Relationship between price, volume, trades, and taker buy activity.
  - Observed strong correlation among volume, trades, and taker buy volume, but weak correlation with price.

- **Anomaly Detection:**  
  - Top 10 crash days and rally days for Bitcoin.
  - Highlighted extreme market events for risk assessment.

---

## 📊 Key Insights

- Bitcoin exhibits **distinct bull & bear market cycles** from 2018 to 2025.
- **7-day and 30-day moving averages** capture short-term and long-term price trends.
- **Volatility spikes** coincide with major events like the COVID-19 crash and 2021 bull run.
- **Trading activity peaks** during US and European market hours.
- **Volume, trades, and taker activity** are strongly correlated among themselves but weakly with price.
- Bitcoin remains a **highly cyclical, volatile, sentiment-driven asset**.

---

## 🔮 Future Scope

- Extend analysis to **other cryptocurrencies** such as Ethereum (ETH), Solana (SOL), etc., for cross-market insights.
- Apply **machine learning models** (ARIMA, LSTM) for price prediction and volatility forecasting.

---

## 🛠️ Technologies & Libraries

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
- **Data Visualization:** Line plots, rolling volatility charts, heatmaps, scatter plots, histograms, boxplots
- **Time Series Analysis:** Handling missing timestamps, moving averages, rolling statistics

---



