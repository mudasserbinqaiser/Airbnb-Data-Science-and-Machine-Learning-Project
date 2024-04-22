# Airbnb-Data-Science-and-Machine-Learning-Project
"What are the factors and features of a listing that make an Airbnb listing more expensive?" That is the question this project aims to answer.

I started of by collecting data of Airbnb listings from Kaggle. Then, I cleaned the data to a useful format for data analysis. Then I did Exploratory Analysis on the data by focusing on 3 sub-problems:

1. What are the features of a property that affect its price?
2. Are there particular neighborhoods where Airbnb listings fetch higher prices?
3. Does textual data in the summary and sentiments of reviews affect price?

I also answered questions like:

1. Can you spot any major differences in the Airbnb market between neighborhoods?
2. Are you able to identify any trends or seasonality in the review data?

Afterwards, we did Machine Learning on the data by adopting 4 different **Regression** models for our regression problem. They were:

1. Linear Regression
2. Random Forrest Regression
3. XGBoost
4. CatBoost

We partitioned the data into train and test sets and evaluated the models on their prediction accuracy. Once we found the most accurate prediction model, we used that model in a library called **TreeInterpreter** which decomposed the prediction into a sum of contributions from each feature. We used this to find the most important features that affected the price of a listing.

Author - Mudassar Bin Qaiser
