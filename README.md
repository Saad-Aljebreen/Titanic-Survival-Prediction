


# Project_2_Titanic





## Problem Statment:
If you are familiar with the Titanic movie, you may have wondered about the story of Jack who died and Rose who survived! But what about the others? Fortuanetly, we have a a data set of the people who were on the titatnic and we would like to make a model that can predict the survival of a passenger given some features!

## Executive Summary:

1\ Objective: Developing a model that can predict survival of passengers based on certain features.

2\ Datasets Description:

https://www.kaggle.com/c/titanic/data

We have 2 main datasets. 
1- The main data set which has 891 entries(each representing a passenger) along with 12 features (columns) , starting with ID for each row/passenger. and ending with (Survived) which is an indicator (1 the passenger survived & 0 died). 'Survived' is our target feautre which is the base we want to develop a model to predict for test data. 
2- The testing data set which has 418 entries(each representing a passenger) along with 11 features (columns) , starting with ID for each row/passenger. There is no 'survived' since the goal of this set is to predict the target.

3\ Data Importing & Cleaning & Features Engineering: We import the data, look at it, and find out that it has some categorial and numerical values. We start looking at missing values (nulls), relation with target, and meaning of values. We came back to this section to do the feautres engineering after the initial modelling.

4\ EDA & Data Visualization: We start plotting categorical and numerical features against the target to see the possible effect and basic insight for each feature. We then plot some features together to see the relation between these features. Then we fill nulls with median, mode or mean depending on what seems appropriate from our EDA.

5\ Data Modeling:

We use a variety of differnt models keeping in mind some basic knowledge about models:

1- KNN with GridSearch 
2- KNN with GridSearchCV 
3- Bagging with GridSearchCV 
4- DT with GridSearchCV 
5- RFR with GridSearchCV





## Conclusions:

We developed 5 classifications models to predict survival rates based on the data set of the titanic passengers.

We have 2 main datasets. 1- The main data set which has 891 entries(each representing a passenger) along with 12 features (columns) , 'Survived' is our target feautre which can be 1 or 0. (Survived or not) 2- The testing data set which has 418 entries(each representing a passenger) along with 11 features (columns).

We imported the data, looked at it, and found out that it has some categorial and numerical values. We start looking at missing values (nulls), relation with target, and meaning of values.

Then we start EDA & Data Visualization: We start plotting categorical and numerical features against the target to see the possible effect and basic insight for each feature.

5\ Data Modeling:

We use a variety of differnt models keeping in mind some basic knowledge about models:

1- KNN with GridSearch 2- KNN with GridSearchCV 3- Bagging with GridSearchCV 4- DT with GridSearchCV 5- RFR with GridSearchCV

And finally, we went back to the data cleaning step to do features engineering, where we changed some columns and created new ones, and went back to the modelling step again.

Insights:

1- Mose of those who died are males from the economy class. Those men probably tried to help their family members if they had or other females and children if not.
