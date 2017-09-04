# TensorFlow Examples
Code examples for some popular machine learning algorithms, using TensorFlow library. This tutorial is designed to easily dive into TensorFlow, through examples. It includes both notebook and code with explanations.

## Tutorial index

#### 1 - Introduction
- Hello World ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/1%20-%20Introduction/helloworld.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/1%20-%20Introduction/helloworld.py))
- Basic Operations ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/1%20-%20Introduction/basic_operations.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/1%20-%20Introduction/basic_operations.py))

#### 2 - Basic Classifiers
- Nearest Neighbor ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2%20-%20Basic%20Classifiers/nearest_neighbor.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/2%20-%20Basic%20Classifiers/nearest_neighbor.py))
- Linear Regression ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2%20-%20Basic%20Classifiers/linear_regression.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/2%20-%20Basic%20Classifiers/linear_regression.py))
- Logistic Regression ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2%20-%20Basic%20Classifiers/logistic_regression.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/2%20-%20Basic%20Classifiers/logistic_regression.py))

#### 3 - Neural Networks
- Multilayer Perceptron ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/3%20-%20Neural%20Networks/multilayer_perceptron.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3%20-%20Neural%20Networks/multilayer_perceptron.py))
- Convolutional Neural Network ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/3%20-%20Neural%20Networks/convolutional_network.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3%20-%20Neural%20Networks/convolutional_network.py))
- AlexNet ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/3%20-%20Neural%20Networks/alexnet.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3%20-%20Neural%20Networks/alexnet.py))
- Recurrent Neural Network (LSTM) ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/3%20-%20Neural%20Networks/reccurent_network.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3%20-%20Neural%20Networks/recurrent_network.py))
- Bidirectional Recurrent Neural Network (LSTM) ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/3%20-%20Neural%20Networks/bidirectional_rnn.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3%20-%20Neural%20Networks/bidirectional_rnn.py))
- AutoEncoder ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3%20-%20Neural%20Networks/autoencoder.py))

#### 4 - Multi GPU
- Basic Operations on multi-GPU ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/4%20-%20Multi%20GPU/multigpu_basics.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/4%20-%20Multi%20GPU/multigpu_basics.py))

#### 5 - User Interface (Tensorboard)
- Graph Visualization ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/5%20-%20User%20Interface/graph_visualization.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/5%20-%20User%20Interface/graph_visualization.py))
- Loss Visualization ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/5%20-%20User%20Interface/loss_visualization.ipynb)) ([code](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/5%20-%20User%20Interface/loss_visualization.py))


## More Examples
The following examples are coming from [TFLearn](https://github.com/tflearn/tflearn), a library that provides a simplified interface for TensorFlow. You can have a look, there are many [examples](https://github.com/tflearn/tflearn/tree/master/examples) and [pre-built operations and layers](http://tflearn.org/doc_index/#api).

#### Basics
- [Linear Regression](https://github.com/tflearn/tflearn/blob/master/examples/basics/linear_regression.py). Implement a linear regression using TFLearn.
- [Logical Operators](https://github.com/tflearn/tflearn/blob/master/examples/basics/logical.py). Implement logical operators with TFLearn (also includes a usage of 'merge').
- [Weights Persistence](https://github.com/tflearn/tflearn/blob/master/examples/basics/weights_persistence.py). Save and Restore a model.
- [Fine-Tuning](https://github.com/tflearn/tflearn/blob/master/examples/basics/finetuning.py). Fine-Tune a pre-trained model on a new task.
- [Using HDF5](https://github.com/tflearn/tflearn/blob/master/examples/basics/use_hdf5.py). Use HDF5 to handle large datasets.
- [Using DASK](https://github.com/tflearn/tflearn/blob/master/examples/basics/use_dask.py). Use DASK to handle large datasets.

#### Computer Vision
- [Multi-layer perceptron](https://github.com/tflearn/tflearn/blob/master/examples/images/dnn.py). A multi-layer perceptron implementation for MNIST classification task.
- [Convolutional Network (MNIST)](https://github.com/tflearn/tflearn/blob/master/examples/images/convnet_mnist.py). A Convolutional neural network implementation for classifying MNIST dataset.
- [Convolutional Network (CIFAR-10)](https://github.com/tflearn/tflearn/blob/master/examples/images/convnet_cifar10.py). A Convolutional neural network implementation for classifying CIFAR-10 dataset.
- [Network in Network](https://github.com/tflearn/tflearn/blob/master/examples/images/network_in_network.py). 'Network in Network' implementation for classifying CIFAR-10 dataset.
- [Alexnet](https://github.com/tflearn/tflearn/blob/master/examples/images/alexnet.py). Apply Alexnet to Oxford Flowers 17 classification task.
- [VGGNet](https://github.com/tflearn/tflearn/blob/master/examples/images/vgg_network.py). Apply VGG Network to Oxford Flowers 17 classification task.
- [RNN Pixels](https://github.com/tflearn/tflearn/blob/master/examples/images/rnn_pixels.py). Use RNN (over sequence of pixels) to classify images.
- [Residual Network (MNIST)](https://github.com/tflearn/tflearn/blob/master/examples/images/residual_network_mnist.py). A residual network with shallow bottlenecks applied to MNIST classification task.
- [Residual Network (CIFAR-10)](https://github.com/tflearn/tflearn/blob/master/examples/images/residual_network_cifar10.py). A residual network with deep bottlenecks applied to CIFAR-10 classification task.
- [Auto Encoder](https://github.com/tflearn/tflearn/blob/master/examples/images/autoencoder.py). An auto encoder applied to MNIST handwritten digits.

#### Natural Language Processing
- [Reccurent Network (LSTM)](https://github.com/tflearn/tflearn/blob/master/examples/nlp/lstm.py). Apply an LSTM to IMDB sentiment dataset classification task.
- [Bi-Directional LSTM](https://github.com/tflearn/tflearn/blob/master/examples/nlp/bidirectional_lstm.py). Apply a bi-directional LSTM to IMDB sentiment dataset classification task.
- [City Name Generation](https://github.com/tflearn/tflearn/blob/master/examples/nlp/lstm_generator_cityname.py). Generates new US-cities name, using LSTM network.
- [Shakespeare Scripts Generation](https://github.com/tflearn/tflearn/blob/master/examples/nlp/lstm_generator_shakespeare.py). Generates new Shakespeare scripts, using LSTM network.

## Dependencies
```
tensorflow
numpy
matplotlib
cuda (to run examples on GPU)
tflearn (if using tflearn examples)
```
For more details about TensorFlow installation, you can check [Setup_TensorFlow.md](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/Setup_TensorFlow.md)

## Dataset
Some examples require MNIST dataset for training and testing. Don't worry, this dataset will automatically be downloaded when running examples (with input_data.py).
MNIST is a database of handwritten digits, with 60,000 examples for training and 10,000 examples for testing. (Website: [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/))
