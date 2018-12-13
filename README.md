# A Recommender System Implementation Using Yelp Dataset on Kaggle.com
## Overview
The repository contains work under collaborative filtering applying Nicolas Hug's Surprise package (Singular Value Decomposition) as well as exploring injecting unsupervised cluster(s) (k-means) into SVD model.
## Data
Data can be obtained from kaggle.com @ https://www.kaggle.com/yelp-dataset/yelp-dataset
This is an academic set provided by Yelp (JSON format) with a substantial volume. You can also access it directly on Yelp website. 
## Process
This notebook contains:
1. API call to Yelp Fusion API to retrieve restaurant categories (almost cuisine-like strings)
2. Yelp dataset cleaning and exploratory data analysis using seaborn and bokeh
3. Modeling approach 1: applying Surprise's SVD and a GridsearchCV
4. Modeling approach 2: creating k-means clusters and inject one into SVD
5. A sample text analysis of reviews and regression to predict star ratings
