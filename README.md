# Kansas City District Remapping Analysis

This repository contains the data, scripts, and Jupyter Notebooks used in the analysis of the socio-political and demographic impacts of district remapping within Kansas City, Missouri. The study examines how redistricting affects various demographic variables such as age, income, and racial composition.

## Abstract

The project investigates the dynamics of district mapping and its repercussions on the demographic landscape of Kansas City. Through comprehensive data analytics, we present findings on shifts in median age, population, income, and race distribution post-redistricting.

## Data Sources

- United States Census Bureau
  - BO2001: Race demographics
  - S0101: Age demographics
  - S1901: Income demographics
- City of Kansas City’s parcel viewer for geographic information

## Tools and Libraries

- **Data Analysis and Visualization**:
  - Microsoft Excel
  - Microsoft Power BI
  - Jupyter Labs
  - QGIS (for shapefile adjustments)

- **Python Libraries**:
  - Pandas
  - geopandas
  - Shapely
  - Seaborn
  - NumPy
  - Matplotlib
  - Sklearn (RandomForestRegressor, DecisionTreeRegressor, AdaBoostRegressor)
## Data Sets

Here are the datasets used for the analysis:

- [Census Data](./census_data.csv)
- [American Community Survey Data](./2015-2019_American_Community_Survey.xlsx)
- [District Data](./updated_districts_cleaned.csv)
- [Income Data](./b02000.xlsx)
- [Age Distribution Data](./s0101.xlsx)
- [Income Distribution Data](./s1901.xlsx)

## Jupyter Notebooks

The following Jupyter Notebooks contain the analysis and machine learning models:

- [Data Analysis Notebook](./CensusMedian.ipynb)
- [Random Forest Model Analysis](./RandomForest.ipynb)
- [Decision Tree Model Analysis](./DecisionTree.ipynb)
- [ADA Boost Model Analysis](./adafinal.ipynb)


## Visualizations

Visual representations created from the analysis:

- [Current District Map Visualization](./district map current.png)
- [District Map Visualization](./district map.png)
