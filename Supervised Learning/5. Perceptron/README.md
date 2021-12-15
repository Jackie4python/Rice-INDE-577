# Perceptron

The perceptron is a basic function that mimics the human neuron. It receives  n  inputs, associated to the dendrites inputs to the neuron. 
Each dendrite, due to lernging, is weighted by a number that signals its input relevance for the neuron.

**How Perceptron Model Works?**
 - Perceptron Network is an artificial neuron with "hardlim" as a transfer function. It is mainly used as a binary classifier. Here, our goal is to classify the input into the binary classifier and for that network has to "LEARN" how to do that. "LEARN" means the model has to be trained to do so.  

 - For training, the network is provided with a bunch of inputs with already known outputs. As result is already known, the output of a network is compared with the already known results and with the help of the "Perceptron Learning Rules" model get trained.

**There are 2 functions in the perceptron network:**

- Summation function  
- The transfer function (Hardlim in our case) 

A bunch of inputs is provided to the network. Each neuron in the network has a weight associated with it. At the beginning Perceptron is a dense layer. This means Every input will pass through each neuron(Summation Function which will be pass through activation function) and will classify.

## Task

In this project, I will build a perceptron model from scratch and implement the perceptron learning algorithm for binary species classification.

## Dataset

The data used for this algorithm is the random data I generated. 

## Libraires
Pandas https://pandas.pydata.org/  
Matplotlib https://matplotlib.org/  
Numpy https://numpy.org/  
Seaborn https://seaborn.pydata.org/  
Scikit-learn https://scikit-learn.org/  
