# Ensemble
Ensembling is a technique for combining two or more similar or dissimilar machine learning algorithms to create a model that delivers superior predictive power.

ML-Ensemble combines a Scikit-learn high-level API with a low-level computational graph framework to build memory efficient, 
maximally parallelized ensemble networks in as few lines of codes as possible.
ML-Ensemble is thread safe as long as base learners are and can fall back on memory mapped multiprocessing for memory-neutral process-based concurrency.

## Task
In this project, we are going to work on some synthetic advertising dataset, indicating whether or not a particular internet user has clicked on an Advertisement.  
The goal is to predict if a user would click on an advertisement based on the features of the user by using three different algoritms,such as 
LogisticRegression, RandomForestClassifier, DecisionTreeClassifier,and finally we combine these three methods by using VotingClassifier.

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
