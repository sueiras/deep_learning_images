# Use cases for the course of deep learning for images

Use cases of image modeling with deep learning

- Use case 1: Data augmentation with MNIST
- Use case 2: Train from scratch with CIFAR10
- USe case 3: Transfer learning with cats vs dogs dataset

All use cases can be executed into Google colab environment

* [Data augmentation with MNIST]( https://colab.research.google.com/github/sueiras/deep_learning_images/blob/master/01_mnist_data_augmentation.ipynb)
* [Train from scratch with CIFAR10 basic]( https://colab.research.google.com/github/sueiras/deep_learning_images/blob/master/02_1_cifar10_VGG_based_architecture.ipynb)
* [Train from scratch with CIFAR10 Resnet]( https://colab.research.google.com/github/sueiras/deep_learning_images/blob/master/02_2_cifar10_resnet.ipynb)
* [Transfer learning with cats vs dogs dataset]( https://colab.research.google.com/github/sueiras/deep_learning_images/blob/master/03_transfer_learning_cats_vs_dogs.ipynb)
* [Yolo install]( https://colab.research.google.com/github/sueiras/deep_learning_images/blob/master/yolo/install_yolo.ipynb)
 * [Yolo train]( https://colab.research.google.com/github/sueiras/deep_learning_images/blob/master/yolo/train_yolo.ipynb)


# OPTIONAL. To execute the samples locally

If you want to execute the code in the local PC follow the next steps.

### Create a local Anaconda environment and install text mining packages

Open one Anaconda terminal and execute

```
conda create -n tf python=3.6
activate tf

conda install pip

conda install graphviz
conda install pandas scikit-learn
conda install -c anaconda jupyter 
conda install matplotlib
conda install pillow 
pip install h5py
pip install pydot-ng
pip install --ignore-installed --upgrade tensorflow 

```
Note: If you install spaCy and spaCy models without administrator privileges you can't create the symlinks. In this case use the .load() function in your code to load the models.


Download the datasets:

* cats vs dogs sample dataset: [cats vs dogs (128Mb)](https://s3-eu-west-1.amazonaws.com/training-dl/cats_dogs_sample.tar.gz)
* [Face detection dataset (16Mb)](https://s3-eu-west-1.amazonaws.com/training-dl/face_detection_dataset.zip)


To use yolo in local (windows). Follow the steps in: https://github.com/AlexeyAB/darknet#how-to-compile-on-windows-using-vcpkg



