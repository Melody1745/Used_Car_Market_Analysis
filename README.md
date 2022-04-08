# Used_Car_Market_Analysis
# 1. Introduction and Problem
Over the past year, as the pandemic disrupted supply chains and caused shortages in critical auto components, resulting in a lack of new vehicles, which caused the used car price surging. According to the U.S. Bureau of Labor Statistics’ Consumer Price Index, used car prices are up a staggering 39.8% since March of 2020, while the U.S. inflation is only up 6.3%. JPMorgan analysts say prices will continue to rise and will stay high for longer than expected. It is difficult for people to use previous data and experience to judge whether the price of a used car is a good deal. So, this project tried to create a method to determine whether the price of a used car is appropriate.

# 2.The dataset is from cars.com
The 2021 dataset: https://www.kaggle.com/austinreese/craigslist-carstrucks-data

The 2020 dataset: https://www.kaggle.com/austinreese/craigslist-carstrucks-data/version/5

# 3.Exploratory Data Analysis
In this section, I tested various characteristics of used cars and try to have a better understanding of the data, as well as look at different combinations of features with the help of figures while exploring the data.

# 4. Data Preprocessing
Including missing value processing, encoding cateforical feature, and data normalization, to prepare the data for eslblishing predictive model.

# 5.Prediction
In this section, different machine learning algorithms, including Linear Regression, Decision Tree Regressor, Random Forest Tree Regressor, and XGBoost, are used to predict price/target variables. I applied machine learning models as a framework for data analysis. The dataset is supervised data, which refers to fitting a model of the dependent variable to the independent variable, with the goal of accurately predicting the dependent variable for future observation or understanding the relationship between the variables.

# 6.Conclusion
By comparing the accuracy, I finally choose the Random Forest model for price prediction. My approach is to determine whether the price of a used car is a good deal or a bad deal by comparing the listing price and the predicted price of this used car. I create functions to check whether the deal is good (the predicted price should be higher than the actual price).
If the listing price is less than the predicted price, the deal is considered a good deal; if the listing price is greater than the predicted price, the deal is considered a bad deal.
Finally, I use a function to select the cheapest car based on the "cars.com" dataset.
