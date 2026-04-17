# Baseline MAE Model - Used Cars Dataset

This project focuses on data cleaning and establishing a baseline model for predicting car selling prices.

## Overview

The dataset contained multiple issues such as missing values, inconsistent formatting, outliers, and duplicate records. These were handled through a structured data preprocessing pipeline.

## Data Cleaning Steps

- Removed null values in target and handled missing values in features
- Cleaned and converted `km_driven` and `mileage` to numeric format
- Fixed inconsistencies in categorical columns (`brand`, `fuel_type`, `seller_type`)
- Corrected typos and removed leading/trailing spaces
- Removed unrealistic values (e.g., invalid `seats`, extreme `selling_price`)
- Eliminated duplicate rows
- Applied one-hot encoding to categorical features

## Baseline Model

A simple baseline model was implemented by predicting the **mean selling price** for all records.

This helps establish a reference point to evaluate future machine learning models.

## Evaluation Metric

- Mean Absolute Error (MAE) was used to measure performance

## Result

The baseline MAE provides a benchmark that any predictive model should outperform.
