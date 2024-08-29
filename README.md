# Google-Play-Store-Data-Cleaning-and-Analysis

# Exploratory Data Analysis and Feature Engineering on Google Play Store Dataset

## Overview
This project involves the exploration and feature engineering of a dataset containing information on more than 10,000 apps available on the Google Play Store. The goal is to analyze the data to identify trends and patterns, such as the most popular app categories, apps with the largest number of installs, and those with the largest sizes.

## Dataset
The dataset used in this project includes 13 columns and 10,841 rows, covering a variety of app features such as:
- **App Name**
- **Category**
- **Rating**
- **Reviews**
- **Size**
- **Installs**
- **Price**
- **Content Rating**
- **Genres**
- **Last Updated**
- **Current Version**
- **Android Version**

The dataset is sourced from [Google Play Store Dataset](https://raw.githubusercontent.com/krishnaik06/playstore-Dataset/main/googleplaystore.csv).

## Steps Performed
1. **Data Cleaning**: 
   - Handled missing values and corrected data types.
   - Addressed inconsistencies in the dataset, such as anomalous entries in the "Rating" and "Size" columns.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed distribution of app ratings, sizes, and install counts.
   - Identified the most popular categories and apps by install count.
   - Explored correlations between various features.

3. **Feature Engineering**:
   - Created new features to better understand the relationship between app characteristics.
   - Transformed categorical data into numerical format for more effective analysis.

## Tools & Libraries Used
- **Python**: The programming language used for data analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: The environment used for developing and documenting the analysis.

