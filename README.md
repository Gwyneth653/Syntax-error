# Syntax-error

### Group members: Veerle Blom, Paul van der Wolde and Gwyneth Pechler
### Project 6: Housing prices

## Introduction
Given a provided dataset with 1460 houses and their sales price. We build a model to accurately estimate the values of houses in Ames Iowa.
We build roughly 4 different models to compare which model was most suitable for our problem. These 4 model codes can be find in the "code" folder under "correct data". We also included a "data_prep" file which contains the steps we undertook to prepare the data before implementing in a model. 
The folder "data" includes all the data retrieved from the Kaggle website. The files contain a "train" file which contains the data of 1460 houses in Ames Iowa on which all our models are trained and tested on.
Lastly, there is a folder "wrong_data" in the folder "code" which contains code we wrote trained and tested on the wrong data. 

### Model 1: univariate and multivariate linear regression model
In this code we will show the steps we took to design a univariate linear model for 3 features of our dataset seperately, and a multivariate model in which those 3 features were combined in one model. Those 3 features were chosen by the fact that they had the highest correlations with the sales prices. 

### Model 2: univariate and multivariate polynomial regression model
In this code we will show the steps we took to design a univariate polynomial model for those same 3 features as model 1, and again those 3 features combined in a multivariate polynomial regression model. 

### Model 3: Random Forest/Tree Regressor model
In this code we will show 3 seperate models, all trained on all the features in our data. The first model describes a single decision tree regressor, the second a random forest regressor and the last model describes an extra tree model. 

### Model 4: Neural Network
In this code we will show the design of our final model to predict housing prices. We coded a neural network with all the features and one with 92 features. This model resulted in the best model compared to models 1, 2 and 3. 
