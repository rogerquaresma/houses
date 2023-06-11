In this project, we are going to work on the problem proposed by the [House Prices competition on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data): to build a model to predict house prices based on its features.

The **data** we are going to look at is the Ames Housing Dataset, which includes 81 features describing a wide range of characteristics of 1,460 homes in Ames, Iowa sold between 2006 and 2010.

Price prediction is a machine learning regression problem where the goal is to predict a continuous value. To address it, we are going to use **XGBoost (eXtreme Gradient Boosting)**, a popular and efficient open-source implementation of the gradient boosted trees algorithm. Gradient boosting is a supervised learning algorithm that attempts to accurately predict a target variable by combining an ensemble of estimates from a set of simpler and weaker models.

Since the database include categorical features (i.e. text), missing values and numerical features of varying scales, we are doing to dedicate some time to **data preparation** before we get to our model. We'll organise these steps in a pipeline to automate and optimize this process.
