# Mooc ML

## Cours 31/10/2017

[Gradient Descent](https://fr.wikipedia.org/wiki/Algorithme_du_gradient)
Optimisation du modèle

### Convolution Neural Network

Convolution : http://setosa.io/ev/image-kernels/
Ce n'est pas un produit de matrice, mais une fonction linéaire, suivie d'une fonction non linéraire (fonction d'activation)

https://medium.com/towards-data-science/linear-algebra-cheat-sheet-for-deep-learning-cd67aba4526c
http://neuralnetworksanddeeplearning.com/

### Loss Function (aka cost)

In machine learning the **loss** function or cost function is representing the price paid for inaccuracy of predictions. The goal is to improve the loss.
The loss associated with one example in binary classification is given by:

    -(y * log(p) + (1-y) * log (1-p))

### Learning Rate

The learning rate determines how quickly or how slowly you want to update the weights (or parameters). Learning rate is one of the most difficult parameters to set, because it significantly affect model performance.

TThe method `learn.lr_find()` helps you find an optimal learning rate. It uses the technique developed in the 2015 paper [Cyclical Learning Rates for Training Neural Networks](http://arxiv.org/abs/1506.01186), where we simply keep increasing the learning rate from a very small value, until the loss starts decreasing. We can plot the learning rate across batches to see what this looks like.

## Links

+ [crestle](https://www.crestle.com/)
+ [Stanford CS class](http://cs231n.github.io/)

+ Groups https://docs.google.com/spreadsheets/d/1MjY5tVIZy5VtBaDSqMI3wURKEWJQQEqYmnvIiIwcCdY/edit#gid=0

