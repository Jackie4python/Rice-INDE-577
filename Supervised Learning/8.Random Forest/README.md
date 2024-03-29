# Random Forest
A random forest is a supervised machine learning algorithm that is constructed from decision tree algorithms. 
This algorithm is applied in various industries such as banking and e-commerce to predict behavior and outcomes.  
A random forest algorithm consists of many decision trees. The ‘forest’ generated by the random forest algorithm is trained through bagging or bootstrap aggregating.
Bagging is an ensemble meta-algorithm that improves the accuracy of machine learning algorithms.
The (random forest) algorithm establishes the outcome based on the predictions of the decision trees. 
It predicts by taking the average or mean of the output from various trees. Increasing the number of trees increases the precision of the outcome.

## Task

In this project, we are going to work on some synthetic advertising dataset, indicating whether or not a particular internet user has clicked on an Advertisement.  
The goal is to predict if a user would click on an advertisement based on the features of the user by using the random forest method.

## Dataset
The data used for this model is a public data from Kaggle https://www.kaggle.com/farhanmd29/predicting-customer-ad-clicks.

The data contains the following features:  

- Daily Time Spent on Site: consumer time on site in minutes
- Age: cutomer age in years
- Area Income: Avg. Income of geographical area of consumer
- Daily Internet Usage: Avg. minutes a day consumer is on the internet
- Ad Topic Line: Headline of the advertisement
- City: City of consumer
- Male: Whether or not consumer was male
- Country: Country of consumer
- Timestamp: Time at which consumer clicked on Ad or closed window
- Clicked on Ad: 0 or 1 indicated clicking on Ad


## Libraires
Pandas https://pandas.pydata.org/  
Matplotlib https://matplotlib.org/  
Numpy https://numpy.org/  
Seaborn https://seaborn.pydata.org/  
Scikit-learn https://scikit-learn.org/  
