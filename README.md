# Project 1: TripAdvisor_Classifier

## Overview
As a traveller, all of us go through travel websites to check through the hotels, cafes, restaurants and other places for reviews, in the quest to get the ultimate experience possible. Here, I have created a classification model to predict review rating and performed topic modelling on reviews.


## Notebooks
There are two notebooks in this repository, namely -

1. tripadvisor_datacleaning.ipynb - Describing data, generating histogram, scatter and correlation heatmap plots.

2. tripadvisor_models.ipynb - Creating dummies, engineering new features, scale data, spliting data in train and test data frames. Fitting data in model, scoring model, and ploting predictions and errors.

## Methods
1. Statistic data description using Pandas,Numpy,wordcloud, librarys in Python.
2. Text columns were transformed using PorterStemmer, LancasterStemmer and WordNetLemmatize from nltk library.
3. Words were tokenized using CountVectorize from sklearn library
4. Data was slpit in 25% test and 75% train subsets.
5. Multinomial Naive Bayes, Random Trees, Extra Trees and Bagging with Decision Tree models were used.

## Results
1. The Random Forest Cassifier had a 91% accuracy in train set and 59% accuracy in test and 59% cross validation after hyperparameter tuning.
2. Adjective words were the ones with most impact in this model´s classification process.

## Softwares Used
1. Jupyter notebook
2. Python 3.9.13


## Data
The data folder contains two CSVs (in the zip file). These are -

1. New_Delhi_reviews.csv - Downloaded directly from the Kaggle website. (URL - https://www.kaggle.com/datasets/arnabchaki/tripadvisor-reviews-2023#:~:text=calendar_view_week-,New_Delhi_reviews.csv)
 
2. cleaned_TripAdvisor.csv - This csv file is the result of all the data cleaning done on the raw file downloaded directly from the Kaggle.

(This dataset has been taken from Kaggle. It consists of 20k reviews crawled from TripAdvisor.)
