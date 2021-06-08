# Amazon-Fine-Food-Reviews-Analysis
Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(tfidf). Build MultiNomial Naive Bayes to classify the polarity of the review.
Objective:
Given a text review, determine the sentiment of the review whether its positive or negative.

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

About Dataset
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

Attribute Information:

Id
ProductId - unique identifier for the product
UserId - unqiue identifier for the user
ProfileName
HelpfulnessNumerator - number of users who found the review helpful
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
Score - rating between 1 and 5
Time - timestamp for the review
Summary - brief summary of the review
Text - text of the review
1 Amazon Food Reviews EDA, NLP, Text Preprocessing and Visualization using TSNE
Defined Problem Statement
Performed Exploratory Data Analysis(EDA) on Amazon Fine Food Reviews Dataset plotted Word Clouds, Distplots, Histograms, etc.
Performed Data Cleaning & Data Preprocessing by removing unneccesary and duplicates rows and for text reviews removed html tags, punctuations, Stopwords and Stemmed the words using SnowBall Stemmer
Documented the concepts clearly

Naive Bayes
Applied Naive Bayes using Multinomial NB on TF-IDF Featurization of Data.
Evaluated the test data on various performance metrics like accuracy, f1-score, precision, recall,etc. also plotted Confusion matrix using seaborne
Printed Top 10 Important Features for both Negative and Positive Reviews
Conclusions:
Naive Bayes is much faster algorithm than a Random Model.
The performance of Multinomial naive bayes is way much more better than Random Model.
Best F1 score is acheived by TF-IDF featurization which is 0.75 and AUC Score is 0.79.
