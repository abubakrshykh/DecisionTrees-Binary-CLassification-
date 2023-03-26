# Decision Tree Model for Titanic Survival Prediction
# Introduction
The objective of this project is to build a decision tree model that can predict the survival of passengers on the Titanic based on certain features. The model is trained on a dataset of passengers' information, including their age, gender, class, fare, etc. The goal is to achieve high accuracy in predicting whether a passenger survived or not.

# Dataset
The Titanic dataset consists of two parts: training and testing datasets. The training dataset contains 891 records, and the testing dataset contains 418 records. The dataset contains various features such as age, gender, class, fare, cabin, etc. However, some features such as name and ticket number are not relevant to our model and are removed.

The dataset also contains missing values, which are replaced with either the median value of their respective columns.

# Model
I used the decision tree classifier to build our model. The model was trained on the preprocessed training dataset and then used to predict the survival outcome of passengers in the preprocessed test dataset. The accuracy of the model was measured using the accuracy_score function from the sklearn.metrics module.

# Training and Predicting the Model
After preprocessing the training and test datasets, we trained our decision tree model using the DecisionTreeClassifier() function from the sklearn.tree module. We then used this trained model to predict the survival outcome of passengers in the test dataset using the predict() method.

feel free to contibute.
