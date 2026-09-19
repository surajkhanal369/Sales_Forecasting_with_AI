# AI BASED SALES FORECASTING IN RETAIL BUSINESSESS
## Overview

The repository presents my Msc thesis projects where retailers have to make operating decisions before knowing future demand and that is where sales forecasting becomes an important component of retail planning. The thesis aim is to create and compare statistical, machine learning and deep learning models for retail sales forecasting and to what extent different factors influence forecasting sales. One of the problems that this research aims to solve is how to identify the most suitable forecasting method to best capture the temporal and nonlinear evolution of retail sales. Instead of taking for granted that the statistical models, machine learning or deep learning models are better, the study will compare the different approaches in the same forecasting conditions.

## Contents

The main notebook of the repository presents "AI_forecast_Sales_analysis_file.ipynb " which implements the entire forecasting sales analysis. The notebook presents data preprocessing processes and feature engineering methods, model development procedures, evaluation techniques and result visualization steps.

## Dataset

The Dunnhumby – The Complete Journey dataset was selected because it contains real-world retail transaction data collected over two years from approximately 2,500 households. The dataset provides detailed information about customer purchasing behaviour, product characteristics, transaction history, demographic information, and promotional activities. This makes it suitable for developing a retail sales forecasting model because sales are influenced by multiple factors beyond historical sales patterns.

The dataset contains a large number of transaction records, which provides sufficient data for training and evaluating machine learning models. The availability of customer, product, and promotional information allows the research to investigate the factors influencing sales performance and improve forecasting accuracy.

The main dataset used in this research will be transaction_data.csv, as it contains the target variable sales_value which is transaction-level information. Product.csv will be integrated to include product-related features such as brand, department, and product category. Household demographic information from hh_demographic.csv will be considered to capture customer purchasing behaviour when relevant. Campaign and coupon datasets will also be evaluated during the exploratory analysis because promotional activities may influence sales. The final selection of variables will be based on their relationship with sales_value and their contribution to the forecasting model

Target Variable: SALES_VALUE

The dataset that is used is 
[kaggle](https://www.kaggle.com/datasets/frtgnn/dunnhumby-the-complete-journey)  

## Methodology

The methodology employs a structured approach to data collection, data understanding, data preprocessing, exploratory data analysis (EDA), feature engineering, time-series preparation, model development, evaluation and comparison. Four forecasting approaches will be evaluated which are Auto ARIMA, Decision Tree Regression, Gradient Boosting/XGBoost and LSTM
