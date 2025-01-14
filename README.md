# About Data set( Green Destinations)
Green Destination is a well known travel agency. The HR Director has recently noticed an increase in employees leaving (attrition).She would like to figure out any trends or patterns. She has surveyed the staff of Green Destinations and provided us the data.
# Project overview
HR would like to know what the attrition rate i.e % of people who have left.And she would also like to know if factors like age, years at the company and income play a part in determining if people will leave of not.
# Aim of Project
To help a company understand the attrition in their organization to minimize the attrition rate,so that turnover costs are reduced and employess can be retained for a longer period. To explore the dataset and it's different features understand the relationship between the different variables Find the variables that tend to have a larger number of employess with attrition.
# Analysis Conclusion :
# ### Top Reasons why Employees leave the Organization:
1. No Overtime This was a surpirse, employees who don't have overtime are most likely to leave the 
    organization. This could be that employees would like to have a higher amount of income or employees could 
     feel that they are underused.
 2. Monthly Income: As expected, Income is a huge factor as why employees leave the organization in search for
   a better salary.
3. Age: This could also be expected, since people who are aiming to retire will leave the organization.

Knowing the most likely reasons why employees leave the organization, can help the organization take action and reduce the level of Attrition inside the organization.
We have constructed a very simple pipeline of predicting employee attrition, from some basic Exploratory Data Analysis to feature engineering as well as implementing three learning models in the form of a K-Neighbors Classifier, Random Forest and a Gradient Boosting classifier. This whole notebook takes less than a minute to run and it even returns a 87% accuracy in its predictions.
That being said, there is quite a lot of room for improvement. For one, more features could be engineered from the data. Furthermore one could squeeze performance out of this pipeline by perhaps using some form of blending or stacking of models. I myself am quite keen to implement a classifier voting where a handful of classifiers votes on the outcome of the predictions and we take the majority vote.
