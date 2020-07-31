# Feature_engineering
Feature Engineering in Python using Featuretools
manual feature engineering is a tedious task and is limited by both human imagination - there are only so many features we can think to create 
and by time creating new features is time-intensive. 
Ideally, there would be an objective method to create an array of diverse new candidate features that we can then use for a machine learning task. 
This process is meant to not replace the data scientist, but to make her job easier and allowing her to supplement domain knowledge with an automated workflow.

In this notebook, we will walk through an implementation of using Featuretools, an open-source Python library for automatically creating features with relational data 
(where the data is in structured tables). Although there are now many efforts working to enable automated model selection and hyperparameter tuning, there has been a lack of 
automating work on the feature engineering aspect of the pipeline. This library seeks to close that gap and the general methodology has been proven effective in both machine 
learning competitions with the data science machine and business use cases.
