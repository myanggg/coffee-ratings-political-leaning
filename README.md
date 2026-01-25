# Coffee Shop Ratings vs Political Leaning

## Project Overview
This project analyzes whether coffee shops located in Republican-leaning ("Red") cities receive higher Yelp ratings than those in Democratic-leaning ("Blue") cities.

Using Yelp coffee shop ratings combined with city-level political and socioeconomic data, the project applies data wrangling and regression analysis to explore whether political context is associated with perceived service quality.

## Research Question
Do coffee shops located in Republican cities receive higher average ratings than those in Democratic cities?

## Data & Variables
- Yelp coffee shop ratings
- City political leaning (Democratic vs Republican vote share)
- Median household income
- Education level
- Median rent
- Population density

## Methodology
- Data loading and cleaning using Python (pandas)
- Data wrangling and feature integration across multiple datasets
- Multiple linear regression analysis conducted in R
- Hypothesis testing and interpretation of regression results

## Key Findings
- Coffee shops in Democratic-leaning cities are rated approximately 0.13 stars higher on average
- Higher income and population density are associated with slightly lower ratings
- Median rent shows a weak positive association with ratings
- Overall model explanatory power is low (R² ≈ 0.008)

## Repository Structure
- `notebooks/`: Data cleaning and exploratory analysis notebooks
- `data/`: Final cleaned dataset used for regression analysis
- `presentation/`: Final project presentation slides

## Tools Used
- Python (pandas, Jupyter Notebook)
- RStudio (regression analysis)
