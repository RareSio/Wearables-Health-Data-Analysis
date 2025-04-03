# Wearables-Health-Data-Analysis
## Overview
This repository contains a Jupyter Notebook (.ipynb) developed as part of a Master's coursework project in Bioinformatics. The project analyzes data collected from Xiaomi Smart Band 7 devices, focusing on physiological differences between three subjects who were monitored over an extended period of time. The analysis involves preprocessing, statistical evaluation, and visualization of heart rate, sleep patterns, and activity data.

The notebook demonstrates proficiency in working with wearable device data and showcases the use of Python programming and its libraries for bioinformatics research.

## Title
Wearable Data Analysis Using Xiaomi Smart Band 7: A Study of Physiological Variability Across Subjects

## Key Highlights
- Subjects: Data was collected from three individuals over a long-term monitoring period.

- Focus Areas: Heart rate trends, sleep metrics (REM, deep sleep), and physical activity patterns.

- Programming Language: Python

- Libraries Used:

  - numpy – Numerical computations

  - pandas – Data manipulation and preprocessing

  - matplotlib – Data visualization

  - scipy.stats – Statistical analysis tools

## Repository Contents
Project_of_Wearables.ipynb: The Jupyter Notebook containing the full code for data loading, preprocessing, analysis, and visualizations.

## Features
- Data Preprocessing:

  - Conversion of timestamps to human-readable datetime format.

  - Filtering out erroneous heart rate values above physiological limits (>220 bpm).

  - Separation of data by device IDs to analyze each subject individually.

- Analysis Methods:

  - Descriptive statistics (mean, median, standard deviation).

  - Time-series plots for heart rate trends.

  - Histograms and box plots for variability analysis.

  - Q-Q plots to evaluate data distribution normality.
