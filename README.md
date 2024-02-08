# Machine Learning - [Master ICFP](https://www.phys.ens.fr/en/formations/m2-icfp)

**Prerequisites**:
- Proficiency in Python: please use the tutorial [here](https://cs231n.github.io/python-numpy-tutorial/) for those who aren't as familiar with Python
- Basic Calculus, Linear Algebra
- Basic Probability and Statistics


## 1. Fundamentals of predictions and supervised learning

### Fundamentals of predictions
- Minimizing errors
- Modeling knowledge
- Prediction via optimization
- Types of errors and successes
- Properties of ROC curves

### practicals
- Exact ROC curves for Gaussian mixtures: https://github.com/mlelarge/icfp-ml/blob/main/Exact_ROC_GM.ipynb

### supervised learning
- Sample versus Population
- A first learning algorithm: the perceptron
- Connection to empirical risk minimization
- Formal guarantees for the perceptron

### practicals
- Naive Bayes and logistic regression: https://github.com/mlelarge/icfp-ml/blob/main/01_NaivesBayes_Logistic_empty.ipynb

## 2. Pytorch basics and autodiff

[Module 2a - Pytorch tensors](https://dataflowr.github.io/website/modules/2a-pytorch-tensors/)

[Module 2b - Automatic differentiation](https://dataflowr.github.io/website/modules/2b-automatic-differentiation/)

## 3. Optimization for machine learning

- gradient descent
- SGD
- over-parameterized models:https://hackmd.io/@mlelarge/S1y5bEAhj

### practicals
- [Module 5 - Stacking layers](https://dataflowr.github.io/website/modules/5-stacking-layers/)

- Heavy Ball Method: https://github.com/mlelarge/icfp-ml/blob/main/HeavyBall_empty.ipynb

## 4. Kernels

- Local averaging methods
    - partitions estimators
    - k-nearest neighbors
    - kernel smoothing
- Positive-definite kernel methods
    - representer theorem
    - kernel trick