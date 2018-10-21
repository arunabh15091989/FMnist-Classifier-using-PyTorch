# FMnist-Classifier-using-PyTorch
# Data Science Nanodegree
# Deep Learning


### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [PyTorch](https://anaconda.org/peterjc123/pytorch)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

Please install the following as well to make running python on your system easier:
 [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

Code uses the popular Fashion MNIST dataset and uses pytorch to create a multilayer perceptron which correctly identifies the 28X28 image provided to the neural network.

### Run

In a terminal or command window, navigate to the top-level project directory  that contains this README and run one of the following commands:

```bash
ipython notebook Part4-Fashion-MNIST-Exercise.ipynb
```  
or
```bash
jupyter notebook Part4-Fashion-MNIST-Exercise.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Zalando seeks to replace the original MNIST dataset




**Target Variable**
Each training and test example is assigned to one of the following labels:

0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot 
