# 🛢️ Indian Oil Stock Intelligence Dashboard (Power BI)
An interactive Power BI dashboard that analyzes **Indian Oil Corporation (IOC)** stock prices and trading volume from **30 July 2018 to July 2023**, with views by year, quarter, month and weekday.
## 📄 Dashboard Preview
👉 **[Click here to view the full dashboard (PDF)](indianoil_stock_dashboard.pdf)**
## 🎯 Objective
To understand how IOC's Open, High, Low, Close prices and trading Volume changed over time, and to find which periods and weekdays stand out.
## 📁 Files in this Repository
| File | Description |
|---|---|
| [Indian Oil Data (2).csv](Indian%20Oil%20Data%20%282%29.csv) | Stock dataset |
| [Indian Oil Stock Intelligence Dashboard.pbix](Indian%20Oil%20Stock%20Intelligence%20Dashboard.pbix) | Power BI report file |
| [indianoil_stock_dashboard.pdf](indianoil_stock_dashboard.pdf) | PDF export of all 13 report pages |
| `README.md` | Project documentation |
## 🧩 Dashboard Pages
| Page | What it shows |
|---|---|
| Main Menu | Navigation buttons to every page |
| Year Analysis | Yearly Open, Close, High, Low, Volume |
| Month Analysis | Monthly comparison across all years |
| Quarter Analysis | Q1–Q4 price and volume comparison |
| Day Analysis | Monday–Friday comparison |
| Close Waterfall | Close change 2019 → 2020 by month, quarter, day and candlestick type |
| Data Table | Daily records with Volume tier (Low / Medium) |
| Decomposition Trees | Drill-down of Open, Close, High, Low by Year → Month → Quarter |
| Open Split | Open change 2018 → 2019 |
| Close Split | Close change 2020 → 2021 |
## 🗂️ Dataset
- **Period:** 30 July 2018 to July 2023
- **Original columns:** Date, Open, High, Low, Close, Volume
- **Created columns:** Day, Month, Quarter, Year, `candlestick_type` (Bullish / Bearish / Neutral), `Volume_tier` (Low <15M, Medium 15–30M)
## 📈 Visuals Used
KPI cards · Bar and column charts · Line chart · Pie and donut charts · Funnel chart · Waterfall charts · Decomposition tree · Table · Slicers · Navigation buttons
## 🔍 Key Insights
- **2019** had the highest yearly Close total (23.0K), and 2020 recorded the highest trading volume (8bn).
- 2018 and 2023 are **partial years**, so their totals are lower.
- **July** had the highest monthly Open total (8.7K) and **April** the lowest (7.0K).
- Close fell from 23.0K (2019) to 15.1K (2020), then recovered to 18.0K (2021).
## 🛠️ Tools Used
Power BI Desktop · Power Query · DAX · Excel / CSV
## ▶️ How to Open
1. Download this repository (**Code → Download ZIP**) and unzip it.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open `Indian Oil Stock Intelligence Dashboard.pbix`.
4. If Power BI asks for the data, point it to `Indian Oil Data (2).csv`.
## 👤 Author
**RAJ SINGH**
[https://www.linkedin.com/in/raj-singh2705/] | [https://github.com/RajSingh270]
