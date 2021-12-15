# Multi-Layer Perceptron

A multi-layer perceptron (MLP) has the same structure of a single layer perceptron with one or more hidden layers. 
The backpropagation algorithm consists of two phases: the forward phase where the activations are propagated from the input to the output layer, and the backward phase, 
where the error between the observed actual and the requested nominal value in the output layer is propagated backwards in order to modify the weights and bias values.

## Task

This project is implemented for a projct of Class 577 Statistic. I finished this project with Chirs, Haoyang, and Carlos.  
Firstly clean up and reorgnizing the data. Then remove some features that have nothing to do with housing prices, leaving only those that are related to housing prices.
Then perform MLP regression, find out the characteristics that have l greatest relationship with house prices through heatmap,
and perform MLP regression with house prices one by one. 

## Dataset

The data used for this algorithm is a public data from Kaggle [https://www.kaggle.com/shivachandel/kc-house-data].  
In this dataset the sales price of houses in King County, Seattle are present. It includes homes sold between May 2014 and May 2015.  
By observing the data, we can know that the price is dependent on various features like bedrooms(which is most dependent feature), 
bathrooms, sqft_living(second most important feature), sqft_lot, floors etc. The price is also dependent on the location of the house where it is present.  

## Libraires
Pandas https://pandas.pydata.org/  
Matplotlib https://matplotlib.org/  
Numpy https://numpy.org/  
Seaborn https://seaborn.pydata.org/  
Scikit-learn https://scikit-learn.org/  
Scipy https://scipy.org/  
Tensorflow https://www.tensorflow.org/  
Keras https://keras.io/  



