PCRegression
============

Linear prediction using Linear Regression, PCR and Ridge Regression

    Consider the Auto-mpg dataset from UCI repository. You can download the dataset
    from UCI repository http://archive.ics.uci.edu/ml/datasets/Auto+MPG. 
    Ignore the categorical attribute(car name). It has few missing MPG entries, ignore such
    record from the dataset.

      1.We'll implement traditional multi variate linear regression to predict the value of
        mpg (miles per gallon) for a given set of test attributes.

      2.We'll then repeat the same problem using Principal Component Regression and Ridge
        Regression

      Example: Given the <8 307.0 130.0 3504. 12.0 70 1> attributes, what is the predicted value of mpg?

      Divide the dataset into the following training and test sets
        
        Training: 80%
        Test : 20%
