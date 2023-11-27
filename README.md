# Kansas City District Remapping Analysis

This repository contains the data, scripts, and Jupyter Notebooks used in the analysis of the socio-political and demographic impacts of district remapping within Kansas City, Missouri. The study examines how redistricting affects various demographic variables such as age, income, and racial composition. 
Our overleaf report is here https://www.overleaf.com/read/yqpbpthggqxz#bdd445 

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
![Correlation Matrix](/Correlation_Matrix.png)
![District Map](/District_Map.png)
![KCMO](/KCMO.png)
![MSEDepths](/MSEDepths.png)
![Median Income over time by dis](/Median_Income_over_time_by_dis.png)
![Median income over time 20-21](/Median_income_over_time_20-21.png)
![New district 1](/New_district_1.png)
![PairPlot](/PairPlot.png)
![Power BI income](/Power_BI_income.png)
![Power BI median income](/Power_BI_median_income.png)
![Python for visuals](/Python_for_visuals.png)
![Race 2020 Power BI](/Race_2020_Power_BI.png)
![Relationships of Data](/Relationships_of_Data.png)
![Sample Power BI Dash](/Sample_Power_BI_Dash.png)
![Treemap of age 2021 by dist](/Treemap_of_age_2021_by_dist.png)
![Variance of Native Populace 5 year period](/Variance_of_Native_Populace_5_year_period.png)
![ada MSE](/ada_MSE.png)

## Results
In the course of our analysis, we encountered a substantial volume of data. Upon examining the redistricting efforts within the City of Kansas, the findings suggest that the processes are functioning appropriately. However, it is important to acknowledge the potential for data limitations to influence these results. One significant factor is the varying levels of participation in the census. As not all individuals engage with the census, there could be a skewing effect on the data, which in turn might affect the perceived efficacy of the redistricting measures. It is, therefore, crucial to consider these limitations when interpreting the results.
