## Air Quality Analysis Readme

#Introduction
This project focuses on analyzing air quality in Delhi using Python libraries such as Pandas for data manipulation, Plotly for data visualization, and requests for fetching data from a source. The dataset used for analysis is delhiaqi.csv, which contains information about various pollutants' concentrations over time.

#Prerequisites
Make sure you have the following libraries installed:
Pandas
Plotly
Requests

#Getting Started

Clone this repository.
Ensure you have the required dataset (delhiaqi.csv) in the project directory.

#Usage
Run the Python script analyze_air_quality.py.

This script performs the following tasks:
Calculates the Air Quality Index (AQI) for each pollutant and overall AQI for each row in the dataset.
Analyzes AQI distribution, pollutant distribution, correlation between pollutants, hourly average AQI trends, and average AQI by day of the week.
Visualizes the analysis using Plotly.
View the generated plots for insights into Delhi's air quality.

#Files
analyze_air_quality.py: Python script for analyzing air quality and generating visualizations.
delhiaqi.csv: Dataset containing air quality information for Delhi.
README.md: Instructions and information about the project.

#Methodology
Data Import: The dataset (delhiaqi.csv) is imported using Pandas.
Data Cleaning: Any missing or inconsistent data is handled to ensure accurate analysis.
AQI Calculation: Functions calculate_aqi and calculate_overall_aqi are used to compute AQI for each pollutant and overall AQI, respectively.
Analysis: Various aspects of air quality are analyzed, including AQI distribution, pollutant distribution, correlation between pollutants, and average AQI trends.
Visualization: Plotly is used for creating interactive visualizations to illustrate the analysis results effectively.

#Conclusion
The analysis provides valuable insights into Delhi's air quality, which can be utilized for public health management and environmental policies.

#Contributors
Riddhiman Mukhopadhyay

