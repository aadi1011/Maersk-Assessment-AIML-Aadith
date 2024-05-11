# AP Moller Maersk DS-ML Coding Challenege

## Overview
This project aims to predict the sourcing costs of various product combinations using machine learning models. The dataset contains information about different attributes such as product type, manufacturer, area code, sourcing channel, product size, and more. The goal is to forecast the sourcing costs for June 2021 using data from July 2020 to May 2021.

## Dataset
- The dataset comprises rows representing the sourcing of one unit of a particular product combination.
- Each unique product combination is represented by attributes in Columns A to F.
- Training data spans from July 2020 to May 2021, and June 2021 is the test set.
- Multiple rows may have the same combination in the training dataset.
- The test set (June 2021) contains only a single value for each combination.

## Approach
1. **Exploratory Data Analysis (EDA)**: Understand the dataset's structure, distributions, and relationships between variables.
2. **Data Preprocessing**: Handle outliers and poor data quality, feature engineering, and data cleaning.
3. **Model Building and Evaluation**: Implement various machine learning algorithms such as linear regression, decision tree, and random forest. Evaluate their performance using metrics like MSE, RMSE, MAE, and R-squared score.
4. **Optimization**: Apply optimization techniques to enhance model performance, such as outlier removal and feature engineering.
5. **Model Selection**: Choose the best-performing model based on evaluation metrics and optimize it further if necessary.
6. **Forecasting**: Use the selected model to forecast the sourcing costs for June 2021.

## Conclusion
In this analysis, we developed predictive models to estimate sourcing costs based on product attributes and other factors. By employing machine learning algorithms and optimization techniques, we achieved significant improvements in predictive accuracy, particularly with the cleaned decision tree model. The final model demonstrated strong performance on the training data, indicating its suitability for predicting sourcing costs for the test dataset in June 2021.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Authors
- [Aadith Sukumar](https://github.com/aadi1011)
