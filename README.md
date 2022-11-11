# Music-Recommendation
Machine learning group project for CPT_S 437.
## Introduction
Recommenders systems are very common in our everyday lives from online shopping to youtube recommendations or spotify recommendations through their song radio feature. 
The objective of our project is to create a recommender system that will be trained to recommend new artists to users based on their preferences and past listening experiences. The trained model will then be validated for random users to generate accuracy, precision and recall metrics.
From our research we have discovered that there are 2 main types of recommender system content based and collaborative.Content based uses item features to recommend other items similar to what the user likes. Collaborative filtering uses similarities between users and items simultaneously to provide recommendations.

## Our method
We build a collaborative filtering model, by first using K-nearest neighbors which will provided recommendations based 10 nearest neighbors to any input artist. We also used matrix factorization to alleviate an issue we discovered. We implemented matrix factorization by decomposing user-item inetraction matrix into the product of 2 lower 2d matrices. we used tensorflow to denote the user and artist matrices and used the loss function for matrix facorization to minimize error between predicted and the actual values.

## Dataset
dataset:https://grouplens.org/datasets/hetrec-2011/
