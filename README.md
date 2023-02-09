<<<<<<< HEAD
# Sentiment Analysis on ~500000 Tweets to Predict Real State Pricing Trend in 2010 to 2021
=======
# Sentiment Analysis on collected Tweets to Predict Real State Pricing Trend in 2010 to 2021
>>>>>>> 2f6157bd69355d56b38fbb762b77397a0ec86c98
## Author: Milad(Mylo) Ebtedaei

This work was done for a private project and the dataset cannot be released because I don't own the copyright. However, everything in this repository can be easily modified to work with other datasets.

## Dataset Information
We use and compare various different methods for sentiment analysis on tweets collected from Twitter with tweepy tweepy which is a python library for accessing the Twitter API. The dataset is a combined csv file. 

## Requirements
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

numpy
scikit-learn
scipy
nltk
The library requirements specific to some methods are:
.
.
.
Analyzes sentiment from Twitter tweets on housing prices to determine impact of public sentiment on Real Estate pricing.
This repository contains all the associated work that has been done for the area which includes:
Tweepy as a Python library for accessing the Twitter API and collecting tweets
Notebooks associated with data engineering, LDA and regression Modeling
Web App

## Interesting facts from exploratory data analysis
Less 0.01% users will push tweets with their locations.
More than 65.6% users will write the locations in their profile, although very few of them don't live on Earth according to that fact. In this project we have used the location that is mentioned in the profile.

## Orignal Development
- Extract Twitter Data, preprocess data in Python
- Combine collected tweets in the form of dataframes together 
- Perform exploratory data analysis and text clening on tweets
- Connect with Plotly for interactive dashboard 

## Challenges
Unstructured tweet texts may contain messy code and emoji characters
Most of the tweets were created by bots or were advertisement
It's hard to get Tweiter's approval to collect the tweets with tweepy for more than 500.000 tweets
Plotly doesn't have well-document on reference making customize dashboard much harder

## Questions?
Email the author at mylo.ebted@gmail.com
