# Machine Learning - [Master ICFP](https://www.phys.ens.fr/spip.php?rubrique284)

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
- The Neyman-Pearson Lemma
- Properties of ROC curves

### supervised learning
- Sample versus Population
- A first learning algorithm: the perceptron
- Connection to empirical risk minmization
- Formal guarantees for the perceptron

### practicals
- Naive Bayes (and logistic regression) https://github.com/mlelarge/icfp-ml/blob/main/01_NaivesBayes_Logistic_empty.ipynb

## 2. Unsupervised learning: k-means and EM

- K-means clustering
- Mixtures of Gaussian
- Expectation-Maximization for GMM

### practicals
- SVD and Eigenfaces https://github.com/mlelarge/icfp-ml/blob/main/02_SVD_Eigenfaces_empty.ipynb

## 3. Kernels

- Local averaging methods
    - partitions estimators
    - k-nearest neighbors
    - kernel smoothing
- Positive-definite kernel methods
    - representer theorem
    - kernel trick

### practicals
Random Fourier Features for Scalable Kernels https://github.com/mlelarge/icfp-ml/blob/main/03_kernel_random_fourier_empty.ipynb

## 4. Bayesian and Variational Inference

- Gaussian
- Linear regression
- Logistic regression
- Laplace method
- Variational inference

### practicals
Variational inference for the univariate Gaussian

## 5. Optimization for machine learning

- gradient descent
- SGD
- over-parameterized models:https://hackmd.io/@mlelarge/S1y5bEAhj

## 6. Pytorch basics and autodiff

[Module 2a - Pytorch tensors](https://dataflowr.github.io/website/modules/2a-pytorch-tensors/)

[Module 2b - Automatic differentiation](https://dataflowr.github.io/website/modules/2b-automatic-differentiation/)

[Module 5 - Stacking layers](https://dataflowr.github.io/website/modules/5-stacking-layers/)

## 7. Autoencoders and Normalizing Flows

[Module 9a - Autoencoders](https://dataflowr.github.io/website/modules/9a-autoencoders/)

[Module 9c - Flows](https://dataflowr.github.io/website/modules/9c-flows/)

## 8. Diffusion models ddpm

[Module 18a - Denoising Diffusion Probabilistic Models](https://dataflowr.github.io/website/modules/18a-diffusion/)
