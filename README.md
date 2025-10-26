# Car-Sharing-Demand-Prediction
The Car Sharing Demand Prediction project focuses on building a machine learning model to forecast the number of car rentals in a city over time. This predictive model helps car rental services optimize their operations by anticipating user demand based on various time-related and environmental factors.

Methodology
Data Preprocessing:
•	Handled missing values, converted categorical variables and normalized where necessary.
•	Verified data consistency and checked for correlations.
Exploratory Data Analysis (EDA):
•	Visualized distributions and relationships between rental counts and features.
•	Found strong influence from temperature, hour, and working day.
Model Building and Evaluation:
•	Trained multiple regression models: Linear Regression, Ridge, Lasso, Random Forest, and Gradient Boosting.
•	Evaluated using RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R² Score.

Results
Model	RMSE	MAE	R² Score
Linear Regression	440.68	330.53	0.534
Ridge Regression	440.68	330.52	0.534
Lasso Regression	440.68	330.52	0.534
Random Forest	172.78	97.54	0.928
Gradient Boosting	213.50	138.15	0.891

Insights
•	Hour of the day and temperature are the strongest predictors of car rental demand.
•	Clear or mildly warm weather increases rental activity, while extreme weather lowers it.
•	Random Forest and Gradient Boosting outperform linear models significantly, highlighting nonlinearity in the dataset.
•	These models can be used for demand forecasting, helping car-sharing services allocate fleets efficiently and improve operational planning.


