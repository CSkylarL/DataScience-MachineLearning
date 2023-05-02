
# Fashion MNIST

Fashion MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples, each example is a 28x28 grayscale image, associated with a label from 10 classes.

Here is a illustration of the dataset from the [official website](https://github.com/zalandoresearch/fashion-mnist)
![image](https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/embedding.gif)

This folder contains the following files:
- Data
    - [X_train](./X_train.npy): The training features in `.npy` format.
    - [y_train](./y_train.npy): The training target in `.npy` format.
    - [X_test](./X_test.npy): The test features in `.npy` format.
    - [y_test](./y_test.npy): The test target in `.npy` format.
- [Data Description](./fashion_mnist.ipynb): A Jupyter notebook providing comprehensive details about the background, creation process, and distinct characteristics of the data.