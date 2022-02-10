# Classification of drug-resistant tuberculosis (DR-TB) and drug-sensitive tuberculosis (DS-TB) using clinical data
This directory contains code for inference using clinical data to predict DR-TB vs DS-TB

load the test data and training data first, then using SVM classifier to perform classification.
testData.mat is the test data with 25 clincial and radiological features.
trainData.mat is the train data with 25 clinical and radiological features.
run testmain.m , you will get the performance such as AUC, accuracy, specificity, sensitivity, precision, etc.
