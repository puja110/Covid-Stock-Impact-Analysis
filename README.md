# COVID - Stock Impact Analysis

This project explores the impact of COVID-19 on the Canadian Stock Market by analyzing pandemic data alongside stock performance across various sectors. By examining trends, correlations, and economic recovery patterns, we aim to understand how health crises can influence financial markets.

---

## Canada COVID-19 Data

This dataset provides daily COVID-19 statistics across Canadian provinces and territories.

- **Data Source:** Covid19 Data Worldwide
- **Data Size:** 8,752 rows × 8 columns
- **Use Cases:**
  - Tracking COVID-19 case trends
  - Analyzing regional impact over time
  - Correlating pandemic severity with market behavior

---

## Canada Stock Market Data

This dataset includes daily stock performance for major companies in Canada, using data pulled from the `yfinance` library.

- **Data Source:** YFinance Library
- **Symbols Used:**  
  `^GSPTSE`, `BNS.TO`, `WCP.TO`, `SES.TO`, `POW.TO`, `ENGH.TO`, `RUS.TO`, `IAG.TO`, `FC.TO`, `CNQ.TO`, `RY.TO`
- **Data Size:** 18,852 rows × 8 columns
- **Use Cases:**
  - Monitoring stock trends during COVID-19
  - Analyzing volume and price fluctuations
  - Understanding sector-level economic response

---

## Objective

To uncover:

- Trends and correlations between COVID-19 spread and stock volatility
- How different sectors responded to the pandemic
- Insights into economic recovery across Canada

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib
- YFinance library
