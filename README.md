# Calorie_Prediction
This project is about predicting the calories burned based on the following Features: Gender Age Height Weight Duration Heart_rate Body_temp

The data was obtained from the following site: https://www.kaggle.com/datasets/ruchikakumbhar/calories-burnt-prediction


## Data files, there are 3 notebooks:
1. ‘data_understanding’ in which the data is analysed and the understanding of the data is improved.
2. ‘data_preprocessing’ in this notebook the data is prepared so that the training and test data is available. (Not many steps were needed)
3. ‘ML_models_train_predict’ in this notebook the model was trained and tested as well as evaluated.


RandomForestRegressor was used as the regression model.

## Results:
- Mean Absolute Error (MAE): 1.81
- Mean Squared Error (MSE): 9.14
- Root Mean Squared Error (RMSE): 3.02
- R²-Score: 0.9970 (almost perfect fit)

Feature Importance:
- Feature "Duration" of training has the greatest influence on the prediction
- Heart rate & body temperature also play an important role