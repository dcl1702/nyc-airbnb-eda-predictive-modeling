# NYC Airbnb Data Analysis and Predictive Modeling

## Overview

This project analyzes the 2019 New York City Airbnb dataset to explore pricing patterns, location-based trends, room type differences, and host behavior. The analysis combines exploratory data analysis, statistical testing, and machine learning models to better understand what factors are associated with Airbnb listing prices.

The project focuses on variables such as price, room type, neighborhood group, availability, number of reviews, reviews per month, and host listing count.

## Objective

The goal of this project was to identify key factors that influence Airbnb listing prices in New York City and evaluate whether listings can be meaningfully grouped or predicted based on available features.

## Dataset

The dataset used in this project is the New York City Airbnb Open Data 2019 dataset.

Original dataset source:

[New York City Airbnb Open Data on Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

The dataset is based on publicly available Inside Airbnb data and includes over 48,000 Airbnb listings in New York City.

## Project Files

- `nyc_airbnb_analysis.ipynb`: Main analysis notebook
- `nyc_airbnb_final_report.docx`: Written final project report
- `README.md`: Project summary and documentation
- `requirements.txt`: Python package requirements


## Methods Used

- Data cleaning and missing value review
- Log transformation for skewed variables
- Univariate analysis
- Bivariate analysis
- Pearson and Spearman correlation analysis
- One-way ANOVA
- Welch’s ANOVA
- Linear regression
- Decision tree classification
- K-means clustering
- Random Forest regression

## Key Findings

- Airbnb prices in New York City are strongly right-skewed, with most listings priced under $250 but some extreme high-price outliers.
- Room type is one of the strongest factors associated with price.
- Entire homes and apartments tend to have higher prices than private rooms and shared rooms.
- Manhattan and Brooklyn dominate listing volume, with Manhattan generally showing higher prices.
- Correlations between numeric variables and price were mostly weak.
- ANOVA and Welch’s ANOVA showed statistically significant price differences across room types.
- K-means clustering identified different listing groups based on price, availability, and review activity.
- Random Forest regression slightly improved prediction performance compared to linear regression, but the most important features remained room type and neighborhood group.

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scipy
- pingouin
- scikit-learn

## Key Skills Demonstrated

- Exploratory data analysis
- Data preprocessing
- Handling skewed distributions
- Feature transformation
- Statistical hypothesis testing
- Regression modeling
- Classification modeling
- Clustering
- Model evaluation

## Future Improvements

- Add geospatial visualizations using latitude and longitude
- Explore seasonal pricing effects
- Test additional regression and classification models
