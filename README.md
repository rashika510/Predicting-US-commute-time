# Predicting-US-commute-time
Using Big Data Analytics to predict the US commute time based on the NHTS dataset.

# Goal of the project
The objective of the project was to predict commute time based on attributes such as trip miles, purpose, miles which was unlike the traditional prediction system.
The data set is from the National Household Travel Survey (NHTS) https://nhts.ornl.gov. We implemented regression for the project with Python, Apache Spark and Hadoop. To predict commute time, we used Linear Regression, Gradient Boosting, Elastic Net Regression and Random Forest for feature selection and prediction. For optimization, we leveraged feature engineering and hyper parameter optimization techniques.

# Technologies and Concepts

Technologies: Apache Spark, SparkSQL, SparkML, Python

Concepts: Data cleaning, Feature selection, Linear Regression, Gradient Boosting, Elastic Net Regression, Random Forest, Predictive modeling, hyper parameter optimization

# Results
The top features to predict the commute time were the trip miles, start time, travel dat, purpose, state divisons, urban/rural area, age, etc.
The algorithm which best predicted the commute time was Gradient Boosting with the least RMSE of 5.737. In this project, we analyzed that despite traffic and geolocation there are different attributes where we could predict commute time.
