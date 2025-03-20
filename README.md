# ICC Men's T20 Worldcup'24 Dashboard

## Description
This project provides a comprehensive analysis of cricket player performance data, focusing on batting and bowling statistics. By loading, cleaning, and analyzing data from the `Main_data.xlsx` file, this project identifies key performance indicators (KPIs), uncovers performance trends, and extracts actionable insights to aid team strategies and player development.

## Objective

The main objectives of this project are:

1.  **Data Cleaning and Preprocessing:** Ensure data quality and consistency by handling missing values and standardizing formats.
2.  **Exploratory Data Analysis (EDA):** Identify key trends, outliers, and relationships within the data through statistical analysis and visualization.
3.  **KPI Calculation:** Compute key performance indicators (KPIs) for both batsmen and bowlers, such as batting average, strike rate, economy rate, and bowling average.
4.  **Actionable Insights:** Provide data-driven recommendations to enhance team strategies, player development, and talent scouting.

## Steps Involved

The project workflow consists of the following steps:

1.  **Data Collection and Loading:**
    *   Collected cricket player data from the "Batting" and "Bowling" sheets of the `Main_data.xlsx` file.

2.  **Data Cleaning and Preprocessing:**
    *   Handled missing values using appropriate imputation techniques.
    *   Ensured consistency in data types and formats across all columns.

3.  **Exploratory Data Analysis (EDA):**
    *   Computed descriptive statistics (e.g., mean, median, standard deviation) for key metrics.
    *   Created visualizations using matplotlib and seaborn to explore distributions, outliers, and relationships.

4.  **KPI Calculation:**
    *   Calculated the following key performance indicators (KPIs):
    *   **Batting Average:** Total runs scored divided by the number of outs
    *   **Strike Rate:** (Total runs scored / Total balls faced) * 100.
    *   **Economy Rate:** Total runs conceded per over bowled.
    *   **Bowling Average:** Total runs conceded divided by the number of wickets taken.
    *   **Bowling Strike Rate:** Number of balls bowled per wicket taken.

5.  **Analysis and Interpretation:**
    *   Identified top-performing batsmen and bowlers based on various KPIs.
    *   Extracted insights related to performance drivers and team-based trends.

## Findings

The key findings of the project include:

- Identification of top-performing batsmen and bowlers based on KPIs.
- Insights into performance drivers, such as the correlation between batting average and strike rate.
- Team-based trends and comparisons of player performance across different teams.
