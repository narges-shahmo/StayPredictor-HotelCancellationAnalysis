# StayPredictor: Hotel Cancellation Analysis

## Overview

StayPredictor delves into the pressing issue of booking cancellations at Star Hotels, a challenge that has become increasingly prevalent in the hospitality industry. With cancellations leading to significant revenue losses, especially those occurring at the last minute, this project seeks to leverage Machine Learning to predict the likelihood of booking cancellations, thereby enabling more effective and profitable cancellation and refund policies.

## Project Objectives

- To identify key factors contributing to booking cancellations at Star Hotels.
- To develop a predictive model capable of forecasting potential booking cancellations.
- To provide actionable insights and recommendations to mitigate the impact of cancellations on revenue.

## Data Insights

The analysis was conducted on a dataset comprising 56,926 records across 18 variables, including booking status, type of meal plan, room type reserved, and average price per room. Notable findings from the exploratory data analysis (EDA) include:

- A significant proportion of reservations are made for two adults, often without children.
- Bookings are predominantly for weeknights, with a lower frequency during weekends.
- The majority of bookings are made 0 to 100 days in advance of the arrival date.

## Exploratory Data Analysis Highlights

- Seasonal trends indicate a higher volume of bookings during July and August, with corresponding peaks in cancellations.
- Online market segments dominate bookings, contributing to 82% of total reservations.
- Special requests from guests tend to decrease the likelihood of cancellation.

## Model Development and Performance

The project employed logistic regression and decision tree models to predict booking cancellations. Key steps in model development included handling multicollinearity, creating dummy variables for categorical data, and employing techniques like pre-pruning in decision trees to enhance model performance. The logistic regression model, with a recall score threshold of 0.36, showed promising results, effectively identifying true positives and negatives while maintaining a balance between sensitivity and specificity.

## Business Insights and Recommendations

- Lead time, special requests, and the number of children are significant predictors of cancellations.
- Targeted strategies to reduce cancellations may include loyalty programs for repeat guests, promotional deals for new guests, and personalized offers for guests with special requests or children.
- Further analysis of seasonal booking and cancellation trends can provide insights for dynamic pricing strategies and offer optimization.

## Conclusion

StayPredictor offers valuable predictive insights into booking cancellations at Star Hotels, highlighting opportunities for policy refinement and customer engagement strategies to mitigate revenue losses. By understanding the underlying patterns and drivers of cancellations, Star Hotels can implement targeted measures to enhance guest satisfaction and loyalty, ultimately contributing to improved financial performance.

*Note: This project is part of the coursework from University of Austin's post graduate program.*