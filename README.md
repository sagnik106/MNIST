# MNIST - Digit Classification
A deep Learning project to classify a handwritten digit based on the dataset from MNIST.

## Libraries/Requirements:
* Python 3.6.9
* Tensorflow 2.0
* Keras 2.2.4
* Numpy 1.15.4
* Matplotlib 3.0.2

## Model architecture:
1. ANN:
    * Input layer of dimension (28*28)
    * Dense layer of size (28*28) with relu activation
    * Dense layer of size (28*28) with relu activation
    * Dense layer of size 10 with softmax activation for prediction
1. CNN:
    * Input layer of dimension (28*28)
    * Reshape (28*28) tensor to (28,28,1)
    * Convolution layer of 32 filters with relu activation
    * Maxpooling layer
    * Convolution layer of 64 filters with relu activation
    * Maxpooling layer
    * Convolution layer of 128 filters with relu activation
    * Maxpooling layer
    * Flatten layer
    * Dense layer of size 1024 with relu activation
    * Dense layer of size 10 with softmax activation for prediction

## Training and Testing:
The [Jupyter Notebook](https://github.com/sagnik106/MNIST/blob/master/model.ipynb) has the related information and code