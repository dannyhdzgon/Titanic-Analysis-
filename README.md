# Titanic Survival Data Analysis

## Project Overview

This project analyzes the Titanic passenger dataset using Python to explore how passenger characteristics influenced survival rates.

The objective was to clean and prepare the dataset, identify patterns in passenger survival, and visualize relationships between survival outcomes and demographic characteristics.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Exploratory Data Analysis (EDA)
- Data Cleaning & Visualization

## Dataset

The analysis uses the Titanic passenger dataset, which includes information such as:

- Passenger survival status
- Age and sex
- Passenger class
- Ticket fare
- Port of embarkation

## Data Cleaning & Preprocessing

The following techniques were applied:

- Identified missing values across dataset columns.
- Filled missing age values using the median.
- Replaced missing embarkation values using the most frequent category.
- Checked for duplicate records.
- Rounded ticket fares to two decimal places.
- Identified fare outliers using the Interquartile Range (IQR) method.
- Created age groups to support demographic analysis.
- Removed unnecessary columns for the final analysis.

## Exploratory Data Analysis

Analyzed survival rates based on:

1. **Sex:** Compared survival rates between male and female passengers.
2. **Passenger Class:** Examined survival differences among first-, second-, and third-class passengers.
3. **Age Groups:** Categorized passengers into age ranges to explore survival patterns.
4. **Sex and Passenger Class:** Investigated how multiple passenger characteristics related to survival outcomes.

## Data Visualizations

Created three bar charts using Matplotlib:

- Titanic Survival Rate by Sex
- Titanic Survival Rate by Passenger Class
- Titanic Survival Rate by Sex and Passenger Class

These visualizations help communicate differences in survival rates across passenger groups.

## Key Takeaways

- Practiced cleaning and preparing a real-world dataset for analysis.
- Applied Pandas operations to calculate and compare survival rates.
- Used the IQR method to identify potential outliers.
- Developed visualizations to communicate findings.
- Strengthened skills in exploratory data analysis and interpreting categorical data.

## Project Files

- **Google Colab Notebook:** Python code, preprocessing steps, analysis, and visualizations.
- **Titanic Dataset:** Source data used for the analysis, if included in the repository.
