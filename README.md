# 🛢️ Indian Oil Stock Intelligence Dashboard (Power BI)
An interactive Power BI dashboard that analyzes **Indian Oil Corporation (IOC)** stock prices and trading volume from **30 July 2018 to July 2023**, with views by year, quarter, month and weekday.
![Main Menu](screenshots/01_main_menu.png)
## 🎯 Objective
To understand how IOC's Open, High, Low, Close prices and trading Volume changed over time, and to find which periods and weekdays stand out.
## 📁 Repository Structure
| Folder | Description |
|---|---|
| `data/` | Stock dataset (CSV) |
| `dashboard/` | Power BI file (.pbix) and PDF export |
| `screenshots/` | Images of all 13 report pages |
## 🧩 Dashboard Pages
| Page | What it shows | Preview |
|---|---|---|
| Main Menu | Navigation buttons to every page | [View](screenshots/01_main_menu.png) |
| Year Analysis | Yearly Open, Close, High, Low, Volume | [View](screenshots/02_year_analysis.png) |
| Month Analysis | Monthly comparison across all years | [View](screenshots/03_month_analysis.png) |
| Quarter Analysis | Q1–Q4 price and volume comparison | [View](screenshots/04_quarter_analysis.png) |
| Day Analysis | Monday–Friday comparison | [View](screenshots/05_day_analysis.png) |
| Close Waterfall | Close change 2019 → 2020 by month, quarter, day and candlestick type | [View](screenshots/06_close_waterfall_2019_2020.png) |
| Data Table | Daily records with Volume tier (Low / Medium) | [View](screenshots/07_daily_data_table.png) |
| Decomposition Trees | Drill-down of Open, Close, High, Low by Year → Month → Quarter | [Open](screenshots/08_open_decomposition_tree.png) · [Close](screenshots/09_close_decomposition_tree.png) · [High](screenshots/10_high_decomposition_tree.png) · [Low](screenshots/11_low_decomposition_tree.png) |
| Open Split | Open change 2018 → 2019 | [View](screenshots/12_open_split_waterfall.png) |
| Close Split | Close change 2020 → 2021 | [View](screenshots/13_close_split_waterfall.png) |
### Year Analysis
![Year](screenshots/02_year_analysis.png)
### Quarter Analysis
![Quarter](screenshots/04_quarter_analysis.png)
## 🗂️ Dataset
- **Source:** [Add source, e.g. Yahoo Finance / NSE India]
- **Period:** 30 July 2018 to July 2023
- **Original columns:** Date, Open, High, Low, Close, Volume
- **Created columns:** Day, DayOfWeek, Month, Month NO, Quarter, Year, `candlestick_type` (Bullish / Bearish / Neutral), `Volume_tier` (Low <15M, Medium 15–30M)
## 📈 Visuals Used
KPI cards · Bar and column charts · Line chart · Pie and donut charts · Funnel chart · Waterfall charts · Decomposition tree · Table · Date, Year, Quarter slicers · Navigation buttons
## 🔍 Key Insights
- **2019** had the highest yearly Close total (23.0K), and 2020 recorded the highest trading volume (8bn).
- 2018 and 2023 are **partial years**, so their totals are lower.
- **Q1** had the highest trading volume (8bn), and the four quarters' price totals were very close (24.5%–25.5% share).
- **July** had the highest monthly Open total (8.7K) and **April** the lowest (7.0K).
- Close fell from 23.0K (2019) to 15.1K (2020), then recovered to 18.0K (2021).
*Note: these figures are based on **Sum** of prices, so they depend on the number of trading days in each period.*
## 🛠️ Tools Used
- Power BI Desktop
- Power Query / DAX
- Excel / CSV
## ▶️ How to Open
1. Download or clone this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open `dashboard/indianoil_stock_dashboard.pbix`.
4. If asked, point the data source to `data/indianoil_stock_data.csv`.
## 🚀 Future Improvements
- Use **Average** or **Closing price** instead of Sum for price metrics.
- Add moving averages and daily returns.
- Add a volatility analysis page.
## 👤 Author
**RAJ SINGH**
[https://www.linkedin.com/in/raj-singh2705/] | [https://github.com/RajSingh270]
