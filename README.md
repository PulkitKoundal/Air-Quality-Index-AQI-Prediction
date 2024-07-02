# Air-Quality-Index-AQI-Prediction
*Air Quality Index (AQI) Prediction Using Logistic Regression*

- *Data Processing and Sub-Index Calculation*: Cleaned and prepared air quality data by handling missing values and converting relevant columns to integer type. Calculated sub-indices for various pollutants including PM10, PM2.5, SO2, NOx, NH3, CO, and O3 based on established health guidelines.
  
- *Feature Engineering*: Created a comprehensive AQI metric by combining sub-indices of the pollutants and classified the AQI into predefined buckets (Good, Satisfactory, Moderate, Poor, Very Poor, Severe) for easier interpretability.

- *Model Development*: Utilized Logistic Regression to predict the AQI bucket from the AQI value. Split the dataset into training and testing sets with an 80-20 ratio to evaluate the model's performance.

- *Model Training and Evaluation*: Trained the logistic regression model and achieved a high accuracy score in predicting the AQI bucket. Evaluated the model performance using accuracy metrics.

- *Deployment*: Implemented an interactive component to predict AQI bucket based on user input AQI value, providing real-time classification.

