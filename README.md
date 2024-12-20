# Movie_Rating_Prediction
For predicting the "audience_rating," I experimented with multiple algorithms, including Random Forest Regressor, Gradient Boosting Regressor, CatBoost Regressor, and XGBRegressor. Among these, the XGBRegressor delivered the best results, demonstrating superior performance metrics. The XGBRegressor was particularly advantageous due to its ability to handle missing values, regularization techniques (L1 and L2), and its efficient use of computing resources. Furthermore, its robust handling of both small and large datasets and built-in support for parallel processing allowed for faster training and better optimization of model parameters.
Additionally, I utilized a Deep Neural Network for prediction; however, it did not yield the desired results due to the small dataset size, which limited its effectiveness.The final and optimal results produced by the XGBRegressor are as follows

Mean Absolute Error (MAE): 11.30
Mean Squared Error (MSE) : 200.63
R² Score                 : 0.5082

These metrics reflect a notable improvement and affirm the effectiveness of the XGBRegressor for this task.
