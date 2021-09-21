# Project 2 - Ames Housing Data and Kaggle Challenge

# OUTILNE
1. Import data from train and test
2. Check for null values both datasets at the same time(train and test)
3. Drop columns that have more than 50% of missing items(train and test)
4. On columns with less than 200 values as null populate(train and test)
5. I use mean to populate the int and float values(train and test)
6. I use mode to populate on the object values(train and test)
7. Create heat maps and scatter plots in order to get a better glance of the data(train)
8. Create dummy variables for the categorical variales(train and test)
9. fill null variables with zeros just in case the dummy functions would create NAN values
10. Set X with all numerica data excluding the variables that are not related to sales price.
11. Set our y target variable which is 'sales price'
12. Create X_train, X_val, y_train, y_val which will help us train and test our model.
13. Create a Linear Regression Model
14. Fit the model
15. Get the score on the train data
16. Get the score on the test data.
17. Get the r2 score on the test data
18. If pleased with the model test the test.csv data set
19. if not revise the model
20. save the predictions into a csv file
21. Submit prediction to Kaggle

# The dataset train and test

https://www.kaggle.com/c/dsi-ames/data

# Project Statement

1. Whys is so important to get an accurated prediction of the data set?
   House Price prediction, is important to drive Real Estate efficiency. 
   In earlier years, House prices were determined by calculating the acquiring and selling price in a locality. Therefore, the House Price    
   prediction model is very essential in filling the information gap and improve Real Estate efficiency.
   
# What are the strongest correlations that sale price has with other features of the dataset?

![alt text](Projects/project_2/1.png)

![alt text](Projects/project_2/2.png)

![alt text](Projects/project_2/3.png)

![alt text](Projects/project_2/4.png)

# How did our model performed?

![alt text](Projects/project_2/5.png)

-We got an 87% prediction in our model

