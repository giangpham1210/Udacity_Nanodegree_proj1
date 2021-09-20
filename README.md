# [Udacity_Nanodegree_DataScience] Boston AirBNB

This repository is for my first project in Udacity Nanodegree Data Science course.

>- My notebook: https://github.com/giangpham1210/Udacity_Nanodegree_proj1/blob/main/boston-airbnb.ipynb
>- My blog: https://www.kaggle.com/giangphamhl/boston-airbnb?scriptVersionId=75215457

## 1.	Objective:
This is my first project for Udacity Data Science Nanodegree and it is to understand some insights and to check the feature correlations of Boston AirBnB data.
The project focuses on 4 following questions:
>- Question 1: Correlations between Price and other Features
>- Question 2: Model formulation to predict Price using Linear Regression Algorithm
>- Question 3: The most frequent n_grams in Review dataset's comments
>- Question 4: Distribution of Price, Listing Supply and Listing Demand


The CRISP-DM methodology is used to build this data science project, including:
>- Business Understanding
>- Data Understanding
>- Prepare Data
>- Model Data
>- Results

## 2.	Libraries used in the Jyupyter notebook
>- Numpy
>- Pandas
>- Matplotlib
>- Seaborn
>- Datetime
>- Sklearn
>- Nltk
>- Re
>- String
>- Collections

## 3. Files used
>- calendar.csv
>- listing.csv
>- review.csv

## 4. Results
>- There are some factors that are positively correlated to price, such as number of accomodates, number of bedrooms or number of beds. These factors are also used to understand how much they affects the price by using a basic linear regression. Nonetheless, the R2_score is quite low so feature selection step should be carefully considered or other different regression models should be used.
>- Based on the high frequency of positive comments, such as "great", "clean", "nice", "highly recommend", it can be said that the good reviews for rentals account for a large proportion.
>- In question 4, I made the assumption that the number of reviews is proportional to the number of uses of the Airbnb service in Boston. With this assumption, it is easily seen that the demand for rooms in December, January and February is much lower than in the others. Meanwhile, service supply and price remained unchanged between months. Therefore, I recommend that listing owners should lower the room rates from December to February to increase competition and attract more visitors. 
