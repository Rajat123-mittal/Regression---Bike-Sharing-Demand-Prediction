# Regression-Bike-Sharing-Demand-Prediction

Project Name - Regression - Bike Sharing Demand Prediction

Contribution - Individual

Presented By - Rajat Mittal

Email id - rajatmittal251@gmail.com

## About the Project
##Objective:

The primary objective of this project is to develop a regression model that accurately predicts the demand for bike sharing based on various factors. By leveraging features such as date, time, weather conditions, and seasonal variations, the model aims to provide insights into the number of bikes rented per hour. The ultimate goal is to optimize bike availability, enhance user experience, and improve operational efficiency for the bike-sharing service.

Dataset: The dataset comprises the following key features:

Date: Recorded in the format year-month-day.

Rented Bike Count: The count of bikes rented at each hour, serving as the target variable.

Hour: The hour of the day.

Temperature: Temperature in Celsius.

Humidity: Percentage of humidity.

Windspeed: Wind speed in m/s.

Visibility: Visibility in meters.

Dew Point Temperature: Dew point temperature in Celsius.

Solar Radiation: Solar radiation in MJ/m2.

Rainfall: Amount of rainfall in mm.

Snowfall: Amount of snowfall in cm.

Seasons: Categorical variable representing Winter, Spring, Summer, or Autumn.

Holiday: Binary indicator for holiday or no holiday.

Functional Day: Binary indicator for functional (Functional hours) or non-functional (Non Functional Hours) day.

Data Preprocessing:

1.Date Handling:

Extract day, month, and year from the 'Date' column.

2.Categorical Encoding:

Encode categorical variables like 'Seasons' using one-hot encoding or label encoding. Encode binary categorical variables 'Holiday' and 'Functional Day' as 0 or 1.

3.Missing Values:

Check for and handle missing values in the dataset.

Problem Statement
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyse the data to discover important factors that govern the bookings.

Required Skills
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Conclusion
The project successfully demonstrated the feasibility of using machine learning techniques to predict bike demand in Seoul.

Some of the key points are:-

High demand in the morning and evening.
Less Demand in the winter season.
Highest demand in june.
Found multicollinearity between temperature and dew point temperature.
Perform linear regression,Lasso Regression,Ridge regression but amongst them i have selected Ridge Regression as i achieved 70% training accuracy and 71% testing accuracy.
There is no use of removing outliers, it affects negatively on model performance.
Overall, the project highlights the potential of machine learning in solving real-world problems and provides a roadmap for future research in this area. The findings of this project can be extended to other cities with similar bike sharing systems, leading to more effective and efficient bike sharing operations, and better outcomes for all stakeholders.
