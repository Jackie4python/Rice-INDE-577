# Linear Regression
Before there was any ML algorithms, there was a concept and that was regression.
Linear regression is most simple and every beginner Data scientist or Machine learning Engineer start with this. 
Linear regression comes under supervised model where data is labelled. 
In linear regression we will find relationship between one or more features(independent variables) like x1,x2,x3………xn. and one continuous target variable(dependent variable) like y.

Once the parameter values i.e bias term and theta1 are randomly initialized, the hypothesis function is ready for prediction, 
and then the error (|predicted value – actual value|) is calculated to check whether the randomly initialized parameter is giving the right prediction or not.

## Task

This project is implemented for a projct of Class 577 Statistic. I finished this project with Chirs, Haoyang, and Carlos.  
Firstly clean up and reorgnizing the data. Then remove some features that have nothing to do with housing prices, leaving only those that are related to housing prices. 
Then perform a simple linear regression, find out the characteristics that have l greatest relationship with house prices through heatmap,
and perform linear regression with house prices one by one. 
Finally, we select some characteristics that are most relevant to housing prices to perform multiple linear regression on housing prices.

## Dataset 
The data used for this algorithm is a public data from Kaggle [https://www.kaggle.com/shivachandel/kc-house-data].  
In this dataset the sales price of houses in King County, Seattle are present. It includes homes sold between May 2014 and May 2015.  
By observing the data, we can know that the price is dependent on various features like bedrooms(which is most dependent feature), bathrooms, 
sqft_living(second most important feature), sqft_lot, floors etc. The price is also dependent on the location of the house where it is present. 

## Libraies Used 
Pandas https://pandas.pydata.org/  
Matplotlib https://matplotlib.org/  
Numpy https://numpy.org/  
Seaborn https://seaborn.pydata.org/  
Scikit-learn https://scikit-learn.org/  
