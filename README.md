# Instracart Shopping Analysis

## Executive Summary
This project provides a comprehensive end-to-end data analysis of Instacart’s shopping dataset. The objective was to decode customer purchasing patterns, optimize operational efficiency, and identify high-value products to support data-driven decision-making.

## Tech Stack
- **Python:** Data preprocessing, cleaning, and feature engineering.
- **Tableau:** Interactive BI dashboard creation and visualization.

## Key Insights
- **Basket Size Distribution:** Analysis reveals a right-skewed distribution, identifying key customer segments.
- **Operational Peaks:** Heatmap analysis identifies peak ordering hours, crucial for logistics planning.
- **Product Quadrant:** Bubble chart visualization categorizes products by reorder rate vs. sales volume.
- **Customer Habit Formation:** Statistical analysis reveals a massive shift in loyalty. The reorder rate jumps from just 22% for new users (1-3 orders) to 81% for veteran users (31+ orders).
- **Temporal Predictability:** KDE distributions and standard deviation metrics show that most operational activity is concentrated between 9:00 AM and 5:00 PM (Mean: 13.4, Std Dev: 4.2 hours).
- **Independent Shopping Routines:** Correlation analysis (r = -0.002) proves that a customer's preferred shopping hour is a strict personal habit and is not affected by the number of days since their last order.

## Interactive Dashboard
You can view the full dashboard here:
[**Click to view the Interactive Dashboard on Tableau Public**]- https://public.tableau.com/app/profile/babak.suleymanov4455/viz/Book1_17841229383890/Dashboard3

## How to use
- Python scripts are available in the repository for data processing.
- The Tableau workbook is included for local exploration.
