# Home Sales Analysis

## Overview

This project analyzes home sales data to extract key metrics, such as the average home price by year built, the influence of the number of bedrooms, square footage, view rating, and more on home prices. To efficiently query and process the data, SparkSQL was used extensively, enabling optimized querying, caching, partitioning, and reading of Parquet-formatted data to enhance runtime performance.

## Table of Contents
1. [Overview](#overview)
2. [Results](#results)
3. [Summary](#summary)
4. [Future Work](#future-work)

## Results

#### Figure 1: Average Price for Four-Bedroom Houses Sold Per Year
![Figure 1](https://github.com/pixare7/Homes_Sales/blob/main/images/fig1.png)

*Figure 1 displays the average sale price of four-bedroom homes for each year, as calculated by a SparkSQL query.*

#### Figure 2: Average Price of Homes by Year Built
![Figure 2](https://github.com/pixare7/Homes_Sales/blob/main/images/fig2.png)

*Figure 2 shows the average home price grouped by the year each home was built, highlighting any trends in property values over time.*

#### Figure 3: Run Time Improvement with Caching
![Figure 3](https://github.com/pixare7/Homes_Sales/blob/main/images/fig3.png)

*The above runtime illustrates the efficiency gained by caching temporary tables, resulting in nearly a 50% reduction in execution time.*

## Summary

In this project, SparkSQL was instrumental in providing insights into the home sales data by enabling quick aggregation, filtering, and partitioning. The use of cached and partitioned Parquet files significantly improved runtime for repeated queries, demonstrating the effectiveness of these techniques in large data environments.

## Future Work

Future improvements could include expanding the dataset to cover additional regions, exploring more complex machine learning models to predict home prices based on available features, and visualizing geospatial trends in home sales. Additionally, incorporating other data sources, such as economic indicators or population demographics, could enhance the analysis and provide a deeper understanding of factors influencing home prices.
