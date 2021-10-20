# Statistical Analysis of Amazon Customer Reviews Dataset Web Services S3 

Statistical analysis of Amazon Customer Reviews Dataset as part of a Big Data Mining Course.
Preliminary processing of data:
  •	 Processing text data of Amazon Customer Reviews Dataset by:
    o	Text processing methods and normalization.
    o	Classify Text reviews to positive or negative.
    o	Build a function that processes the explanatory variables before fitting regression model.
Fit a classification model to Big Dataset:
  •	Goal: predict the “binstar” variable using the explanatory variables.
    o	Step One:
  •	Divide the data into train and test. 
  •	Running logistic regression model on one product category train data and check its accuracy index on test data. 
  •	Running logistic regression model on blocks of the same data and averaging the accuracy indices.
  •	Combining models from similar data - Building a combined model by averaging the coefficients of the partial models and checking its accuracy index.
  •	Comparison between the three models.
    o	Step Two:
  •	Preforming the same process on bigger data (10 products categories) and Combining models from different datasets. 
    o	Step Three:
  •	Big Data - Fitting steaming data using Stochastic Gradient Descent.
  •	Dividing the data (the largest categories in the AWS dataset) into batches and running SGD algorithm on each batch individually and checking its accuracy index.
    o	Step Four:
Improving the classifier results by using Gradient Boosting Classifier.
