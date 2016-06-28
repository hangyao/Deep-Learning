# Deep Learning notMNIST
- 1_notmnist: Preprocess notMNIST data and train a simple logistic regression model on it.
- 2_fullyconnected: Train a fully-connected network using Gradient Descent and Stochastic Gradient Descent.
- 3_regularization: Use regularization techniques to improve a deep learning model.
- 4_convolutions: Design and train a Convolutional Neural Network.
- 5_word2vec: Train a skip-gram model on Text8 data and visualize the output.

## Install

This project requires **Python 2.7** and the following Python libraries installed:

- [TensorFlow](http://www.tensorflow.org/)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [SciPy library](http://www.scipy.org/scipylib/index.html)
- [Six](http://pypi.python.org/pypi/six/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

## Code

Template code is provided in the following notebook files:
- `1_notmnist.ipynb`
- `2_fullyconnected.ipynb`
- `3_regularization.ipynb`
- `4_convolutions.ipynb`
- `5_word2vec.ipynb`

## Run

In a terminal or command window, navigate to the top-level project directory `notMNIST/` (that contains this README) and run one of the following commands:

```ipython notebook 1_notmnist.ipynb```  
```jupyter notebook 1_notmnist.ipynb```

This will open the iPython Notebook software and project file in your browser.

## Data

Notebook #1 to #4 use the [notMNIST](http://yaroslavvb.blogspot.com/2011/09/notmnist-dataset.html) dataset to be used with python experiments. This dataset is designed to look like the classic MNIST dataset, while looking a little more like real data: it's a harder task, and the data is a lot less 'clean' than MNIST.

Notebook #5 uses the [Text8](http://mattmahoney.net/dc/textdata) dataset.
