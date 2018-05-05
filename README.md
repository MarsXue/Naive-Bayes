# ML-Project1
Project 1 for COMP30027 Machine Learning 2018

---
### Project Detail
Implementation of both supervised and unsupervised Naive Bayes classifiers

---
### Dataset Detail
- breast-cancer.csv
	- 286 instances
	- 9 nominal attributes
	- 2 classes: no-recurrence-events / recurrence-events
- car.csv
	- 1728 instances
	- 6 nominal attributes
	- 4 classes: acc / unacc / good / vgood
- hypothyroid.csv
	- 3163 instances
	- 18 nominal attributes
	- 2 classes: hypothyroid / negative
- mushroom.csv
	- 8124 instances
	- 22 nominal attributes
	- 2 classes: e (edible) / p (poisonous)

---
### Function Implementation
- train()
	- calculate counts (or probabilities) from the training data to build a model
- predict()
	- use the model from train() to predict a class from the test data
- evaluate()
	- output the evaluation metric or sufficient information

