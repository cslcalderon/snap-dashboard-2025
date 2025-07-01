# Texas SNAP Data Dashboard

This repository contains my **Texas SNAP data analysis and dashboard project**, using **ArcGIS, R, and Quarto** to visualize and analyze indicators of SNAP utilization across Texas.

## Data Sources

- **American Community Survey (ACS)** – Used for county and regional demographic indicators.
- **Feeding America** – Provided food insecurity rates and related indicators for comparative analysis.
- **Texas Health and Human Services Commission (HHSC)** – SNAP participant data by county and region.

These datasets collectively highlight the reach and critical importance of SNAP in Texas.

## Repository Structure

- `Sofia_SNAP_Data.qmd` – Quarto markdown file with **data cleaning, wrangling, and visualizations**.
- `Sofia_SNAP_Data.html` – Rendered report for easy viewing.
- `SNAP_Counties.qmd` – Additional analysis focusing on county-level breakdowns.
- `SNAP_Dashboard.Rproj` – Project file to open directly in **RStudio** for environment consistency.
- `raw_data/` and `Sofia_SNAP_Data_files/` – Contain input data and intermediate cleaned files.
- `County_12_Regions.csv` – Reference file for regional grouping of Texas counties.

## Usage

To view and interact with the `.qmd` files:

1. Clone or download the repository.
2. Open `SNAP_Dashboard.Rproj` in **RStudio** to ensure your environment aligns with the project.
3. Open `Sofia_SNAP_Data.qmd` or `SNAP_Counties.qmd` and **render them within RStudio** to generate updated HTML reports.
4. Ensure required packages (`tidyverse`, `quarto`, `sf`, `janitor`, etc.) are installed before rendering.

## Purpose

This project aims to **visualize SNAP participation across Texas** and understand how it intersects with food insecurity and regional disparities. By using clear, accessible maps and charts, the project highlights the **importance of maintaining strong SNAP support to serve millions of Texans in need.**

## Visualization

You can view the way the data was visualized here: https://experience.arcgis.com/experience/0baf2e6448b94eed9984b3164885edd0/page/SNAP-Overview?draft=true&org=EveryTexan
I used ArcGIS and Flourish to visualize data!
