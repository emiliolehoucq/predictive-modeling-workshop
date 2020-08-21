# Statistical Learning (Predictive Modeling) in R

## Overview

Over the course of three days, we'll be covering some common models in statistical learning/predictive modeling: shrinkage methods (Lasso and Ridge regression), tree-based methods (boosted trees and random forests), and single-layered neural networks. 

We'll focus on how to implement the models in R, rather than the methods themselves. I assume you know the models.

I'll show how to implement the models for regression. However, the classification version is easy to change and I included notes on how to do it.

We'll also cover model tuning and validation--some days through a validation set approach and others through k-fold cross validation. We'll use various tools to implement it. To get the full set of skills (which you can also use with other models), you'd have to attend the three days.

## Software

You'll need R and `tidyverse`, `janitor`, `robustHD`, `skimr`, `ggcorrplot`, `glmnet`, `glmnetUtils`, `ranger`, `vip`, `pdp`, `xgboost`, `nnet`, `caret`, `ALEPlot`.

There are other implementations of some of the models we'll cover in R. I included another package for boosted trees and another for neural networks in the notes.

## Data

We'll be using the [Online News Popularity Data Set](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) for the explanations and the [clickstream data for online shopping Data Set](https://archive.ics.uci.edu/ml/datasets/clickstream+data+for+online+shopping) for the exercises. Since they have a quite large number of observations to run models during the sessions, we'll take subsamples of them, as indicated in the lecture notes.

## Resources

For a brief overview of different topics, you can check out [Towards Data Science](https://towardsdatascience.com/). I recommend [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/). For a more detailed and technical coverage, [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/). Both of these books are free online.
