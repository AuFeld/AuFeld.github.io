---
layout: post
title: Naive Bayes Classifier
subtitle: An Algorithm from Scratch
cover-img: 
gh-repo: AuFeld
tags: [algorithm, naive bayes]
---

## Why Naive Bayes Classifier?

I decided to use the Naive Bayes Classifier as my CS Build because I was able to relate to it and be able to utilize
it in a way that I understood. I wanted to be able to find the likelihood of an event to occur. When I came across the 
UCI data set for student performance, I knew that I would be able to identify a problem that I could solve with NBC.

## Breakdown of Code

After studying the NBC algo, and using UPER, I was able to identify the necessary methods needed for the algo: making 
predictions, getting the accuracy, calculating the mean and variance, and splitting the data set. 

## Splitting the Dataset

A necessary function to split the data set into a training and testing. The training set is the set used to train the 
algo and store the results to be tested on the test portion of the dataset with a 80/20 split. 

## Split by Class

Splitting by class was essential to the algo to identify successful and unsuccessful targets. By identifying the passing 
grade with a 1 and a not passing grade with a 0, we were able to identify positive and negative results in the algo.

## Defining the Mean and Variance

Two essential statistics for NBC, mean and variance. By creating a loop to traverse the columns, the algo was able to 
establish and store both the mean and variance for both passing and not passing grades in the dataset.

In lehman's terms the mean is defined as sum(x)/n * count(x). Where x is the list of values or a column. The standard 
deviation is calculated as the mean difference from the mean value. Standard deviation is defined as 
sqrt((sum i to N(x_i-mean(x))^2)/N-1). You can see that we square the difference from the mean, then take the square 
root to return the units back to their original value.

A tree traversal was chosen because I wanted the algo to visit each node only once, in order, in the data structure. 
The traversal is classified by the order in which the nodes are visited.

## Making Predictions

Probabilities are calculated separately for each class. This means that we first calculated the probability that a new 
piece of data belongs to the first class, then calculates the probabilities that it belongs to the second class and then 
stores it in a dictionary. 

## Modeling

After loading in the dataset, the features with high cardinality were dropped to reduce the noise of our model. The next 
step was to establish which grades were considered passing (greater then or equal to 70%) and not passing (less then 70%), 
then identifying which student was passing their course with a 1 for passing and a 0 for not passing. An initial 
probability was calculated to establish a baseline to compare our results to by simply identifying which students 
actually passing their course with a 71% baseline. 

The next step, I had to implement the mean, variance, and calculate methods for each class (passing and not-passing 
grades). The next step was to calculate the predictions and then utilize the get accuracy method to determine the 
accuracy, precision, and recall of the algo that I created. 

## Conclusion

With an accuracy score of 56%, I was 14.92 basis points below the establish baseline of 71%. A disappointing result. 
One of the major factors has to be from dropping the features with categorical variables in the dataset. And by doing 
so I lost pertinent features that were essential to the accuracy of the naive bayes algo.

[My Code](https://github.com/AuFeld/Student_Performance)