# Homework 3 - data transformation & dimensionality reduction (deadline 18. 12. 2022, 23:59)

In short, the main task is to play with transformations and dimensionality reduction to obtain the best results for the linear regression model predicting house sale prices.
  
> The instructions are not given in detail: It is up to you to come up with ideas on how to fulfill the particular tasks as best you can!

However, we **strongly recommend and require** the following:
* Follow the assignment step by step. Number each step.
* Properly comment all your steps. Comments are evaluated for 2 points of the total together with the final presentation of the solution. However, it is not desirable to write novels! 
* Do not leave the task to the last minute.
* Hand in a notebook that has already been run (i.e. do not delete outputs before handing in).

## What are you supposed to do:

Your aim is to optimize the _RMSLE_ (see the note below) of the linear regression estimator (= our prediction model) of the observed sale prices.

**Just copied code from tutorial 3 and 5 will not be accepted.**

### Instructions:

  1. Download the dataset from the [course pages](https://courses.fit.cvut.cz/MI-PDD/homeworks/index.html) (data.csv, data_description.txt). It corresponds to [this Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). 
  1. Transform features appropriately and prepare new ones - focus on the increase in the performance of the model (possibly in combination with further steps). Split the dataset into a train and test part exactly as we did in the tutorials. Use the test part for evaluation of the influence of further steps. _(3 points)_
  1. Try to find some suitable subset of features - first without the use of PCA. _(4 points)_
  1. Use PCA (principal component analysis) to reduce the dimensionality. Discuss the influence of the number of principal components. _(4 points)_
  1. Compare the results of previous steps on the test part of the dataset. _(3 points)_
  
Give comments (!) on each step of your solution, with short explanations of your choices.

All your steps and following code **have to be commented!** Comments are evaluated for _2 points_ together with the final presentation of the solution.

**If you do all this properly, you will obtain 16 points.**

**Note**: _RMSLE_ is a Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sale prices.


## Comments

  * Please follow the technical instructions from https://courses.fit.cvut.cz/NI-PDD/homeworks/index.html.
  * If the reviewing teacher is not satisfied, she can (!) give you another chance to rework your homework and to obtain more points. However, this is not a given, so do your best! :)
  * English is not compulsory.