# NYC COVID-19 and the Housing Market

Click [here](https://2hyunie.github.io/qmss-dv-group-g/index.html) to view our website.
The codes and datasets used for the content of the website can be found [here](https://github.com/QMSS-G5063-2022/Group_G_Covid_Housing_Prices) and the codes used to build the website can be found on this repository.

This project aims to explore how the Covid-19 pandemic has impacted the housing market by focusing on comparing the sales price across NYC. The project will track how the waves of Covid-19 cases affected the price fluctuations by conducting data analysis on quarterly tabular, spatial and text data, with illustrations.

Research Questions:
* How has Covid-19 affected the housing market via housing prices over time?
* How has COVID-19 affected the NYC housing market? Are there any regional variations in the housing price fluctuations?
* How has the overall perspective on Covid-19 changed over time?

The website has been coded using `HTML`, `CSS`, and `JavaScript` from scratch to build a simple, yet user-friendly website.

## Part 1: Trends in Covid-19 and Sales Price

Part 1 examines Covid-19 rate and sales prices in all five boroughs in NYC from the 3rd quarter of 2020 to the 1st quarter of 2022. `ggplot2` and `ggplotly` in R is used to create the visualizations.

## Part 2: Geographical Variations

This section maps out the changes in the NYC Covid-19 case rates and housing prices by quarter using `ggplot2`. Specific neighborhoods are consulted from the analysis.

Two hypothesis are tested in this section:

1. The association between Covid-19 and housing prices is negative.
2. The association between Covid-19 and housing prices is positive.

## Part 3: Text Analysis

The final section studies the changes of perspective on Covid-19 over time (2020 Q3 vs. 2021 Q4) by conducting sentiment analysis and creating word clouds using Python.

## Data Sources

* Covid-19: [Case Rate by MODZCTA](https://github.com/nychealth/coronavirus-data/blob/master/trends/caserate-by-modzcta.csv)
* Housing: [NYC Housing Sales Data](https://www1.nyc.gov/site/finance/taxes/property-annualized-sales-update.page)
* Mapping: [Modified Zip Code Tabulation Areas (MODZCTA)](https://data.cityofnewyork.us/Health/Modified-Zip-Code-Tabulation-Areas-MODZCTA-/pri4-ifjk)
* Text Analysis: [Tweets](https://github.com/QMSS-G5063-2022/Group_G_Covid_Housing_Prices/tree/main/Part3_data)
