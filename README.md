# Sentiment-Analysis

* Using file handling method extracted the text data and converted to dataframe.
* Cleaned the data and analysed various columns like rating,review etc by duing Exploratory
Data Analysis. Made word cloud depending upon rating column so as to find words with
positive and negative sentiments.
* Now rating column is segregated in two parts, rating greater than three is taken as
positive sentiment and less than three as negative sentiment.
* Now divide the dataset into train, test. Preprocessed data by lowering case , removing
special characters, removing stop words etc.
* Used Bag of words to convert text data to an array. Used various classification tasks like
logistic regression, SVC, Decision Tree and various ensemble techniques with
hyperparameter tuning.
* Successfully made a logistic regression model with the accuracy of 93.38%
