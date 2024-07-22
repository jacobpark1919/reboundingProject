# reboundingProject

#### Project Summary:  
In this project, we will attempt to predict offensive rebound outcomes in NCAA basketball plays. We have downloaded a dataset from Kaggle.com that includes over 300,000 rows of basketball plays to train our models off of. We have two major goals:  

1.) Explore and understand offensive rebounds  
2.) Train models in order to predict which types of plays will result in an offensive rebound  

We use many different models to predict offensive rebounds ranging from simple models like Logistic Regression and Gaussian Naive Bayes, to more advanced models such as XGBoost, Random Forest, and Convolutional Neural Networks.  

#### Table of Contents:  
1.) Exploratory Data Analysis (EDA) and Data Cleaning  
2.) Simple Modeling/Baseline Model  
3.) Feature Engineering  
4.) More Complex Feature Engineering  
5.) Model Experimentation with Hyperparameter Tuning  
6.) Convolutional Neural Network  
7.) Conclusion  

#### Results:
Here are the log loss of each model that I used  
  
1.) Random Forest - 0.1480  
2.) XGBoost - 0.5088  
3.) Logistic Regression - 0.5745  
4.) CNN - 0.5866  
5.) Gaussian Naive Bayes - 0.8887  

Random Forest was the clear winner in terms of log loss. By taking a look at the table below, it was also the clear winner in terms of accuracy score and in terms of offensive rebound prediction

#### Key Insights:

Here are some key insights that will increase the odds of grabbing an offensive boards:
  
1.) Have many players near the basket  
2.) Be on the opposite side of the shooter  
3.) The further a defensive is from an offensive palyer, the more likely there is to be an offensive board

#### About:
Authors:  
Jacob Park - Rising senior at Boston University studying applied mathematics.  
Thomas Kwon - Rising senior at Stevens Institute of Technology studying computer science.

