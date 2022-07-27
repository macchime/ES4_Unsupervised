# ES4_Unsupervised
# MOVIE RECOMMENDER SYSTEM
Explore Team ES4 Project
=========================
INSTALLATION REQUIREMENTS
=========================
Importing critical libraries for data cleaning, manipulations and modeling:

    * !pip install surprise 
    * !pip install comet
    * !pip install wordcloud
 
LOAD AND VIEW DATA
======================
Importing the train & test data sets 
In order to work with the large dataset provided for us we formulated an algorithm after much research that could scale down the memory usage of this data so as to have a faster process time.
To import the datasets, when working on a jupyter notebook make sure the notebook is in the same folder as the csv files for the train and test datasets. To view the data and have a feel of the background of the data you can run the following codes 'test.head(), train.head(), genome_score.head(), genome_tags.head(), imdb.head(), links.head(), movies.head(), tags.head(), sample_submission.head()'to view the first five rows of the datasets.

DATA PREPROCESSING
==================
This is done to identify missing values, check the datatypes and further clean the dataset.
To identify and get the total number of missing values in the dataset you run a simple line of code 'train.isnull().sum(), test.isna().sum(), genome_score.isnull().sum(), genome_tags.isnull().sum(), imdb.isnull().sum(), links.isnull().sum(), movies.isnull().sum(), tags.isnull().sum() and finally sample_submission.isnull().sum()'. 

EXPLORATORY DATA ANALYSIS (EDA)
===============================
In this section we applied a variety of techniques to maximize specific insights into the dataset, reveal underlying structure, extract significant variables, detect outliers and anomalies, test assumptions, develop models and determine best parameters for estimations. Predominantly, EDA is done to dig deeper into a dataset to get more insights about it's behaviour.
For this dataset we started by plotting a barchart to check the number of apearances of each user to get a better insight on the data and hopefuuly detect outliers in the dataset, we then plotted a barchart to show the highest ratings the movies were getting from the users, we plotted another barchart to check the most popular movie genre in the dataset.


UNSUPERVISED LEARNING MODELS
============================
There two main unsupervised learning algorithms; 
The content-based filtering of which we used the cosine similarity algorithm and for the 
The collaborative filtering we used


*  Non-Negative Matrix Factorization Algorithm
*  SlopeOne AlgorithmRandom
*  CoClustering AlgorithmLinear
*  Singular Value Decomposition (SVD)
*  Singular Value Decomposition plus-plus (SVDpp)
*  BaselineOnly algorithm

