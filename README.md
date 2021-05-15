# Amazon Fine Food Reviews 
Using review text data the objective is to predict whether the review sentiment is positive or negative.
This is a classification problem.

Dataset source : <a href=https://www.kaggle.com/snap/amazon-fine-food-reviews>Kaggle dataset</a>

## Data Labelling :
* Scores above 3 has been labelled as positive and below 3 as negative

## Preprocessing Steps :
* Remove html tags
* Remove punctuations, special characters
* Check for alpha numeric (avoid in most cases)
* Convert to lowercase
* Remove stopwords

## Feature Engineering :
* Bag of Words
* TF-IDF

## ML Models trained and validated :
* Logistic Regression on BoW
* Logistic Regression on TF-IDF

