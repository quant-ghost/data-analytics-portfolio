# Sales & Geospatial Analytics Dashboard | Yandex DataLens

## Project Overview

An interactive sales and geospatial analytics dashboard developed using **Yandex DataLens** to monitor business performance, evaluate sales trends, and analyze the geographic distribution of customer orders.

The dashboard combines sales data from Google Sheets with geographic coordinates to provide both financial insights and location-based analysis in a single interactive environment.

## Business Objectives

The primary objective is to provide a clear overview of sales performance and geographic demand by:

- Monitoring actual sales against planned targets (Plan vs. Actual).
- Identifying top-performing products based on cumulative sales.
- Tracking the number of customer applications and orders.
- Analyzing regional sales and delivery distribution.
- Identifying high-demand geographic areas to support business and logistics decisions.

## Data Sources & Workflow

**Google Sheets** served as the primary data source, while geocoding tools were used to convert customer addresses into geographic coordinates.

The workflow included:

1. **Data Collection:** Gathering and organizing sales transactions and application records in Google Sheets.
2. **Data Preparation:** Structuring records and preparing the dataset for analysis.
3. **Geocoding:** Converting customer addresses into latitude and longitude coordinates.
4. **Data Integration:** Connecting the prepared Google Sheets dataset to Yandex DataLens.
5. **Dashboard Development:** Building interactive visualizations, KPI indicators, sales comparisons, and geographic maps.

## Tools & Technologies

- **Google Sheets** – Data collection, organization, and storage.
- **Geocoding Tools / API** – Address processing and geographic coordinate extraction.
- **Yandex DataLens** – Data visualization, KPI development, calculated metrics, and geospatial analytics.

## Data Analysis & Preparation

The project involved several data preparation and analytical steps:

- Organized sales transactions and application records.
- Processed customer address data and extracted geographic coordinates.
- Created geographic points using `GEOPOINT([lat], [lng])`.
- Connected Google Sheets as a data source in Yandex DataLens.
- Calculated cumulative sales totals (*Накопительный итог*).
- Compared planned and actual sales performance (*План vs. Факт*).
- Developed geographic heatmaps and location-based visualizations.

## Key Metrics & KPIs

The dashboard provides an overview of the following business indicators:

| KPI | Description |
|---|---|
| Total Applications | Total number of unique applications (27,492) |
| Total Sales | Overall sales revenue (170,070,213) |
| Plan vs. Actual | Comparison of actual sales against planned targets |
| Cumulative Product Sales | Product performance ranking based on cumulative sales |
| Geographic Distribution | Geographic concentration and distribution of orders |

## Dashboard Features

- **KPI Overview:** Summary of key sales and application metrics.
- **Sales Performance:** Comparison of planned and actual sales.
- **Product Analysis:** Product-level sales ranking and cumulative performance.
- **Geospatial Analysis:** Interactive maps with geographic points and heatmaps.
- **Dynamic Filtering:** Date range and application date filters for more detailed analysis.
- **Regional Insights:** Visualization of order concentration across different geographic areas.

## Business Value

The dashboard transforms raw sales and location data into actionable business insights. It helps decision-makers monitor sales targets, identify high-performing products, understand regional demand, and recognize areas with high order concentration.

These insights can support better sales planning, marketing decisions, and logistics optimization.

## Dashboard Preview

![Yandex DataLens Sales & Geospatial Analytics Dashboard](./sales_datalens_dashboard.png)

## Data Confidentiality

This project was developed using real transaction records. Customer-identifying information and sensitive business details have been anonymized or modified to protect data confidentiality while preserving the analytical structure and functionality of the dashboard.
