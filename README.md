# Programming Guide for Neural Network in Python
For people new to programming or Neural Network, it's always hard to tune the network and do everything efficiently.
This guide aims to help people learn some "little" techniques to make the whole process more efficient and convenient.

This is a programming guide based on [Keras](http://keras.io/) (a Python package for Neural Network), while the knowledge can also be applied to other packages, i.e., [Theano](http://deeplearning.net/software/theano/), or even other languages.
Before reading this guide, you may need the basic knowledge about how to use Keras.
We will start from a basic [MNIST](http://yann.lecun.com/exdb/mnist/) (a handwritten digits dataset) example in Keras, and then make it faster and use less memory.

Note that we won't talk about how to design the architecture of the Neural Network here.
You can refer to the [ResNet](http://arxiv.org/abs/1512.03385) architeture if you want to do some image recognition.
ResNet is currently the state-of-the-art image classification model, and it's very elegant comparing with many previous work.
