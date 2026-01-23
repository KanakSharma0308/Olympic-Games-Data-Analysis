# Olympic-Games-Data-Analysis
Project Overview
This project provides a comprehensive analysis of historical Olympic data (from Athens 1896 to Rio 2016). The goal was to transform a large, raw dataset into an interactive dashboard to uncover trends in athlete participation, gender distribution, and country-wise performance.

Key Objectives (Problem Statements)
1. The dashboard was designed to answer several critical sports-related business questions:
2. Gender Share: What is the percentage of medals won by male vs. female athletes?
3. Participation Trends: How has the ratio of male and female participants evolved year-over-year?
4. Country Performance: Which are the Top 10 countries based on total medal count (Gold, Silver, Bronze)?
5. Elite Athletes: Who are the Top 10 Olympic medalists in history?
6. Scope of Games: Total unique sports played and total participating countries over the years.

Technical Workflow
1. Data Extraction & Transformation (ETL)
Used the Power Query Editor to clean and shape the raw data:
Data Cleaning: Removed redundant columns (Age, Height, Weight) to optimize performance.
Data Standardization: Replaced abbreviations (M/F) with full names (Male/Female) for better readability.
Merging: Performed a join between the 'Athlete Events' table and 'Country Definitions' using the NOC code.
Handling Nulls: Filtered out null values and non-medal entries to ensure accuracy in analysis.

2. Data Modeling
Integrated two primary datasets into a single flattened model for efficient querying.
Created calculated measures using DAX (where applicable) and utilized Distinct Count to track unique sports and countries.

3. Data Visualization
Built an interactive and dark-themed UI featuring:
Donut Charts: For gender-based medal share.
Stacked Area Charts: To visualize participation growth over a century.
Matrices: To provide a detailed breakdown of medal types by country.
Stacked Column Charts: To rank the most successful athletes.
KPI Cards: For high-level summaries of total sports and countries.

Tools Used
Power BI Desktop
Power Query (Data Cleaning & ETL)
Excel

Insights Uncovered
The analysis highlights a significant increase in female participation over the last few decades.
Identified the USA, Russia, and Germany as historically dominant nations across all medal categories.
Visualized the career achievements of legendary athletes like Michael Phelps.

How to View
Download the .pbix file from this repository.
Open it using Power BI Desktop.


Author: Kanak Sharma Academic Background: B.Tech in Materials and Metallurgical Engineering

