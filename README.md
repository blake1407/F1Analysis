This project aims to analyze F1 drivers' performance across different circuits during the 2021-2024 seasons. Through exploratory data analysis and statistical techniques, we seek to answer two key questions:
1. Does track qualities influence lap time across drivers?
2. What are some circuits that each driver performs best in?

An in-depth overview of the data analysis pipeline and results is available [here](https://blaketrn.notion.site/A-Simple-F1-Drivers-Performance-Analysis-1c1b8fab88a780e9bed4e9c02eadbbe6).

## 📋 Overview
The workflow consists of several integrated components:
1. **Data Collection** - FastF1
   - [FastF1](https://github.com/theOehrly/Fast-F1) is an open-source resource providing: lap timing data, car telemetry and position, tire data, weather data.
3. **Data Preprocessing** - Removing outliers
4. **Statistical Analysis** - Simple statistical techniques (mean, std, var) and mixed-effects modeling
5. **Developing Visualizations** - Scatter plots and box plots

## 📋 Driver Selection Criteria
To ensure accurate comparisons, the project focuses on a roster of recent drivers who have:
- Remained with the same team for the past 3-4 years
- Consistent performance across multiple seasons

## 📋 Repository Structure
- ```fastf1.ipynb```: Comprehensive Jupyter Notebook containing all code and analysis
- ```Data.csv``` and ```New_data.csv```: Data retrieved using FastF1 API
- ```Lap Performance Across*.png```: Visualization for across drivers comparisons
- ```LapTimePerKm*.csv```: Statistical analysis summaries

## 📋 Getting Started
1. Clone the repository
2. Install required dependencies: Copy ```pip install fastf1 pandas matplotlib seaborn plotly statsmodels```
3. Open ```fastf1.ipynb```
4. Run the notebook to reproduce the analysis and visualizations


