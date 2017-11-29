# Project Sophia: Make Neural Networks from Scratch

It's good to go back to the basic sometime after all the Deep Learning noise. We tend to forget that learning things the hard way and learning the low level details of neural networks is important in the long run, be it for research engineer or software engineer. It's like, learning the theory behind neural networks is not important when you just getting started but at some point of time in the future, we will run into problem and we need to understand the lower level details in order to debug and fix the problem. As a software engineer, yeah, we know this is not your problem and you can always get help from a researcher. But at this stage, I like to think we are in the assembly language era of Computer Science. There is a real shortage of research engineer in the Deep Learning field.

This project was ~~plagiarized from~~ inspired by:
* Stanford [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/neural-networks-case-study/) course taught by Andrej Karparthy, Justin Johnson, and Serena Yeung
* Chris Olah's [Colah Blog](http://colah.github.io/posts/2015-08-Backprop/)
* Worth to mention Andrew Ng, Kian, and Younes's [Coursera Deep Learning MOOC](https://www.deeplearning.ai/) also in the same spirit.
* Andrew Trask's ["A Neural Network in 11 lines of Python"](https://iamtrask.github.io/2015/07/12/basic-python-network/)

This notebook recreates neural network algorithms using only the linear algebra library `numpy` (uses other libraries for performance benchmark and visualization). The sample data is a 2-dimensional data with three classes in a form of spirals. 

The content consists of the following aspects of neural networks:

* Weight initialization
* Loss functions
    * Cross-entropy loss
    * Hinge loss
    * Regularization loss
* Layers
    * Linear
    * Sigmoid
    * Tanh
    * ReLu
    * Swish
    * Softmax
    * SVM
    * Dropout (TBD)
    * Batch Normalization (TBD)
    * Convolution (TBD)
    * LSTM (TBD)
    * Embeddings (TBD)
* Training
    * Linear > Softmax
    * Linear > SVM
    * [Linear > Activation]++ > [Linear > Output]
* Optimization (TBD)
* Validation (TBD)
