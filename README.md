# Home-Credit-Loan
The data we analyzed can be found here: https://www.kaggle.com/c/home-credit-default-risk/data 

The objective of this analysis is to use historical loan application data to answer the following questions.
- What factors will affect how much an individual is approved for?
- How does a previous application affect your loan amount?
- Which loan purpose, increase or decrease the amount difference?
- What start time of application, increase or decrease the amount difference?

We started by gathering all the data from each data set and combining it together to make it one big data set. All together the data was about 2.5 GB and as you may know, this is very big data. We took a sample of this data to allow our models and analyzing easier and more efficient. 

We started by building a random forest regression model to predict the difference between the amount a client applied for and the amount they actually received. A Random forest regression uses ensemble learning that combines predictions from multiple machine learning algorithms to make more accurate predictions than a single model. We chose this model because our target variable was not a classifier, instead it was a continuous variable.

This analysis was meant to provide recommendations for clients to be able to get the full amount on a loan that they need. We hope our recommendations are helpful and serve anyone well during these hardship times.
