# Building-Energy-Benchmarking
Energy Consumption and Efficiency Analysis
### Project Overview
This project aims to analyze energy consumption, greenhouse gas (GHG) emissions, and energy efficiency across various property types. The analysis includes detecting outliers, performing correlation analysis, conducting hypothesis testing, and providing recommendations for improving energy efficiency and reducing emissions.

### Table of Contents
Project Overview

Data Description

Analysis Steps

Key Findings

Recommendations

Visualizations

Usage

Contributing

License

### Data Description
The dataset includes information on various properties, such as:

    Property Name

    Property Type

    Total GHG Emissions (Metric Tons CO2e)

    Energy Star Score

    Site Energy Use (GJ)

    Building Size (m²)

    And other relevant metrics

## Analysis Steps
### Data Cleaning:

Used Regex to identify and correct incorrectly formatted numeric values.

Removed or corrected values that did not conform to expected formats.

### Outlier Detection:

Applied the Interquartile Range (IQR) method to detect outliers in Total GHG Emissions.

Replaced outliers with the median value for the respective property type.

### Correlation Analysis:

Computed and visualized the correlation matrix between energy consumption, emissions, and building size.

Identified strong correlations and discussed their implications.

### Hypothesis Testing:

Conducted a t-test to compare the average Energy Star Score between two different property types (e.g., Offices vs. Residential buildings).

Interpreted the results and discussed statistical significance.

### Key Findings
Larger buildings tend to have higher GHG emissions.

Strong correlation between emissions and building size.

Higher energy consumption leads to higher emissions.

Significant property type variations in energy consumption.

### Recommendations
Implement Energy Efficiency Programs: Focus on upgrading older buildings with energy-efficient technologies.

Adopt Renewable Energy Sources: Encourage the use of solar panels and wind turbines.

Optimize operational practises: Implement best practices for energy management, such as scheduling and automation, to reduce energy consumption during non-peak hours.

Regular Energy Audits: Conduct audits to identify areas for improvement.

### Visualizations
Correlation Matrix Heatmap: Visualizes the correlation between energy consumption, emissions, and building size.

Bar Chart: Shows the top 10 buildings with the highest GHG emissions.

Heatmap: Displays energy usage intensity across different property types.
