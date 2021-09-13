# Analyze A/B Test Results
##  Project Overview

A/B tests are very commonly performed by data analysts and data scientists. It is important that we get some practice working with the difficulties of these

In this project, we worked to analyze the results of an A/B test run by an e-commerce website. 
we goal is to work through the notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

**By going through three main parts as below:**
- Part I - Probability
- Part II - A/B Test
- Part III - Regression

## Statistical Analysis Scope

- Bootstrapping sampling distributions
- P-value and Z-score calculation
- Logistic regression

## Results
In the final analysis, based on the entire project and the overall result:
- we don't have sufficient evidence to indicate that the new page in more conversions rate than the old page.
- we cannot to reject the null hypothesis. 
It may be the best idea to keep the old page to run the experiment a little longer and afterwards provide the test results, this will save time and money to create a new page.


## File Description

```
Analyze_ab_test_results_notebook.ipynb : Jupyter Notebook file containing project code
Analyze_ab_test_results_notebook.html : Another version in html file containing project code
ab_data.csv : The original dataset of the project
countries.csv : Additional dataset for the project
README.md : This file, describing the contents of this repository
```

## Installation
We will install the following Python libraries for facilitate of analysis:

```
pandas
numPy
matplotlib
statsmodels
```
> It will be recommend to installing Anaconda, which comes with all of the necessary packages.

## Run
To run this project navigate to project directory in terminal and then use following command.

```
jupyter notebook Analyze_ab_test_results_notebook.ipynb
```

## Licensing and Acknowledgements
This project was presented as part of the Data Analyst Nanodegree Program at Udacity.
