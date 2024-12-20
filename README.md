# Algorithms and Insights 
This repository is designed to showcase my skills in developing Algorithms that extract insights from structured and unstructured data. Below is a description of each file contained in this repository 

**1. 2019DMB02_AkashGupta_Dissertation:** is a document that describes my postgraduate dissertation project. 
- Contains a description for Sentiment Analysis methodologies for analyzing product reviews on E-commerce platforms.
- In this project, I developed algorithms for computation of sentiment intensity scores and sentiment 
classification for text data. Concepts applied: Tokenization, Regular Expressions, word-
vectorization, Sentiment Lexicons, Cosine similarity, N-gram analysis, Naïve Bayes 
classification.

**1. Base_CREATE_DATASET:** is python program that generates a dataset using simulation 
- Meant for people who want to practice ML code on simulated datasets but do not want to go through the pain of generating a dataset from scratch
- Simply call the create_dataset() function - answer a few basic questions that the program asks - and you have your dataset ready in a neat Pandas DataFrame format


**2. Base_VARIABLE_CLUSTERING:** is a python program that addresses the issue of variable redundancy in Machine Learning. 
- Variable redundancy refers to the presence of similar families of variables, or clusters of highly correlated variables in a dataset. 
- Similar variables do not contribute any significant predictive power to a model - hence there must be a way to eliminate these similar variables and select one variable from each cluster that best represents the cluster of similar variables. 
- This is done using the VARIABLE CLUSTERING algorithm that uses Principal Component Analysis to create clusters of similar variables and then uses a ratio of within cluster and cross cluster correlation to determine the best representative variable in each cluster. 


**3. INTERACTIVE_STRATIFIED_SAMPLING:** is an interactive python function that implements stratified sampling on your population dataset (
can be used only for ML applications where response variable is binary). 
- It first tells you the event rate in the population.
- Then it asks you the total sample size you are looking for and the event rate you want in the sample. 
- Then it asks you to enter the variable by which you want to stratify the sampling. 
- Implements the sampling and provides the output sample data. 


**4. META_DATA_CALC:** is a python function that calculates essential meta data and summary information about your dataset. 
- Before beginning any Data Science project, it is essential to know basic information like:
  - Variable names 
  - Data Types of the variables (how many numeric/character variables are present)
  - Summary statistics of the numeric variables 
  - Percentage of missing values in each variable 
- All these measures are calculated using this function
