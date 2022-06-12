# Digits-Recognition-using-KNN
libraries used are numpy,matpotlib,sklearn and dataset MNIST.
MNIST Handwritten Digits Recognition using KNN 
K-Nearest Neighbours can be used for both classification and regression. 
K-NN is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure.
KNN is a type of instance-based learning, or lazy learning, where the function is only approximated locally and all computation is deferred until classification. 
The KNN algorithm is among the simplest of all machine learning algorithms.
It is a non-parametric algorithm wherein it doesn’t require training data for inference, hence training is much faster while inference is much slower when compared to parametric learning algorithm for all obvious reasons.
Procedures:
The ultimate goal is to correctly identify digits from a dataset of tens of thousands of handwritten images:-
The K-NN working can be explained below:\
Step-1: Select the number K of the neighbors\
Step-2: Calculate the Euclidean distance of K number of neighbors\
Step-3: Take the K nearest neighbors as per the calculated Euclidean distance.\
Step-4: Among these k neighbors, count the number of the data points in each category.\
Step-5: Assign the new data points to that category for which the number of the neighbor is maximum.\
Step-6: Our model is ready.
