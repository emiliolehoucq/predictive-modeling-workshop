# Statistical Learning (Predictive Modeling) in R

Over the course of three days, we'll be covering some basics of statistical learning or predictive modeling. We'll cover shrinkage methods (Lasso and Ridge regression), tree-based methods (boosted trees and random forests), and single-layered neural networks. We'll focus on how to implement the methods in R, rather than the methods themselves. You should at least know the methods. 

I'll show how to implement them for regression. However, the classification version is easy to change and I included notes on how to do it.

At the same time, we'll cover model tuning and validation--some days through a validation set approach and k-fold cross validation. Some days we'll use for loops, while others we'll use map functions. To get the full set of skills (which you can also use with other methods), you'd need to attend the three days.

## Software

You'll need R and XXXXX.

We'll be using the last version of R and all of the packages. Please make sure they are updated.

## Data

We'll be using the [Online News Popularity Data Set](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) and the [clickstream data for online shopping Data Set](https://archive.ics.uci.edu/ml/datasets/clickstream+data+for+online+shopping) from the UCI Machine Learning Repository. Since they have a quite large number of observations to run models during the sessions, we'll take subsamples of them, as indicated in the lecture notes.

## Resources

For a brief overview of different topics, you can check out [Towards Data Science](https://towardsdatascience.com/). I recommend [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/). For a more detailed and technical coverage, [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/). Both of these books are free online.

## Authorship

The helper functions for the boosted trees are taken from Arend Kuyper's Data Science Manual.
