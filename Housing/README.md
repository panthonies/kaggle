# Predicting House Sale Prices in Ames, Iowa

This is one of Kaggle's popular beginner competitions, where the goal is to create a regression model to predict the final sale price of residential homes in Ames, Iowa. Details on the competition can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/).

For my submission, I created a weighted ensemble of 4 models: MARS (multivariate adaptive regression splines), elastic net, polynomial SVM, and GBM (stochastic gradient boosting).

Files in this folder:
- *analysis-housing.Rmd:* source code for data analysis and modeling (written in R markdown)
- *train.csv:* training data
- *test.csv:* test data
- *submission.csv:* my submission

My submission scores in the top 13% (as of May 2020). [**View the final HTML rendering of my analysis here**](https://anthonypan.com/kaggle/housing).