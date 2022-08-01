# SimpleNeuralNetwork
A very simple two layer python neural network using numpy.

## What is a Neural Network
A neural network is a mathematical model inspired by the biological network of neurons found in the human brain. They work by having layers of nodes which can be simply thought of as a number which then gets changed by the connections between nodes that can be seen as a "weight" which is a vector of numbers and each node has a bias which changes the input to the node. A series of these nodes can then be used to group together inputs to an abstract output, for example an input of an image could be simplified to an output on a certain node which means "dog".</br>
To train the neural network, backwards propagation is used which adjusts the weights and biases of a network. The backwards propagation works through calculating the affect the weights and biases have on the cost function in order to adjust them.</br>
This code is a VERY simple two layer example which contains a single input and a single output. 
You could train this network to only output 1 if the input is greater than 0.5 and 0 otherwise.

## Machine Learning
Machine learning (ML) is a very wide topic generally reffering to algorithms which can recognise patterns in data.</br>
Neural Networks are a sub part of ML known as a supervised learning algorithm. This name comes from the fact that the data used to train a neural network must have labels however, Neural Networks can also be used as semi-supervised learning algorithms.</br>
ML also has unsupervised learning algorithms such as the K-Means clustering algorithm which works by clustering data into distinct clusters to recognise patterns.

## Dependencies
```
pip install matplotlib
pip install numpy
```
