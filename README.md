# Supermarket-Sales-Prediction-Web-App

Keeping track of individual item sales data in order to forecast future client demand, adjust inventory management and the popularity of that given product in a region to adjust shipping quotas has become a very important aspect of automating demand for big supermarkets, where the amount of iteams and goods processed are very high. 
The sales and other associated data for this purpose are collected from various sources and stored in data warehouses across the country to optimize for analytics purposes.
By carefully mining and processing this data, interesting visualization, various anomalies and many interesting patterns can be found.
This data is finally used to optimize profit and loss for the respective retailer.

# Approach

  Data Exploration :  Read the dataset using pandas and numpy to find null values, categorical and numerical columns from the given dataset
  
  Data Visualization :  Performed Exploratory Data Analysis, to gain insights and learn the correlation of the columns with the output variable.
  
  Feature Engineering :  Removed missing values and normalize the dataset to feed the values to the ML model.
  
  Model Building :   Build simple and ensemble regression models to check base accuracy and mean squared error. Then compare the models to find the best possible model. 
  
  Deployment :   Using Streamlit built a webapp, to predict the Item_Outlet_Sales provided all necessary inpputs are provided
 
# Link
  
  https://store-sales-predict.herokuapp.com/
