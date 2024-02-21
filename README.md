## MNIST Digit Classification Project
![MNIST](https://miro.medium.com/v2/resize:fit:1400/1*XdCMCaHPt-pqtEibUfAnNw.png)

### Overview

This project focuses on classifying handwritten digits from the MNIST dataset using the Stochastic Gradient Descent (SGD) classifier. The dataset is fetched from `sklearn.datasets using fetch_openml` as `MNIST_784`.

## Dataset

The MNIST dataset is a collection of 28x28 pixel grayscale images of handwritten digits (0 through 9). Each image represents a single digit, and the task is to train a model to correctly classify them.

## Model Used
`**Stochastic Gradient Descent (SGD) Classifier:**`

Stochastic Gradient Descent (SGD) is an iterative optimization algorithm commonly used in machine learning for training models. It is a variant of the gradient descent optimization technique. 
Stochastic Gradient Descent (SGD) works by iteratively updating the parameters of a machine learning model to minimize a specified loss function. The key steps in the SGD process are as follows:

 `**a. Initialization:**` Initialize the model parameters randomly.

`**b. Data Shuffling:**` Shuffle the training dataset to introduce randomness.

`**c. Iterative Process:**` For each training example or mini-batch of examples: Compute the gradient of the loss function with respect to the model parameters using the current example(s).Update the model parameters in the opposite direction of the gradient to minimize the loss.

`**d. Learning Rate:**` Multiply the gradient by a learning rate, which determines the step size in the parameter space.

`**e. Convergence:**` Repeat these steps until a specified number of iterations (epochs) or a convergence criterion is met.

![SGD](https://miro.medium.com/v2/resize:fit:491/1*n4ftRAKEJu8-gLB3pzY0DA.png)

## Result and Accuracy

|ML Model|Train Accuracy|Test Accuracy|
|---|---|---|
|Stochastic Gradient Descent (SGD) Regressor|97.3%|97.1%|

## Files Included

`MNIST_classification.ipynb`: Jupyter Notebook containing the code for data exploration, model training, and evaluation.
`requirements.txt`: List of required Python packages.

## Acknowledgment

The MNIST dataset used in this project is fetched using `fetch_openml` from the `sklearn.datasets`.




