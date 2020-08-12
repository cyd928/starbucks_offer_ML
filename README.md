# Starbucks Offer Machine Learning Project

## Motivation

To understand the business insights behind the data of Starbucks customers and see how data could help provide recommendations to business decisions and predict customer behaviour.


## Objective

* investigate the offer response stats of the sample customers
* identify the demographic groups for customers who respond to the viewed offer
* build a machine learning model to predict whether a customer will respond to an offer


## Libraries used

* Data Wrangling tools: _numpy, pandas_
* Visualisation tools: _matplotlib, seaborn_
* Modelling tools: _sklearn.ensemble, sklearn.model_selection, sklearn.metrics_


## Files 

* data: raw data used for the analysis and modelling
* README.md: description of the project
* Starbucks_Capstone_notebook.ipynb: main script for the analysis and modelling


## Analysis 

The script for this analysis can be found in Starbucks_Capstone_notebook.ipynb via
https://github.com/cyd928/starbucks_offer_ML


## Result 

Blog post to discuss the result of this analysis can be found via
https://medium.com/@chenyudan0928/data-driven-insights-into-customer-behaviour-towards-starbucks-promotional-offers-6e2ae9cd13fd

#### Some Key Insights of the Results:
* 37.7% of the customers viewed the offer sent, of which 95.2% responded to the offer. 
* There appears to be no major difference in age for customers responded/did not respond to the offers. 
* However, customers with longer membership tenure tend to respond to the offers more than those who have lower tenure. This trend is significant across all genders.
* We determine Random Forest Classifier works the best for the data. The model suggests that tenure, difficulty to obtain the offer are the most important features for the prediction.


## Acknowledgements
Owner: cyd928
Project source provided by: Udacity & Starbucks 