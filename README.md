# Poverty-Metrics-Analysis-in-DRC
This project analyzes global poverty metrics using R. The focus is on understanding key indicators such as the Multidimensional Poverty Index (MPI), headcount ratio, intensity of deprivation, and other metrics across regions and over time using data visualization, summary statistics, and exploratory data analysis techniques.

# Project Overview
This project aims to:
1. Clean and preprocess poverty data for analysis.
2. Provide insights into poverty trends and regional disparities.
3. Explore relationships between key poverty indicators.
4. Identify regions with severe poverty for targeted interventions.

# Features
Data Cleaning: Handles inconsistencies and prepares the data for analysis.
Exploratory Data Analysis (EDA):
Distribution analysis of MPI.
Trends over time for key indicators.
Regional comparisons of poverty metrics.
Visualization: Includes histograms, line plots, bar charts, and box plots.
Correlation Analysis: Examines relationships between poverty metrics.
Interactive Dashboard: (Optional) Shiny-based app for dynamic exploration of indicators.

# Installation
To replicate this analysis, follow these steps:

Clone this repository:
git clone https://github.com/YourUsername/Poverty-Metrics-Analysis.git
cd Poverty-Metrics-Analysis

# Install the required R packages:
install.packages(c("ggplot2", "dplyr", "corrplot", "shiny"))
Open the Poverty_Metrics_Analysis.Rmd file in RStudio.
Run the RMarkdown file to generate the HTML report.

# Data
The dataset used in this project contains poverty-related metrics across different regions and periods. The indicators analyzed include:
MPI (Multidimensional Poverty Index): Measures the intensity of poverty.
Headcount Ratio: Proportion of the population living in poverty.
Intensity of Deprivation: Average deprivation experienced by the poor.
Vulnerable to Poverty: Percentage of the population at risk of falling into poverty.
In Severe Poverty: Percentage of the population experiencing severe poverty.

# Visualizations
1. Distribution of MPI
Histogram showcasing the frequency of MPI values across regions.
2. Trends Over Time
Line plots to illustrate changes in MPI and headcount ratio over the years.
3. Regional Comparisons
Bar plots and box plots comparing poverty metrics across regions.
4. Correlation Matrix
A heatmap to explore relationships between various indicators.
Usage
You can run individual analyses or generate the full report using RMarkdown. Additionally, the optional Shiny app allows for dynamic interaction with the data:

# Launch the app:
shiny::runApp("shiny_dashboard.R")
Select an indicator to view trends and comparisons.

# Directory Structure

Poverty-Metrics-Analysis/
│
├── data/
│   └── hdx_hapi_poverty_rate_global.csv   # Dataset
├── scripts/
│   ├── data_cleaning.R                    # Data cleaning script
│   ├── eda_visualizations.R               # EDA and visualizations
│   └── shiny_dashboard.R                  # Shiny app script
├── Poverty_Metrics_Analysis.Rmd           # Main analysis file
├── README.md                              # Project documentation

# Contributions
Contributions are welcome! If you have ideas to improve this analysis or add new features, please fork the repository and submit a pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Author
Elvira Khwatenge
