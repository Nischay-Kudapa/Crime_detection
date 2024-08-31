# Crime_detection
The Crime Detector Model predicts the time (hour, minute) and location (x, y coordinates) of crimes using historical data, trained with a Random Forest Regressor and evaluated through Mean Absolute Error (MAE).
Data Preprocessing: The model cleans and preprocesses the dataset, converting timestamps into separate features (year, month, day, hour, minute) and extracting geographical coordinates (x, y) from location data.

Feature Engineering: Numerical features are standardized, and categorical features are one-hot encoded to prepare them for training.

Model Training: The model utilizes a Random Forest Regressor to predict the hour, minute, and exact coordinates (x, y) of crime occurrences. Separate models are trained for each of these predictions.

Evaluation: The model's performance is evaluated using Mean Absolute Error (MAE) and Mean Squared Error (MSE), providing insights into its accuracy.

Prediction: After training, the model can predict the time and location of a crime for a specific entry from the dataset, which can be compared to actual values to assess its effectiveness.

The model is scalable, allowing for processing large datasets and leveraging parallel processing to optimize training time.
