# Image Processing with Artificial Intelligence 
This task is application of AI on Image processing using Python. The aim is to modify the lfw_people datasets in sklearn in different ways with different learners, and give a conclusion on the most accurate learner. The learner in the initial datasets was replaced with some Supervised and Unsupervised machine learning models to determine this. 

## Introduction
Image processing is one of the key part of Artificial Intelligence. This can be applied in different ways ranging from identification of patterns in images, AI aided medical disgnosis, fraud detection, security and surveillance etc. 


## Objective of the Project
This project aim to fecth and modify the lfw_people datasets contained in sklearn library - https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_lfw_people.html by utilizing the following supervised and unsupervised machine learning models;

i. Random Forest Classifier

ii. Multilayer Perceptron

iii. Deep Convolutional Neural Network

iv. KMeans Clustering.

The outcome of the application of these different models are given below.


## The results of the application of the Models:

i. **Random Forest Classifier** ---> Gave an accuracy of 63%. https://github.com/Riabdulm/Image-Processing-with-AI/blob/c67cd6203c09c5a856feb4f4753c8aebbbf066ed/random-forest-classifier.ipynb 

ii. **Multilayer Perceptron** ---> Gave an accuracy of 71%. https://github.com/Riabdulm/Image-Processing-with-AI/blob/c67cd6203c09c5a856feb4f4753c8aebbbf066ed/multilayer-perceptron.ipynb

iii. **Deep Convolutional Neural Network** ---> Gave the highest accuracy at 88%. https://github.com/Riabdulm/Image-Processing-with-AI/blob/c67cd6203c09c5a856feb4f4753c8aebbbf066ed/deep-convolutional-neural-network.ipynb

iv. **KMeans Clustering** ---> The unsupervised KMeans clustering gave the lowest accuracy at 18%. https://github.com/Riabdulm/Image-Processing-with-AI/blob/c67cd6203c09c5a856feb4f4753c8aebbbf066ed/kmeans-clustering.ipynb


## Conclusion

Convolutional Neural Network (CNN) gave the best accuracy as they are more suited to images because neural network exploits geometric regularities that are found in images. On the other hand, KMeans clustering produced the least accuracy as unsupervised machine learning has no prior information about the dataset.


