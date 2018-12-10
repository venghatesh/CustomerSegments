# Machine Learning Engineer Nanodegree
# Unsupervised Learning
## Project: Creating Customer Segments

## Project Overview
In this project unsupervised learning techniques is applied on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. we will first explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, we will preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, we will apply PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. Finally, we will compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

## Project Highlights
This project is designed  towards developing conclusions for a potential client on a real-world dataset. Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information we can assist a company engineer future products and services that best satisfy the demands or needs of their customers.

Things done as part of  this project:

- Applying preprocessing techniques such as feature scaling and outlier detection.
- Interpreting data points that have been scaled, transformed, or reduced from PCA.
- Analysing PCA dimensions and construct a new feature space.
- Optimally cluster a set of data to find hidden patterns in a dataset.
- Assess information given by cluster data and use it in a meaningful way.

## Description
A wholesale distributor recently tested a change to their delivery method for some customers, by moving from a morning delivery service five days a week to a cheaper evening delivery service three days a week. Initial testing did not discover any significant unsatisfactory results, so they implemented the cheaper option for all customers. Almost immediately, the distributor began getting complaints about the delivery service change and customers were canceling deliveries, losing the distributor more money than what was being saved. we've been hired by the wholesale distributor to find what types of customers they have to help them make better, more informed business decisions in the future. our task is to use unsupervised learning techniques to see if any similarities exist between customers, and how to best segment customers into distinct categories.

## Software and Libraries
This project uses the following software and Python libraries:

- [Python 3.0 (https://www.python.org/download/releases/3.0/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- seaborn (https://seaborn.pydata.org/)




## Project Files


This project contains three files:

- `customer_segments.ipynb`: Main Python file containing unsupervised ML code. 
- `customers.csv`: The project dataset. 
- `visuals.py`: This Python script provides supplementary visualizations for the project. 

