# PRML-Project
This repository contains the .ipynb files and the report of our project for the course Pattern Recognition and Machine Learning, taught in the Fall Semester in Aristotle University of Thessaloniki.
> Course Professor: Panagiotis Petrantonakis 

# Description
This assignment is part of the Pattern Recognition & Machine Learning course and consists of four main Parts, each focusing on different Classification Algorithms.

# Part A: ML Classifier
This part involves the development of a Maximum Likelihood (ML) classifier to recognize stress in users of a video game, based on data derived from button pressure patterns. The goal is to evaluate the reliability of the variable x. This evaluation is based on data from 12 users, 7 of whom did not feel stressed and 5 felt stressed.

# Part B: Bayesian Classifier
This part comes as an extension of part A. We implement a Bayesian Classifier and estimate the unknown parameter theta.

# Part C: Decision Tree compared to Random Forest Classifier
Using the Iris Dataset from the sklearn library we implement a Decision Tree Classifier and a Random Forest Classifier and we compare, among other characteristics of each classifier, the maximum depth of each one and decide which classifier is more optimal.

# Part D: Classification Algorithm Development
Training Set: datasetTV.csv:
8743 samples with 224 features per sample, followed by a label (1,...,5) in the last column.
Test Set: datasetTest.csv:
6955 samples without provided labels.
The goal of this Part is to try out a variety of classifiers, train them using the training set and validate them using the Test Set to determine which one works better with our data. In the end we produce a .npy file with the labels of the Test Set that the Classifier provided us with.
