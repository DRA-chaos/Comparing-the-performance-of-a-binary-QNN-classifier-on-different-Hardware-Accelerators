# Quantum Neural Network for Binary Classification tested on various processors

This project encompasses building a Quantum Neural Network for the binary classification of digits (it can also be expanded to other instances of pattern recognition or image processing ) and comapring the performance od the model on three Processing Units ; CPU, GPU and TPU.
This project has been carried out under the guidance of Dr Amlan Chakrabarti, Professor and Director AKCSIT, Calcutta University.
All the notebooks above have been run on Google Colaboratory owing to the ease in integratig TensorFlow Quantum with Cirq.

## Pre-requisites
The following are the pre-requisites needed to run the notebooks on a local machine. (These have been mentioned in the Google Colab files as well)

* Python3
* tensorflow
* tensorflow_quantum
* cirq
* sympy
* numpy
* seaborn
* matplotlib
* collections

## Dataset:
The MNIST dataset distributed with Keras has been used in this project.
The MNIST database of handwritten digits, available on this [page](http://yann.lecun.com/exdb/mnist/) , has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.
This dataset was so chosen owing to it's simplicity and ease of use , notably to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

![image](https://user-images.githubusercontent.com/68393451/125188025-14410a80-e250-11eb-9293-12871ab9a51a.png)

[image source](https://en.wikipedia.org/wiki/MNIST_database#/media/File:MnistExamples.png)

## References :
[1]Cong, Iris & Choi, Soonwon & Lukin, Mikhail. (2018). Quantum Convolutional Neural Networks. https://arxiv.org/pdf/1802.06002.pdf

[2]Farhi, Edward & Neven, Hartmut. (2018). Classification with Quantum Neural Networks on  Near Term Processors. 

[3]Aliyev, Vagif. “A definitive explanation to the Hinge Loss for Support Vector Machines.” Towards data science, Medium, https://towardsdatascience.com/a-definitive-explanation-to-hinge-loss-for-support-vector-machines-ab6d8d3178f1.

[4]Beer, K., Bondarenko, D., Farrelly, T. et al. Training deep quantum neural networks. Nat Commun 11, 808 (2020). https://doi.org/10.1038/s41467-020-14454-2

[5]Chowdhury, Kunal. “Understanding loss functions : Hinge loss.” Analytics Vidhya, Medium, https://medium.com/analytics-vidhya/understanding-loss-functions-hinge-loss-a0ff112b40a1.

Flowchart outlining the architecture:

![image](https://user-images.githubusercontent.com/68393451/125188443-6898ba00-e251-11eb-88ce-6f657983009b.png)


Enjoy your journey through the quantum realm !

Rita Abani

