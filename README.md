# -Boston-Housing-Data-Analysis

##-Overview
This repository contains an analysis of the Boston Housing dataset, a classic dataset used in regression analysis and predictive modeling. The dataset contains information collected by the U.S Census Service regarding housing in the Boston, Massachusetts area. It comprises 506 observations with 14 attributes, each representing aggregated data about various features for houses in different Boston neighborhoods.

#Tools Used:
The analysis utilizes Python and various libraries for data manipulation, visualization, and analysis, including:

<p align="Left">
  <img width="40" height="20" src="Boston-Housing-Data-Analysis/images.png">
</p>

<p align="Left">
  <img width="40" height="20" src="-Boston-Housing-Data-Analysis/download.png">
</p>
#Description
The Boston Housing dataset provides insights into the housing market and factors influencing housing prices. Key attributes include crime rate, zoning, proximity to business areas, environmental factors like nitric oxides concentration, average number of rooms, and socio-economic indicators such as the percentage of lower-status population.

Exploratory Data Analysis (EDA)
EDA is conducted to gain insights into the dataset:

Data Inspection: Checking data types, missing values, and initial exploration of the dataset.
Summary Statistics: Calculating mean, median, minimum, maximum, and quartiles for each attribute.
Data Visualization: Creating visualizations like histograms, scatter plots, and box plots to understand variable distributions and relationships.
Correlation Analysis: Identifying relationships between features and the target variable.
Outlier Detection: Identifying and addressing outliers.
Data Preprocessing: Scaling, normalizing, or encoding features as required for modeling.
Data Analysis Tasks
Average Rooms per Dwelling by MEDV Category: Calculating the average number of rooms per dwelling for each category of 'MEDV' (low, medium, high).
Percentage of Houses Bound to Charles River: Determining the percentage of houses that bound the Charles River.
NumPy Operations
Performing NumPy operations on the 'AGE' column:

Compute mean and standard deviation.
Normalize the array.
Conclusion
The EDA reveals important insights:

Price Distribution: Housing prices exhibit a right-skewed pattern.
Correlation Analysis: Features like number of rooms and percentage of lower status population show strong correlations with housing prices.
Outliers: Careful handling of outliers is necessary.
Geographical Trends: Exploring housing prices across different areas may reveal localized patterns.
Data Quality: Ensuring data reliability and accuracy is essential.
