# COVID-19 Analysis in R

This repository contains an analysis of COVID-19 data using R programming language. Analysis of covid-19 for countries and determining it effect on the economy and life span of victims.

## Data

The data used for the analysis is contained in the `covid-data.csv` file. The file contains daily data on the number of COVID-19 cases and deaths in various countries and regions of the world. The data covers the period from January 2021 to the most recent available data.

## Analysis

The analysis is contained in the `covid_analysis.R` script. The script contains the following steps:

1. Loading the data into R.
2. Cleaning the data by removing missing values and selecting the columns of interest.
3. Analyzing the trends in the number of cases and rate of new cases.
4. Creating visualizations to represent the trends and patterns in the data. Graphic display of the impact of Covid-19 on the Country's GDP, Reproduction Rate, Life Expectancy and Human Development Index.

## How to Run the Analysis

To run the analysis, follow these steps:

1. Clone this repository to your local machine.
2. Open R and set the working directory to the cloned repository.
3. Install the necessary packages by running the following command in R: `install.packages(c("tidyverse", "ggplot2"))`
4. Run the `covid_analysis.R` script in R.

## Results

The results of the analysis are presented in the `results` folder. The folder contains the following files:

1. `global_cases.png`: A plot showing the trend in the number of COVID-19 cases globally.
2. `global_deaths.png`: A plot showing the trend in the number of COVID-19 deaths globally.
3. `country_cases.png`: A plot showing the trend in the number of COVID-19 cases in a specific country.
4. `country_deaths.png`: A plot showing the trend in the number of COVID-19 deaths in a specific country.

## Conclusion

This analysis provides insights into the trends and patterns in the spread of COVID-19 globally and in specific countries. The analysis can be useful for policymakers, healthcare professionals, and researchers in understanding the impact of the pandemic and developing strategies to mitigate its effects.
