# Childbed Fever and the Impact of Handwashing

## Overview

This repository contains a data analysis project that investigates the impact of handwashing on reducing the death rates due to childbed fever. The analysis is based on historical data from Dr. Ignaz Semmelweis, who hypothesized that handwashing could prevent the spread of infections in maternity wards.

## Dataset

- The Data Source:
The key columns in the dataset include:
- `date`: The date of the record.
- `births`: The number of births in the clinic.
- `deaths`: The number of deaths in the clinic.
- `clinic`: The name of tgithe clinic.

## Methodology

The analysis includes the following steps:
1. Data Cleaning: Handling missing values and converting data types.
2. Data Visualization: Using histograms, KDE plots, and line charts to visualize the data.
3. Statistical Analysis: Performing t-tests to compare death rates before and after the introduction of handwashing.
4. Time Series Analysis: Highlighting different periods in the data and calculating rolling averages.

## Analysis

### Histograms and KDE Plots

- **Histograms**: Visualized the distribution of death rates before and after handwashing.
- **KDE Plots**: Used kernel density estimates to smooth out the distributions and highlight differences.

### Time Series Analysis

- **Rolling Averages**: Calculated 6-month rolling averages of death rates before handwashing was made mandatory.
- **Trend Analysis**: Highlighted the changes in death rates over time with handwashing.

### Statistical Tests

- **t-test**: Conducted a t-test to determine the statistical significance of the difference in death rates before and after handwashing.

## Results

The analysis shows a significant reduction in death rates after the introduction of handwashing:
- The average death rate before handwashing was ```9.92%```.
- The average death rate after handwashing was ```3.88%```.
- The t-test results indicated a p-value of ```0.0000002985```, demonstrating a highly significant difference.

## Conclusion

The analysis provides strong evidence supporting Dr. Semmelweis's hypothesis that handwashing significantly reduces the death rates due to childbed fever. This finding underscores the importance of hygiene practices in medical settings.

## Resources

* Dr. Semmelweis's Original Data
* Matplotlib Documentation
* Seaborn Documentation
* Scipy Stats Documentation

$$ \text{Special Credits: } @\text{Dr. Angela Yu} $$
