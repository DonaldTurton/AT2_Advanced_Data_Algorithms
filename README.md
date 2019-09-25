# AT2 Advanced Data Algorithms
Electricity Price Prediction

The topic of investigation for this Practical Machine Learning Project concerns Australian electricity prices per megawatt. It is the goal of this project to discover those variables that are the most significant predictors of the price of electricity, build two machine learning models sophisticated enough to predict electricity price 30min into the future, and select the most accurate model based on the root mean square error measurement metric. The two machine learning models selected for the project include a Random Forest Regressor and an XGBoost Regressor, given that this is not a classification task. There have been three different model iterations produced for each of the two regressors selected (six models in total); the first model has no hyperparameter tuning (only the amount of trees has been defined), the second employs random search hyperparameter tuning, and the third model is a model with cross-fold validation hyperparameter tuning. As a result of modelling the data with two different regressors and multiple iterations of each regressor, the variable importance will be different. So, this project report will present graphs which display how variable importance changes between each regressor and each regressors iteration. Each model iteration has been compared based on the root mean square error (RMSE) and the final regressor iteration selected for deployment will be chosen based on the lowed RMSE score.

# Repo Content
The files under this repo can used to replicate the models where. A dictionary of the content on each file below the logical process order. 

1. adaa_data.csv: Original data set for the energy price and meteorological information merge and provided by one of the members of the team. 

2. EDA_EnergyData.ipynb: Exploratory Data Analysis and some feature engineering for lagged prices and moving averages.

3.  Clean_Data:  Extracted from EDA_EnergyData and used for the models.

4. AT2_GetData.ipynb: Random Forest models. Baseline, Random Grid and Grid Search

5. XGB_Model.ipynb: XGB models.  Baseline, Random Grid and Grid Search

6. Report: Methodology and Analysis of results 
