# Restaurant-Rating-and-Review

## Introduction
Online reviews have emerged as a vital source of information for consumers and businesses alike. This project leverages datasets provided by Yelp, a prominent review and recommendation platform, to analyze the relationship between reviews, business features, and operational status. By examining millions of reviews and business attributes, the project aims to understand and predict factors influencing business popularity, quality, and operational status, particularly in the context of the COVID-19 pandemic.

## Data Preprocessing
The project utilizes comprehensive datasets on businesses, reviews, and users obtained from Yelp. Data preprocessing involves handling missing values, exploring rating distributions, and extracting meaningful features from the datasets. Key steps include identifying common business categories, extracting features related to restaurants and food establishments, and performing sentiment analysis on review texts using the Vader algorithm.

## Inference Questions
The project explores relationships between restaurant features and operational status (open or closed) using hypothesis testing. By selecting significant features and conducting Mann-Whitney U tests, the analysis aims to identify predictors of restaurant closure and popularity. Visualizations and statistical tests provide insights into the importance of various features in predicting restaurant status.

## Prediction Questions
Predictive modeling is employed to forecast restaurant ratings and closure likelihood. Features such as location, demographic data, review counts, and sentiment analysis results are utilized to train neural network and regression models. The project evaluates model performance and assesses the effectiveness of different features in predicting restaurant outcomes.

## Classification Questions
Classification tasks focus on predicting restaurant closure using features derived from reviews, business attributes, and user interactions. K-means clustering is employed to group restaurants based on common characteristics, followed by training neural network and logistic regression classifiers. The project evaluates classification accuracy and explores feature importance in predicting closure.

## Summary and Conclusions
The project highlights the impact of various factors on restaurant ratings, operational status, and closure likelihood. Insights from hypothesis testing, predictive modeling, and classification tasks provide valuable information for both consumers and business owners. Limitations and future directions for improving model performance are also discussed, including addressing dataset imbalances and incorporating restaurant type differentiation.
