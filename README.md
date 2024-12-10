# DTSA-5510-Unsupervised-Algorithms-in-Machine-Learning-Final-Project

I have chosen a dataset from Kaggle that contains measurements monetary bills. The dataset cointains 1500 rows and 7 columns. The data contains 1000 genuine bills and 500 fake bills.

The columns are:

is_genuine (True or False representing whether the bill is real or fake)
diagonal (the bills diagonal measurement in mm)
height_left (the height of left side of the bill in mm)
height_right (the height of the right side of the bill in mm)
margin_low (the bottom margin in mm)
margin_up (the upper_margin in mm)
length (the total length in mm)
The link to the Kaggle dataset is : https://www.kaggle.com/datasets/alexandrepetit881234/fake-bills/data

The goal of the project is to build a classification model that can correctly predict whether a bill is real or fake. In doing so, I want to compare supervised and unsupervised techniques to determine if there is a significant performance difference between the different methods. Below I am going to implement the following machine learning techniques and evaluate their performance:

Supervised Learning

Logistic Regression
K-Nearest Neighbors
Unsupervised Learning:

K-Means Clustering
Agglomerative Clustering
DBSCAN
