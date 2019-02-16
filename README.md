# A-B_Test_for_an_e-commerce_website
This project was completed as part of the course requirements for Data Analyst Nanodegree with Udacity.

# Introduction
A/B tests are very commonly performed by companies to decide whether to launch new features on their website.For this project, we implemented an A/B test for a hypothetical e-commerce website and analysed the results. The company has developed a new web page in order to try and increase the number of paid users.  Our aim is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

# Project Description

The steps included :

Removing duplicate records or records with missing values 
Removing records with mismatched condition and page assignment values
Computing probabilities of converting:
	regardless of page.
	Given that an individual received the treatment
	Given that an individual received the control page
Hypothesis Testing using bootstrapping 
Performing standard statistical tests and calculating p-values
Performing Logistic Regression

# Technologies Used
Python

Libraries: pandas, numpy, matplotlib, StatsModels, Scipy

Jupyter Notebook

# Results
We failed to reject the null hypothesis after A/B testing, that is, we did not have sufficient evidence to suggest that the new page is better than the old page.
