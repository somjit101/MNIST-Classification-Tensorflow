# MNIST-Classification-Tensorflow

A simple, exploratory project on the usage of the Tensorflow platform (without Keras) for an image classification task, using an Artifical Neural Network. Nowadays, Keras has made it much easier for us to use the tensorflow background with its intuitive syntax and function definitions, but it might help for us to be familiar with the original syntax of Tensorflow to equip ourselves for future developments on this library. 

## Dataset 

We have used the renowned [MNIST Handwritten Digits Dataset](http://yann.lecun.com/exdb/mnist/) containing 60,000 train samples and 10,000 test samples of 28x28 grayscale images depicting numerical digits written by a huge number of human subjects. 

## Neural Architectures Used

**Here, we have made use of pure Tensorflow to implement the following Neural Network Architectures :** </br>
(The numbers in brackets indicate the number of neurons in teh corresponding Layer)

1. Input Layer [784] ⟶ Sigmoid Activation [512] ⟶ Sigmoid Activation [128] ⟶ Softmax Output Layer [10]
2. Input Layer [784] ⟶ ReLu Activation [512] ⟶ ReLu Activation [128] ⟶ Sigmoid Output Layer [10]
3. Input Layer [784] ⟶ Sigmoid Activation with BatchNormalization [512] ⟶ Sigmoid Activation with BatchNormalization [128] ⟶ Sigmoid Output Layer [10]
4. Input Layer [784] ⟶ ReLu Activation [512] - Dropout Layer ⟶ ReLu Activation [128] ⟶ Dropout Layer ⟶ Sigmoid Output Layer [10]
