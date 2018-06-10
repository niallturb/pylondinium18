# pylondinium18
Tuning the knobs of neural networks using Bayesian Optimization

### Description
Choosing the best hyperparameters for machine learning models is sometimes considered as more of an art than science. For most machine learning practitioners, mastering this art of tuning hyperparameters requires not only a competent background in machine learning algorithms, but also extensive experience working with real-world datasets. Most machine learning algorithms present a variety of hyperparameters to tune, and in the case of neural networks and deep learning models, the list of potential hyperparameters to adjust can increase exponentially. As such, deep learning models are notoriously tricky to optimally tune, where thorough exploration of architectures and hyperparameters is imperative.

Grid search and randomized search methodologies are traditionally used to tune model hyperparameters, however they are costly approaches and incorporate no notion of how trials of previous hyperparameters have performed. Bayesian Optimization is one such approach that forms knowledge about the relation between the hyperparameter settings and model performance in order to make a smarter choice for future parameter settings.

Using Zalando’s Fashion MNIST dataset, which comprises of 60,000 clothing images, I present the use of Bayesian Optimization to tune the hyperparameters of a convolutional neural network in Keras.

#### One dimensional toy Bayesian Optimization example
https://nbviewer.jupyter.org/github/niallturb/pylondinium18/blob/master/basic_bayes_opt_demo.ipynb

#### Full Fashion MNIST demo - tuning hyperparamters of CNN in Keras
https://nbviewer.jupyter.org/github/niallturb/pylondinium18/blob/master/fashion_mnist_bayes_opt.ipynb
