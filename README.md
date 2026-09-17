# Airbnb Seattle — Tableau Dashboard

An interactive Tableau dashboard analyzing Airbnb listing and revenue data for Seattle, WA, broken down by zip code, bedroom count, and time.

![Dashboard Preview](https://raw.githubusercontent.com/Bristisul123/Airbnb-Dashboard/main/Dashboard.png)

## 📊 Overview

This dashboard provides a high-level and granular view of Airbnb performance across Seattle neighborhoods (by zip code), helping identify pricing trends, revenue patterns, and listing distribution.

## 🔑 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Revenue | 98,299,455 |
| Total Listings | 2,873 |
| Average Bedrooms | 1.306 |
| Average Price | 140.5 |

## 📈 Visualizations

- **Average Price per Bedroom** — Bar chart showing how average nightly price scales with number of bedrooms (0–6 bedrooms).
- **Revenue for Year** — Line chart tracking weekly revenue trends across the calendar year.
- **Distinct Count of Bedroom Listing** — Table breaking down listing counts by bedroom count (1–6 bedrooms).
- **Price per Zipcode** — Choropleth map of Seattle showing average price distribution across zip codes.
- **Price by Zipcode** — Bar chart ranking all zip codes by average listing price, from highest to lowest.

## 🗂️ Fields Used

- Zipcode
- Bedrooms
- Price
- Date (Week/Year)
- Revenue

## 🛠️ Tools

- **Tableau** (Tableau Desktop / Tableau Public)
- Data source: Airbnb Seattle listings dataset

## 🚀 How to View

1. Open the `.twbx` file in Tableau Desktop or Tableau Reader, **or**
2. View the published version on [Tableau Public](#) *(replace with your link once published)*

## 📁 Repository Contents

```
├── Dashboard.png          # Dashboard screenshot
├── airbnb_dashboard.twbx  # Tableau packaged workbook (add your file)
└── README.md
```

## 📌 Insights

- Average price increases steadily with bedroom count, with a sharp jump for 5–6 bedroom listings.
- Revenue shows a strong seasonal build-up through the year with a sharp drop at year-end (likely partial/incomplete data for the last period).
- Zip code 98134 and 98119 show the highest average prices, while 98125 and 98133 are on the lower end.
- The majority of listings are 1-bedroom units (1,811 out of 2,873 total).

