# Prediction-model

Here's a summary of what the code does:

Data Cleaning and Transformation:
  1. The code loads a dataset containing Mars weather data.
  2. It renames some columns to have more descriptive names.
  3. Columns related to wind speed, humidity, UV radiation, and weather are dropped.
  4. Various string replacements are performed to clean up the data.
  5. A new column 'day_duration' is created by calculating the time difference between sunrise and sunset.

Data Analysis and Visualization:
   1. The code calculates the mean ground temperature and mean air temperature.
   2. It extracts the 'solar_long' from the 'mars_date_time' column.
   3. The 'season' column is derived from the 'solar_long' based on specific conditions.
   4. The 'season' column is converted to a categorical data type with a specified order.
   5. The data is written in a CSV file.
   6. Several plots are created to visualize different aspects of the Mars weather data, such as daylight variation, atmospheric pressure, ground temperature, air temperature, and their correlations.

Machine Learning:

  1. The code calculates the mean squared error (MSE) and mean absolute error (MAE) to evaluate the performance of temperature predictions.
  2. The code also includes a basic K-nearest neighbors classifier to predict the season based on ground temperature and air temperature.
  3. It's important to note that the code is designed to work with a specific dataset structure, and the exact dataset used here is "mars_weather_clean.csv," which may have been created earlier in the code. If you intend to run this code, make sure you have the correct dataset or adjust the code accordingly based on your data.
