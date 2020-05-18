# DOG & CAT CLASSIFIER USING CNN

![](https://raw.githubusercontent.com/Mohitkr95/Dog-Cat-Classifier-using-CNN/master/Images/1_biZq-ihFzq1I6Ssjz7UtdA.jpeg)

The dogs vs cats dataset refers to a dataset used for a Kaggle machine learning competition held in 2013.

The dataset is comprised of photos of dogs and cats provided as a subset of photos from a much larger dataset of 3 million manually annotated photos. The dataset was developed as a partnership between Petfinder.com and Microsoft.

The dataset was originally used as a CAPTCHA (or Completely Automated Public Turing test to tell Computers and Humans Apart), that is, a task that it is believed a human finds trivial, but cannot be solved by a machine, used on websites to distinguish between human users and bots. Specifically, the task was referred to as “Asirra” or Animal Species Image Recognition for Restricting Access, a type of CAPTCHA. The task was described in the 2007 paper titled “[Asirra: A CAPTCHA that Exploits Interest-Aligned Manual Image Categorization](https://www.microsoft.com/en-us/research/publication/asirra-a-captcha-that-exploits-interest-aligned-manual-image-categorization/)".
In this project I have used the subset of original data from [Deep Learning A-Z™: Hands-On Artificial Neural Networks](https://www.udemy.com/course/deeplearning/#instructor-1) and the project is inspired by **Kirill Eremenko**. In this project I have used the CNN to classify whether the given input image is of Dog or Cat. Here is the link to the [Dataset](https://www.kaggle.com/uysimty/keras-cnn-dog-or-cat-classification/data).

## Installation Instructions

### How to install Theano, TensorFlow and Keras

**For Mac users:**

Open your main terminal or the Anaconda Prompt and enter the following commands:
pip install theano
pip install tensorflow
pip install keras
conda update --all

**For Windows and Linux users:**
In Spyder, go to Tools and Open Anaconda Prompt. Then enter the following commands:
1. Create a new environment with Anaconda and Python 3.5:
conda create -n tensorflow python=3.5 anaconda
2. Activate the environment:
activate tensorflow
3. After this you can install Theano, TensorFlow and Keras:
conda install theano
conda install mingw libpython
pip install tensorflow
pip install keras
4. Update the packages:
conda update --all
5. Run Spyder:
spyder

To install TensorFlow on your GPU (optional):
pip install tensorflow-gpu

## More about Convolutional Neural Network

![](https://raw.githubusercontent.com/Mohitkr95/Dog-Cat-Classifier-using-CNN/master/Images/cnn_example.png)

In deep learning, a convolutional neural network (CNN, or ConvNet) is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks (SIANN), based on their shared-weights architecture and translation invariance characteristics. They have applications in image and video recognition, recommender systems, image classification, medical image analysis, natural language processing, and financial time series.[6]

CNNs are regularized versions of multilayer perceptrons. Multilayer perceptrons usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer. The "fully-connectedness" of these networks makes them prone to overfitting data. Typical ways of regularization include adding some form of magnitude measurement of weights to the loss function. CNNs take a different approach towards regularization: they take advantage of the hierarchical pattern in data and assemble more complex patterns using smaller and simpler patterns. Therefore, on the scale of connectedness and complexity, CNNs are on the lower extreme.


