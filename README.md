# Star-Rating-Based-on-Amazon-Movie-Reviews

## Overview
This is a kaggle competition project. The goal of this project is to predict the star rating associated with user reviews from Amazon Movie Reviews using the available features. We are allowed to use any technique except deep learning for our predictions, like classical machine learning algorithms, random forests, linear regression, etc.

## Data
#### Dataset Description
* train.csv - 1,697,533 unique reviews from Amazon Movie Reviews, with their associated star ratings and metadata. It is not necessary to use all reviews, or metadata for training. Some reviews will be missing a value in the 'Score' column. That is because, these are the scores you want to predict.
* test.csv - Contains a table with 300,000 unique reviews. The format of the table has two columns; i) 'Id': contains an id that corresponds to a review in train.csv for which you predict a score ii) 'Score': the values for this column are missing since it will include the score predictions. You are required to predict the star ratings of these Id using the metadata in train.csv.
* sample.csv - a sample submission file. The 'Id' field is populated with values from test.csv.

#### Data fields
* ProductId - unique identifier for the product
* UserId - unique identifier for the user
* HelpfulnessNumerator - number of users who found the review helpful
* HelpfulnessDenominator - number of users who indicated whether they found the review helpful
* Score - rating between 1 and 5
* Time - timestamp for the review
* Summary - brief summary of the review
* Text - text of the review
* Id - a unique identifier associated with a review  

Note: Some of the rows of the table may have some of these values missing.

#### Dataset Citation

J. McAuley and J. Leskovec. From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews. WWW, 2013
