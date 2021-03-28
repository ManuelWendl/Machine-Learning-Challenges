# Digit Recognizer - Kaggle
This repository contains a sample solution for the kaggle challenge to recognize handwritten digits of the MNIST dataset. The coding challenge can be found on 
https://www.kaggle.com/c/digit-recognizer/submit.
### Task:
Classify hanndwritten images.
### Dataset:
The pictures are stored in the rows of the imported matrices. The training target is the first column of the trainingsdata. 
### Classifying Algorithms:
- In Digit Recognizer DNN.ipynb, there was again used a dense neural network. This network is built from scratch only with numpy and has an adaptable architecture. 
It is the same network already used in the other MNIST digit recognition repo.
- In Digit Recognizer CNN.ipynb, there was used tensorflow to build a convolutional neural network. 
### Conclusion:
The trained, self built network has got strong opponents on kaggle, using CNNs, convolutional neural networks. The accuracy of the competitive prediction is 90,492 %. 
This seems pretty good on the first glance, however in comparison to other competitors, using advanced toolbox methods, the accuracy can be enhanced dramatically.

The convolusional neural network built with tensorflow performs much better and reaches an accuracy of 96.5%. 
