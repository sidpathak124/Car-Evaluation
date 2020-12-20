# Car-Evaluation
Title:
Predicting the Market potential of cars based on their features

Motivation:
At the time of buying a car, or from seller’s perspective (manufacturing a car), it is required to think about the specs/features of a car. What features will make a car successful in the market? is a prime question in the automotive market. All cars have been divided into four classes based on their market potential (viz. Unaccepted, Accepted, Good or Very Good). 
We want to build a machine learning model that can predict, what class would a new car belong to, based on its features. Such a model can tell us in advance, as to how successful a newly designed car would be. Such a model can also allow the manufacturer to design a car with specific features that has the highest chance of being successful in the market.

About the dataset:
The “Car evaluation dataset was taken from UCI repository.
The dataset contains 1728 samples/instances of different cars. 
Each sample of car has six attributes and a target (‘class): 
'buying/pricing', 'maintenance', ‘number of doors', ‘number of persons', 'lug boot', 'safety‘ and 'class‘.
The output will be a multivariate classification of four classes.

Research Question:
Can we predict with reasonable accuracy if a given car with specific features will be successful in the market or not? If yes then should we choose the predictor model based on supervised or unsupervised algorithm.
Further we also like to probe as to, which model and specifically which parameters, would give the best performance.

Models implemented are:
1) Decision Tree
2) KMeans Algorithm
3) Logistic Regression
4) KNearestNeighbor
5) Random Forest
