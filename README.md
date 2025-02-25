# World Bank Economic Indicator Analysis for Top 10 Economies (2025 Projections)

This project analyzes and visualizes key economic indicators from the World Bank for the top 10 economies projected for 2025.  The analysis aims to provide insights into the economic performance and trends of these leading nations.

## Table of Contents

*   [Introduction](#introduction)
*   [Data Source](#data-source)
*   [Methodology](#methodology)
*   [Key Findings](#key-findings)
*   [Technologies Used](#technologies-used)

## Introduction

Understanding the economic landscape of the world's leading economies is crucial for policymakers, businesses, and researchers. This project leverages World Bank data to examine various economic indicators for the top 10 economies projected for 2025.  By visualizing these indicators, we can identify trends, compare performance across nations, and gain a deeper understanding of the global economic dynamics.  Note that the 2025 data used here is based on projections and may vary from actual figures.

## Data Source

The data for this project was obtained from https://mavenanalytics.io/data-playground. Please refer to the data dictionary file to understand column wise descriptions.

*(Add more indicators as needed)*

## Methodology

1.  **Data Cleaning and Preprocessing:**  The data was cleaned and preprocessed using Python with the Pandas library. This involved handling missing values, converting data types, and ensuring data consistency.
3.  **Data Analysis:** Descriptive statistics were calculated, and trends were analyzed for each indicator and country.
4.  **Data Visualization:**  Matplotlib and Seaborn were used to create informative visualizations.

## Key Findings

* The World Bank dataset needed to be cleaned by handling negative/ suspect values and imputing missing values with realistic data points.
* The countries have been segregated by income group. Using a histogram, I was able to see that high income OECD countries have more earners in the $ 25000 - $ 75000 category than high income non OECD countries
* While the entire dataset had 211 countries, I had to slice the dataset to contain only the top 10 economies to focus my analysis.
* GDPs for the top 10 countries were plotted over time to check for inflection points.
* Post dot com revolution (~in 2000); I was able to see the internet adoption over time for the top 10 economies.India stoodout in this visual, seeing an exponential growth while others saw linear growth.
* There is a positive linear correlation between gdp per capita and internet penetration as shown by the linear regression model metrics.

## Technologies Used

*   Python
*   Pandas
*   Matplotlib
*   Seaborn
