# Airbnb Dataset Analysis for Copenhagen.


This folder contains AirBnB listings  dataset for the city of Copenhagen,Denmark and python script which predicts price and average price in top 5 expensive and cheapest neighbourhood. A blog post describing this project in details is published on the website.

# Installation

listings dataset downloaded from AirBnB open source website.

The notebook uses Python 3.6.9. Other libraries used within the code are:

Data Analysis

* numpy (1.19.5)

* pandas (1.1.5)

* sklearn (0.22.2.post1)

Data Visualisation

* matplotlib (3.3.4)

You need a software like Anaconda to run ipython notebook or you can use Google Colab to create the python script.

# Project Motivation

Climate Change is one of the biggest concerns in this coming decade.Different cities across the globe have taken various initiatives to promote sustainability for greener and cleaner planet.Copenhagen, capital of Denmark is identified as greenest city in 2020 and that makes it my top preference for analysis.
I wanted to understand how AirBnB listing have faired in this greenest city and how a traveler can interpret this analysis to make better decision when searching for accomodation in Copenhagen and contribute to sustainability by making informed choices.

# File Description

The files included in this project are:

* listings.csv contains dataset used for analysis.

* Data Science_Project 1.ipynb  

# Project Summary
Part 1. This is project based on CRISP-DM. CRISP-DM has 6 steps. 1)Business Understanding 2) Data Understanding 3) Data Preparation 4) Modeling 5) Evaluation 6) Deployment.

This project is part of  Udacity DataScience Nanodegree program. 

To get the business understanding, I went through the AirBnB dataset to see how prices are predicted for various cities. The following business questions have piqued my curiosity to delve deeper into the dataset:

1) Which neighborhoods has highest AirBnB listings? 

2) What are the different types of AirBnB room? 

3) What are the average price of different types of room in the expensive and cheap neighbourhood ? 

4) How well can we predict prices? What aspects correlate well to prices? 

5) Can we see any co-relation between number of reviews and price?

Data Understanding was carried out by data visualization. Bar plots, scatter plots helped to understand the data and understand the spread.

Data Preparation was carried out to ensure there were no missinng values in the columns before applyiing algorithms. This was done by imputing the missing values.

Algorithm applied is linear regression and r2 square of the training and testing data decides whether it is overfitting or not.

Evaluation is carried out using r2 square and visulaizing the plot of test and train data. Testing and training data spread is uniform and there are few outliers.

Deployment is using these results to write the data science blog.

The blog for this project is [here](https://surfplanethoney.medium.com/how-to-predict-airbnb-listings-price-in-worlds-greenest-city-ca29b95bf2e3)

# Acknowledgements & Licensing

The dataset used for this analysis is available [here](http://insideairbnb.com/get-the-data.html)
The files used here are free to use.
