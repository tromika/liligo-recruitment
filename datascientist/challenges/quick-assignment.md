# 2016

### R version
So we're interested how you can solve a minor task on an unknown field with your theoretical knowledge. As I remember you have limited experience with R so now you have to solve a little R task.

Before you start init a repo for this challenge and submit your solution with your other assignment. We would like to check how much time does it take to you so please do it at the same time and don't forget about your last commit.

The task will be the following:

Take the 3 list below and return the Pearson correlation for each pair.  Also print after the correlation coefficient are the lists significantly different from each other or not.

Here is a sample result(the text or the format may differ):

Correlation: 0.9  - No difference


A <- c(1,2,3,4,5,6,7,8,9,10,11,12)

B <- c(1,1,42,3,5,5,45,7,21,9,11,67)

C <- c(12,11,10,9,8,7,6,5,4,3,2,1)

### Python version

So we're interested how you can solve a minor task on an unknown field. To avoid problems with installation and environments etc. we recommend to use an online IDE like ideone.com or something else. Before you start init a repo for this challenge and submit your solution with your other assignment. We would like to check how much time does it take to you so please do it at the same time and don't forget about your last commit.

The task will be the following:

Take the 3 list below and return the Pearson correlation for each pair. Also please interpret correlation coefficients for each pair with predefined sentences. Make sure you avoid errors.

Here is a sample result(the text may differs):

0.9 - Strong relationship


A = [1,2,3,4,5,6,7,8,9,10,11,12]

B = [1,1,42,3,5,5,45,7,21,9,11,67]

C = [12,11,10,9,8,7,6,5,4,3,2,1]


# 2017

Your task is to implement a confidence interval calculation function that inputs a python list or an R vector. You have 60 minutes to complete this task.

Although you are allowed to use any packages, we would like you to implement the confidence interval, the mean, and the standard deviation yourself. The function should return 95% or 90% confidence interval depended on a parameter.

The second part of your task is to apply your function to a list that you see below. We give you the R and python snippet to create the list/vector. As an output just print the results to the console.

## python
```
import random
random.seed(123)
list = []

for i in range(0,8999):
   list.append(random.random())
```

## R
```
set.seed(123)
vec <- runif(8999, 0.0, 1.0)
```
