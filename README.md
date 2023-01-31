# Rusty-Bargain

## Skills Demonstrated
    Pandas
    Numpy
    Plotly Express
    EDA
    Missing Values
    Encoding Categorical Features
    StandardScaler
    Cross Validation
    Regressions
    Imputation
    Pipeline
    Light GBM
    CatBoost
    XGBoost
    Hyperparameter Tuning

## Purpose
Rusty Bargain is developing an app to attract new customers, and they need to be able to quickly find out the market value of a car. We are given access to historical data: technical specifications, trim, and prices. Rusty Bargain wants a model that will predict the value of the car, while also considering the quality and speed of the prediction, and also the time required for training. 


## Conclusions
The boosting models contain a good balance between speed and model prediction quality. The RMSE scores of the boosting models were better than those of the regression models. Prediction times for either set of models is negligible. Overall, we suggest Rusty Bargain to implement a boosting machine learning model that will predict the market value of a car. From our data, we suggest that they start with a light gbm model, and tune the hyperparameters to achieve a low RMSE. The light gbm model is relatively fast at training, and the predictions are fast. Most importantly, the model prediction quality is the best of the options we've displayed. Another benefit of the light gbm model is its ability to natively handle missing values. This can benefit UX on the app, as users would not have to make up data just to run the model. 