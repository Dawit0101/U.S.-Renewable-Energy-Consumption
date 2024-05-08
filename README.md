# U.S. Renewable Energy Consumption Data Analysis

This project analyzes monthly renewable energy consumption data in the United States from 1973 to 2024. The dataset provides detailed information on renewable energy consumption by source and sector, sourced from the U.S. Energy Information Administration (EIA).

## About the Dataset

The dataset contains the following columns:

- `Year`: The calendar year of the data point
- `Month`: The month number (1-12) of the data point
- `Sector`: The energy consumption sector (Commercial, Electric Power, Industrial, Residential, or Transportation)
- `Hydroelectric Power`, `Geothermal Energy`, `Solar Energy`, `Wind Energy`, `Wood Energy`, `Waste Energy`, and other columns: Renewable energy consumption by source in trillion BTUs
- `Total Renewable Energy`: Total renewable energy consumption (sum of all sources) in trillion BTUs

## Project Steps

1. **Data Loading and Preprocessing**: Load the dataset, handle missing values, and preprocess the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Explore the dataset to understand trends and patterns in renewable energy consumption over time and across sectors.
3. **Comparative Analysis**: Compare renewable energy consumption across different sectors and sources.
4. **Forecasting**: Use a forecasting method to predict future renewable energy consumption trends.
5. **Policy Impact Analysis**: Analyze the impact of renewable energy policies on consumption trends.
6. **Geospatial Analysis**: Visualize renewable energy consumption on a map to understand geographic patterns.
7. **Stakeholder Analysis**: Identify and analyze stakeholders affected by renewable energy policies.
8. **Visualization and Reporting**: Create visualizations and summary reports to communicate findings effectively.
9. **Interactive Dashboard**: Develop an interactive dashboard using Dash or other libraries to allow users to explore the data.
10. **Future Work and Recommendations**: Summarize future work and provide recommendations based on the analysis.

## Dependencies

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Dash (for interactive dashboard, if applicable)

## Usage

1. Clone the repository:

