In this project, I used the RandomForestRegressor model to predict the price of rental listings. The dataset contains features like neighborhood, room type, availability, and number of reviews, which were preprocessed through handling missing values and encoding categorical variables (e.g., room type and neighborhood).

I split the dataset into training and testing sets, trained the RandomForest model, and evaluated its performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The model achieved an MAE of ~62.76 and RMSE of ~197.06, which indicates how far the predicted prices are from the actual values.

I also built a function to predict the price of a new listing by ensuring the input features align with the ones used in the trained model. This allows for real-time predictions of rental prices based on input characteristics like location, room type, and availability.
