# CIFAR-10-Classification
Image classification using ANN and CNN

The [ANN notebook](/CI_ANN.ipynb) includes implementing a fully connected artificial neural network from scratch to classify the CIFAR-10 dataset. This dataset is a smaller version of CIFAR-100 and has ten categories.
The [CNN notebook](/CI_ANN.ipynb) includes an implementation of a convolutional neural network for the same purpose. 

# ANN
The neural network was build based on the architecture shown below:
<p align="center">
  <img src="https://user-images.githubusercontent.com/79719208/196043699-7ddc27c1-15e0-476a-9900-43fdd8fd2afb.png">
</p>
The following steps were taken to build and train the network:

* Data visualization and preprocessing
  * RGB to Grayscale
  * Normalization
  * Flatten
  * Shuffle
* Feedforward
* Backpropagation
* Vectorization
* Test

# CNN
The below architecture was used to construct the initial network. Batch normalization and dropout layers were also added.
<p align="center">
  <img src="https://user-images.githubusercontent.com/79719208/196044282-223d1c2e-0515-435b-b921-4a42e5fbef8d.png" width=55% height=55%>
</p>
