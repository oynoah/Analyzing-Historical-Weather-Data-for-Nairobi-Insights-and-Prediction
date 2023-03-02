# Analyzing-Historical-Weather-Data-for-Nairobi-Insights-and-Prediction

This repository contains a Jupyter Notebook that analyzes historical weather data for Nairobi, Kenya. The dataset used in this analysis was obtained from [Visual Crossing](https://www.visualcrossing.com/weather/weather-data-services)
, and covers the period from January 1, 2013 to December 31, 2022.

The analysis focuses on trends in weather attributes, and uses a polynomial regression to model the relationship between solar radiation and other weather attributes.

# Analysis Overview
The analysis consists of the following steps:

1. **Attributes Selection:** Columns of main focus were selected fro the collected data for analysis.
2. **Data Cleaning:** Values representing observations of the selected attributes were converted to units that are of Kenyan standard and data type conversion was also done.
3. **Exploratoory Data Analysis:** The cleaned data is visualized using plots and statistical summaries to gain insights into the distribution and trends of the data.
4. **Polynomial Regression:** A polynomial regression was used to model the relationship between solar radiation and other weather attributes.
5. **Model Evaluation:** The performance of the polynomial regression model was evaluated using metrics such as mean squared error (MSE) and R-squared. 

# Results
The analysis shows that Nairobi has experienced both wetter and drier seasons in the past decade. The long rains months have constantly been March-May with cold June-August. The hot months are January-February as well as September and October. Other weather attributes have relatively remained constant within a certain range across the years. This shows that Nairobi's climate has been stable; except for the year 2017 and 2022, in which low rains were recorded. The polynomial regression model was able to show that their is connection between the weather attributes and the capacity of solar raduiation.

The model evaluation metrics show that the polynomial regression model has a low MSE and a high R-squared, indicating that it is a good fit for the data.

# Conclusion
In conclusion, this analysis provides insights into the historical(last ten years) patterns of weather attributes in Nairobi, Kenya, and demonstrates the use of a polynomial regression model to predict solar radiation values for the future. The results can be used by researchers and policymakers to better understand the dynamics of solar radiation in the region, and to plan for renewable energy projects that rely on solar power.
