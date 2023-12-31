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
- [American Community Survey Data](.//2015-2019_American_Community_Survey_Detailed_Census_Tract_Data.csv)
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
- [Random Forest MSE](./randomforestmse.ipynb)
- [ADA Boost Model Charts](./ADA%20Charts.ipynb)
- [CensusNMedian](./CensusMedian.ipynb)


## Visualizations

![Correlation Matrix](/Correlation%20Matrix.png)
![District Map](/District%20Map.png)
![KCMO](/KCMO.png)
![MSEDepths](/MSEDepths.png)
![PairPlot](/PairPlot.png)
![Power BI median income](/Power%20BI%20median%20income.png)
![Python for visuals](/Python%20for%20visuals.png)
![Race 2020 Power BI](/Race%202020%20Power%20BI.png)
![Relationships of Data](/Relationships%20of%20Data.png)
![Sample Power BI Dash](/Sample%20Power%20BI%20Dash.png)
![Treemap of age 2021 by dist](/Treemap%20of%20age%202021%20by%20dist.png)
![Variance of Native Populace 5 year period](/Variance%20of%20Native%20Populace%205%20year%20period.png)
![ada MSE](/ada%20MSE.png)

## Results
In the course of our analysis, we encountered a substantial volume of data. Upon examining the redistricting efforts within the City of Kansas, the findings suggest that the processes are functioning appropriately. However, it is important to acknowledge the potential for data limitations to influence these results. One significant factor is the varying levels of participation in the census. As not all individuals engage with the census, there could be a skewing effect on the data, which in turn might affect the perceived efficacy of the redistricting measures. It is, therefore, crucial to consider these limitations when interpreting the results.
