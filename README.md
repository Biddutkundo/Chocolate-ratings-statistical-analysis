# Chocolate Ratings: Statistical Analysis

## Project Overview

This project analyzes the Chocolate Ratings dataset to investigate the relationship between cocoa percentage, bean origin, and expert chocolate ratings. The project was completed for **AMOD 5240 – Statistical Aspects of Modelling at Trent University**.

The analysis uses **R programming** to perform data cleaning, exploratory data analysis (EDA), simple linear regression, and hypothesis testing.

## Research Questions

1. Does cocoa percentage predict the expert rating of chocolate bars?
2. Is the mean rating significantly different between chocolates containing at least 70% cocoa and those containing less than 70% cocoa?
3. Do chocolate ratings differ between chocolates made from cocoa beans originating in Africa and South America?

## Dataset

The Chocolate Ratings dataset was published by the TidyTuesday project on January 18, 2022, and originated from Flavors of Cacao.

The dataset contains information about chocolate manufacturers, cocoa percentage, bean origin, and expert ratings.

### Key Variables

- `rating`: Expert chocolate rating (response variable).
- `cocoa_percent`: Cocoa content percentage (predictor variable).
- `country_of_bean_origin`: Country where the cocoa beans were grown.
- `broad_origin`: Broader geographic region of bean origin.
- `review_date`: Year of the chocolate review.

## Tools and Methods

**Tools:** R, RStudio, tidyverse, ggplot2, and statistical modelling packages.

**Methods:**
- Data cleaning and preprocessing
- Exploratory data analysis and summary statistics
- Data visualization using histograms, scatter plots, and boxplots
- Simple linear regression
- Welch's two-sample t-tests
- Interpretation of p-values and confidence intervals

## Key Findings

- Cocoa percentage had a statistically significant but weak negative relationship with expert ratings.
- Cocoa percentage explained approximately 2.15% of the variation in chocolate ratings.
- There was no statistically significant difference in mean ratings between chocolates with at least 70% cocoa and those with less than 70% cocoa.
- No statistically significant difference in ratings was found between chocolates originating from Africa and South America.

## Project Limitations

Chocolate ratings are subjective, and the dataset may not represent the entire chocolate market. Other factors, such as flavor, texture, and production quality, may influence ratings but are not fully captured in this analysis.

## Learning Outcomes

This project provided practical experience in statistical analysis, data visualization, linear regression, hypothesis testing, and communicating data-driven findings using R.

## Authors

- Biddut Kundo
- Syed Rameez Hassan
- Shunyu Zhao

**Course:** AMOD 5240 – Statistical Aspects of Modelling  
**Institution:** Trent University

