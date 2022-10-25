# ML-functionalities
Python programs that automate data processing, dataset generation and analysis tasks 

**1. Base_CREATE_DATASET:** is python program that generates a dataset using simulation 
- meant for people who want to practice ML code on simulated datasets but do not want to go through the pain of generating a dataset from scratch
- simply call the create_dataset() function - answer a few basic questions that the program asks - and you have your dataset ready in a neat Pandas DataFrame format


**2. Base_VARIABLE_CLUSTERING:** is a python program that addresses the issue of variable redundancy in Machine Learning. 
- Variable redundancy refers to the presence of similar families of variables, or clusters of highly correlated variables in a dataset. 
- Similar variables do not contribute any significant predictive power to a model - hence there must be a way to eliminate these similar variables and select one variable from each cluster that best represents the cluster of similar variables. 
- This is done using the VARIABLE CLUSTERING algorithm that uses Principal Component Analysis to create clusters of similar variables and then uses a ratio of within cluster and cross cluster correlation to determine the best representative variable in each cluster. 
