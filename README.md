# Sentimental_analysis_python
**Data Source: AICTE IBM Virtual Internship**
Sentiment Analysis of Restaurant Review The Restaurant review data content two features Reviews and liked , the reviews content whether positive , negative or neutral. For automating a detection of sentiment of the reviews from text ,build a prediction model to predict whether a review on the restaurant is positive or negative.

##Project Overview
In this project ,dealing with the Restaurant reviews dataset. In this dataset, there are
reviews from the customers which are either positive or negative. And now we are going to
build a machine learning model using both Support Vector Classifier(SVC) and
Countvectorizer methods.
 And finally, this model is going to predict whether the given review is either positive or
negative automatically. In traditional method analyst manually predict the reviews from
users and customers.

##Wow In System
**Pipeline**: The solution uses a pipeline to combine the preprocessing and modeling steps
into a single process. This makes the solution easier to use and maintain.

**Model selection**: The solution uses a support vector machine (SVM) classifier as the
machine learning model. SVM classifiers are well-suited for sentiment analysis tasks
because they can learn complex relationships between the features in the training data.

**Evaluation**: The solution uses accuracy_score and precision_score to evaluate the
performance of the model on the test set. This ensures that the model is generalizing
well to new data.

**Deployment**: The solution saves the trained model to a file using joblib.dump. This allows
the model to be deployed to production and used to make predictions on new restaurant
reviews
