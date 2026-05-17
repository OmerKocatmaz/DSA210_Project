# DSA210 Term Project
## Analyzing the Relationship Between Daily Habits and Productivity

This repository contains the code, dataset, visualizations, and reports for my DSA210 term project.

## Project Overview

The purpose of this project is to investigate how daily habits affect personal productivity.  
To explore this relationship, I collected and analyzed my own daily behavioral data over a 56-day period (March 10 – May 5, 2026).

The dataset includes variables such as:
- Sleep duration
- Sleep quality
- Morning mood
- Energy level
- Study hours
- Phone usage
- Stress level
- Weekend status
- Productivity score

The project combines exploratory data analysis, statistical hypothesis testing, and machine learning methods to identify the most influential factors related to productivity.

## Methods Used

### Exploratory Data Analysis (EDA)
- Scatter plots
- Correlation matrix
- Histograms
- Boxplots
- Time-series visualization

### Statistical Analysis
- Pearson correlation
- Spearman correlation
- Mann-Whitney U test

### Machine Learning Models
- Linear Regression
- Random Forest Regressor
- Logistic Regression
- Random Forest Classifier

## Key Findings

- Energy level showed the strongest statistically significant positive relationship with productivity.
- Phone usage had a significant negative relationship with productivity.
- Random Forest models identified phone usage as the most important predictive feature.
- Weekend productivity was slightly higher on average, but the difference was not statistically significant.

## Repository Structure

```text
project-root/
│
├── data/
│   └── data.csv
│
├── notebooks/
│   └── productivity_analysis.ipynb
│
├── figures/
│   └── plots_and_visualizations
│
├── docs/
│   ├── proposal.pdf
│   └── final_report.pdf
│
├── requirements.txt
└── README.md
