# 🦠 COVID-19 Global Impact Dashboard

## Overview
A multi-page interactive Power BI dashboard analyzing the global spread 
of COVID-19 using real-world data from Johns Hopkins University (CSSE). 
The report includes a custom landing page, dynamic KPI tiles, geographic 
map visuals, and country-wise comparisons — designed for clear storytelling 
and easy navigation.

## Dashboard Features

### 🏠 Landing Page
- COVID-19 themed landing image with a navigation button to the report
- Information icon (tooltip) explaining the report's purpose and KPIs

### 📊 KPI Rotating Tiles (with Icons)
- ✅ Total Confirmed Cases
- 💀 Total Deaths
- 💚 Total Recovered
- 🌍 Total Countries/Regions Affected
- 🔴 Total Active Cases

### 📈 Visuals
- **Scroller Visual** — Country-wise total case counts in a scrolling view
- **Map Visual** — Location-wise breakdown showing:
  - Total Confirmed Cases
  - Total Deaths
  - Total Recovered
  - Incident Rate (per 100K population)
  - Fatality Ratio
- **Table Visual** — Country-wise cases sorted in descending order by total cases

### 🔧 Report Features
- Company logo displayed on report pages
- Top header with report title and details
- Last Refreshed Date & Time stamp
- Home button for navigation back to Landing Page

## Tech Stack
- Power BI Desktop
- DAX (Data Analysis Expressions)
- CSV data processing
- Custom visuals (Rotating Tile, Scroller)

## 📷 Screenshots
<img width="1555" height="748" alt="image" src="https://github.com/user-attachments/assets/e9393d35-035d-4546-a753-b13ea456bd82" />
<img width="1557" height="746" alt="image" src="https://github.com/user-attachments/assets/24876ed1-0c9d-451a-a07a-b0bc2ac62cc0" />
<img width="1365" height="737" alt="image" src="https://github.com/user-attachments/assets/07268212-db14-48ad-8af7-c190d92cc281" />

## Data Source
Johns Hopkins University CSSE COVID-19 Dataset
https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/
csse_covid_19_data/csse_covid_19_daily_reports/01-14-2022.csv

## How to Open
1. Download the `.pbix` file from this repository
2. Open with Power BI Desktop (free to download from Microsoft)
3. Data is pre-loaded — no setup needed



