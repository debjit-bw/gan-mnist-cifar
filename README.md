# GAN for MNIST and CIFAR-10

This Tensorflow custom implementation of a Generative Adversarial Network (GAN) is based on the [GAN paper](https://arxiv.org/abs/1406.2661) by Ian Goodfellow et al. The GAN is trained on the MNIST and CIFAR-10 datasets.

This is a work in progress. I am still working on improving the quality of the generated images. The generator and discriminator models are custom implemented using a NN pipeline on top of Keras. The GAN is trained using the Adam optimizer.