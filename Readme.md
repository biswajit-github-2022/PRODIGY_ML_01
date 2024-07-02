# Purpose

In this task i have predicted prices of houses using Regresion models. 
Used Models are 
models = {
        'Linear Regression': LinearRegression(),
        'Random Forest': RandomForestRegressor(),
        'Gradient Boosting': GradientBoostingRegressor(),
        'XGBoost Regressor': XGBRegressor(),
        'Ridge Regression' : Ridge(),
        'Lasso Regression' : Lasso(),
        'ElasticNet Regression' : ElasticNet(),
        'Desicion Tree Regressor' : DecisionTreeRegressor(),
        'SVM Regressor' : SVR(),
    }

in this data Gradient boost regressor works better so i tried to fine tune it and predicted the test.csv data . Final result is submission.csv