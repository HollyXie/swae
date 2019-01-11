# SlicedWassersteinAE

This repository contains the implementation of our paper: ["Sliced-Wasserstein Autoencoder: An Embarrassingly Simple Generative Model"](https://arxiv.org/pdf/1804.01947.pdf) using Keras and Tensorflow. The proposed method ameliorates the need for adversarial networks in training generative models, and it provides a stable optimization while having a very simple implementation. 

A PyTorch implementation of the SWAE algorithm was kindly provided by [Emmanuel Fuentes](https://github.com/eifuentes/swae-pytorch).

### SWAE_MNIST_uniform.ipynb

This notebook trains the SWAE on the MNIST dataset with a uniform distribution in the embedding space. The figure below visualizes the embedded data and the embedding space for the MNIST dataset:


![](Figures/SWAE_uniform.png)



### SWAE_MNIST_Circle.ipynb

Similarly, this notebook trains the SWAE on the MNIST dataset with a disk distribution in the embedding space. The figure below visualizes the embedded data and the embedding space for the MNIST dataset:

![](Figures/SWAE_circle.png)


### SWAE_MNIST_Ring.ipynb

Similarly, this notebook trains the SWAE on the MNIST dataset with a ring distribution in the embedding space. The figure below visualizes the embedded data and the embedding space for the MNIST dataset:

![](Figures/SWAE_Ring.png)


### Pretrained Models

The pretrained SWAE modules are also uploaded:

* LearnedModels/MNIST_uniform(circle)(ring)_autoencoder.h5
* LearnedModels/MNIST_uniform(circle)(ring)_encoder.h5
* LearnedModels/MNIST_uniform(circle)(ring)_decoder.h5


