# Yulu Hypothesis Testing Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Analysis Steps](#analysis-steps)
4. [File Structure](#file-structure)
5. [Requirements](#requirements)
6. [Installation](#installation)
7. [Running the Analysis](#running-the-analysis)
8. [Conclusion](#conclusion)

## 1. Project Overview

This project aims to analyze the factors influencing the demand for Yulu's shared electric cycles using statistical methods. The study explores how variables like working days, weather, seasons, and more affect total cycle rentals (dependent variable) and provides insights for business decisions.

## 2. Dataset

The dataset used for this analysis can be accessed from the following link: [Yulu Bike Sharing Dataset](insert_actual_link_here)

### 2.1 Dataset Columns

- datetime: Date and time of the observation
- season: Season of the year (1: Spring, 2: Summer, 3: Fall, 4: Winter)
- holiday: Whether the day is a holiday (1) or not (0)
- workingday: Whether it is a working day (1) or not (0)
- weather: Weather condition (1 to 4, with increasing severity)
- temp: Temperature in Celsius
- atemp: Feels-like temperature in Celsius
- humidity: Humidity percentage
- windspeed: Wind speed in km/h
- casual: Count of casual users
- registered: Count of registered users
- count: Total count of rentals (casual + registered)

## 3. Analysis Steps

### 3.1 Exploratory Data Analysis (EDA)
- Univariate Analysis
- Bivariate Analysis

### 3.2 Hypothesis Testing
- 2-Sample T-Test
- ANOVA Test
- Chi-Square Test

### 3.3 Test Assumptions
- Normality checks
- Equal variance verification

### 3.4 Insights and Inferences

## 4. File Structure

- `yulu_analysis.ipynb`: Jupyter notebook containing the full analysis
- `yulu_analysis.pdf`: PDF version of the notebook for easy reference
- `README.md`: This file for instructions and project details

## 5. Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy.stats

## 6. Installation

To install the required libraries, run the following command:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## 7. Running the Analysis

1. Clone the repository or download the dataset and notebook.
2. Open the Jupyter notebook `yulu_analysis.ipynb`.
3. Follow the steps outlined in the notebook to load the dataset, perform EDA, and run hypothesis tests.
4. Review the plots and test results for insights.

## 8. Conclusion

This analysis provides insights into the factors affecting Yulu's shared electric cycle demand. Findings from this study can help Yulu optimize fleet management, pricing strategies, and operations.
