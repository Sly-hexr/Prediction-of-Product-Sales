# Prediction-of-Product-Sales
![supermarket](https://github.com/Sly-hexr/Prediction-of-Product-Sales/assets/133910731/f4442f73-3253-43fa-8c3e-215141401783)
#### Nicholas Rowland
------------------------------------------------------------
# Purpose
## The goal of these series of models is to identify success markers in our various locations and to improve by helping them understand the products and outlets that have a significant impact on increasing sales. Helping our locations understand the importance of these factors will be crucial in increasing sales to stimulate future growth of the company overall.


# This dataset will provide a sales prediction for various supermarkets

https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing

# Data cleaning
To provide the most accurate data possible the data has been cleaned to remove all null/duplicated values for optimal performance

# Exploratory Data Visualization
Visualized data in the form of graphs and plots to demonstrate correlation the following plots were used:
- Bar plot
- Box Plot
- Scatter plot

![data1](https://github.com/Sly-hexr/Prediction-of-Product-Sales/assets/133910731/3f13ec36-c8d8-4ffa-a3e7-abed6b5a879d)
#### The plot above displays that the 3 most commonly sold items from our supermarkets are fruits/vegetables, household goods, and snack foods



![data2](https://github.com/Sly-hexr/Prediction-of-Product-Sales/assets/133910731/e0225117-33e9-44a1-8ef6-9f67b4d3664b)
#### The plot above shows us that tier 3 stores perform better than either tier 1 or tier 2 locations



![data3](https://github.com/Sly-hexr/Prediction-of-Product-Sales/assets/133910731/bd84f637-0c6f-4629-98dd-df97cff56902)
#### The plot above demonstrates a positive correlation between the sales of our quality branded products rather than our economically cost effective products


# Machine Learning Models Used:
- Linear Regression
- Random Forest Regression
- Tuned Random Forest Regression (Best Parameters used)

### Linear Regression Model
- Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 994.970
- MSE = 1,737,439.721
- RMSE = 1,318.120
- R^2 = 0.370

### Random Forest Model
- Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 891.347
- MSE = 1,517,274.032
- RMSE = 1,231.777
- R^2 = 0.450

### Tuned Random Forest Model
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 847.955
- MSE = 1,370,115.384
- RMSE = 1,170.519
- R^2 = 0.503

Among the regression models used, we would definitely implement the tuned random forest model. However, a regression model to make predictions for this dataset would be fairly unreliable. The R^2 score is especially important to us as it displays an accuracy value of only 50% after tuning. The RMSE score is also a little on the higher side for an error score related to our target.

# Final Recommendations
While the model was somewhat unreliable the data visualizations we do have display trends that may not say everything we need but definitely do tell a story. We would just need to find more correlating values and maybe some more data to further tune and return a more accurate model 

# Prediction of product sales revisited

