# Titanic Survival Prediction using Naive Bayes Classifier Algorithm
This project aims to predict the survival of passengers aboard the Titanic using the Naive Bayes classifier algorithm. The dataset used in this project contains information about Titanic passengers, such as their age, gender, passenger class, and other relevant features. By training a Naive Bayes classifier on this data, we can predict whether a given passenger would have survived the Titanic disaster.

## Dataset
The dataset used in this project is the Titanic dataset, which contains information about passengers from the Titanic ship. It consists of the following columns:

* survived: 0 if the passenger did not survive, 1 if the passenger survived (target variable).
* p_class: Passenger class (1, 2, or 3).
* gender: Gender of the passenger.
* age: Age of the passenger.
* sib_sp: Number of siblings/spouses aboard the Titanic.
* parch: Number of parents/children aboard the Titanic.
* fare: Fare paid by the passenger.
* embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Naive Bayes Classifier Algorithm
The Naive Bayes classifier algorithm is a probabilistic machine learning algorithm that is based on Bayes' theorem. It assumes that all features are independent of each other, hence the term "naive." Despite this assumption, the Naive Bayes classifier has been proven to perform well in many real-world applications, including text classification and spam filtering.

The steps involved in using the Naive Bayes classifier algorithm for the Titanic survival prediction are as follows:

1. Load the Titanic dataset.
2. Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features if necessary.
3. Split the data into training and testing sets.
4. Train a Naive Bayes classifier on the training data.
5. Evaluate the performance of the classifier on the testing data using appropriate metrics, such as accuracy, precision, recall, or F1 score.
6. Predict the survival outcome for new, unseen data using the trained classifier.