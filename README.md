## Project Purpose

Using the dataset of home prices in Ames, Iowa taken from kaggle.com, we used machine learning models such as: penalized linear regression, simple linear regression, and random forest regression to predict future home sale transaction prices.  Additionally, we were able to interpret these regression models to provide homeowners a roadmap of renovations and improvements to maximizing their home value.

## Project Guidance

The Machine Learning Project - Final notebook is our “production” ready file.  We kept some of the older files around to document the major changes in model selection and tuning for easy comparison.  The Final notebook walks users through data cleaning, standardization, feature engineering and EDA in general.  It retains commented out sections of various tuning methods we tried that didn’t make the final cut.

In the regression models section we run both ElasticNet and Random Forest models against the data to help us pare down to the most important features.  We were able to gather the most important features in common to focus on for our business model.  We also generate Kaggle submission files to see how well we do against the Test data for each model.

Finally we have a Results Exploration section where we look into the relative added value for various feature to a house.  We also explore which houses our model was not able to accurately predicate prices for and tried to see if we could reduce those residuals in any way.
