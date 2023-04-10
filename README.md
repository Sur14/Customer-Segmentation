# Customer-Segmentation
Customer Personality Analysis using clustering Algorithm


The project aims to agglomerate the customers of a company selling various products
based on ideal attribute(s) to summarize the market segmentation. Here, market
segmentation refers to grouping prospective consumers that share common demands and
respond to marketing actions in a similar way, into segments. It allows businesses to
target different types of customers who value particular products and services
differently.

The entire project has been implemented in Intel API using Jupyter Labs. 
- daal4py was used to implement the KMeans algorithm
- sklearnex was patched for the rest of the work

The goal of this analysis will be to allocate all customers into certain
brackets, depending on age, family, income, that will define the products they buy, the
amount they spend, and the deals they settle for, to:
1) promote only those offers to them, in the future, that they will be interested in
2) predict buying habits of new customers
3) adapt the website and catalog in a way that makes it viable for target customers
4) and attract new customers

Another aspect of this project is prediction of the incomes of customers. After clustering 
the dataset, we use the mean incomes of the clusters to predict for customers whose 
income attribute was missing.
