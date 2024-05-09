# BYTEUPRISE_ML_04
# House Price Prediction with Linear Regression

This project implements a linear regression model to forecast house prices based on key features including  number of bedrooms, and number of bathrooms. Leveraging predictive analytics techniques, this tool provides accurate estimations that offer valuable insights into real estate trends.

# **Dataset**
The dataset used in this project is sourced from the California housing dataset, which includes geographical and socioeconomic information about houses in various locations. The dataset is provided in a CSV format (housing.csv).

# **Features**
* longitude: Longitude coordinate of the house location.
* latitude: Latitude coordinate of the house location.
* housing_median_age: Median age of houses in the area.
* total_rooms: Total number of rooms in the house.
* total_bedrooms: Total number of bedrooms in the house.
* population: Total population in the area.
* households: Total number of households in the area.
* median_income: Median income of households in the area.
* ocean_proximity: Proximity of the house to the ocean (categorical variable).**

# **Project Structure**
The project is organized as follows:
* housing.csv: The raw dataset file.
* cleaned_data.csv: The preprocessed dataset after handling missing values.

# **Requirements**
* Python 3.x
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

# **Model Training and Evaluation**
The linear regression model is trained using the median_income, housing_median_age, total_rooms, total_bedrooms, and population features to predict median_house_value. Model evaluation metrics include:
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
