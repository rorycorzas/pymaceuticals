
# pymaceuticals-challenge

Aurora Perez Corzas. Data Analytics, 2023. Tec de Mty & EdX Bootcamp

* This files corresponds to the 5th project, the Matplotlib challenge. 

* Github Repository link: https://github.com/rorycorzas/pymaceuticals-challenge

* Background

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

* Dependencies and Setup
import matplotlib.pyplot as plt
import pandas as pd
import scipy.stats as st
import numpy as np

* Tasks

This assignment is broken down into the following tasks:

Prepare the data.
Generate summary statistics.
Create bar charts and pie charts.
Calculate quartiles, find outliers, and create a box plot.
Create a line plot and a scatter plot.
Calculate correlation and regression.
Submit your final analysis.

# Pymaceuticals Inc., by Aurora Perez Corzas.
### Analysis

Note: The analysis was also commited at the begining of the Jupyter Notebook code.

It appears that Capomulin & Ramicane are the most effective drugs (in the set of drugs selected to make the study) to take control over the increment in the size of the Mean Tumor Volume.

Also, we can observe by the statistical results, that the variance using the Capomulin & Ramicane (in the range of time that the study was considered) are the drugs that present less variability over time in reference to the other tested drugs, it has a positive value which means that the Mean Tumor Volume has increased but in a less proportion. 

Regarding the overall values of mean, median and variance, Ramicane appears to be the successfull of all. 

It is also important consider that this study was made in a lapse we are not aware of (it is not available in the data) So, this results cannot be considered conclusive in effectiveness considering the tested drugs. It exist the possibility that exist more effective drugs in a long term basis. 

The final comment is about the worst behaviored drugs. In this subject, Ketatpril and the placebo have less effect directly on the contention on the Mean Tummor Volume. This means that the mice using one of these testing methods suffer a general increment in the size of the Tummor and the metastatic sites over the time. 
