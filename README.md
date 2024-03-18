# Querying CSVs and Plotting Graphs with LLM OpenAI


## Introduction

In this assignment, we explore the process of querying CSV datasets and generating plots based on the obtained results using Language Models (LLMs). We utilize the Langchain framework along with the OpenAI model to interactively analyze a dataset containing information on heart disease risk factors.

## Dataset Description

The dataset used in this analysis is a retrospective sample of males in a heart-disease high-risk region of the Western Cape, South Africa. It includes variables such as systolic blood pressure, tobacco consumption, cholesterol levels, adiposity, family history of heart disease, and more.

## Setup and Installation

We first install the necessary libraries, including Langchain, OpenAI, and other dependencies. Additionally, we set up the OpenAI API key for authentication.

## Exploratory Data Analysis (EDA)


We start by examining the metadata of the dataset, including the number of records and columns.


We display a sample of records from the dataset to understand its structure and content.


We check for any missing values in the dataset and report the findings.


We analyze the probability distribution of the response variable, i.e., coronary heart disease (CHD).


We perform univariate analysis to understand the characteristics of individual variables in the dataset.
- Descriptive Statistics
- Histograms
- Box Plots
- Bar Plots


We identify outliers in the dataset, particularly focusing on the age variable among individuals suffering from CHD.

### Hypothesis Testing

We conduct a hypothesis test to compare tobacco consumption between individuals suffering from CHD and those who do not.

## Bivariate Analysis


We create a scatter plot to visualize the correlation between two numerical variables, such as adiposity and LDL cholesterol.


We calculate the correlation coefficients between various variables and visualize the results using a heatmap.

## Conclusion

In this assignment, we demonstrated how to interactively query CSV datasets, perform statistical analysis, and generate informative plots using LLMs. By leveraging these techniques, we gain valuable insights into the dataset and its underlying relationships.
