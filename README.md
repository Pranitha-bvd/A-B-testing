# A-B-testing
A/B testing is one of the most important tools for optimizing most things we interact with on our computers, phones and tablets. 
From website layouts to social media ads and product features, every button, banner and call to action has probably been A/B tested. And these tests can be extremely granular; 
Google famously tested "40 shades of blue" to decide what shade of blue should be used for links on the Google and Gmail landing pages.

## This project: 
Implements A/B Testing in Python to analyze the effectiveness of a new webpage design compared to an old version. 
The goal is to determine if the new design leads to a statistically significant improvement in user conversions.
* Compares two versions of a webpage: Control (old page) vs. Treatment (new page).
* Uses statistical hypothesis testing to evaluate conversion differences.
* Determines whether to adopt the new design based on statistical significance.

## Key Features

* Data Cleaning & Preprocessing: Handles incorrect assignments and duplicate users.
* Exploratory Data Analysis: Computes conversion rates for each group.
* Sample Size Calculation: Uses power analysis to determine the minimum users needed per group.
* Statistical Hypothesis Testing: Conducts a Z-test to evaluate the significance of conversion rate differences.
* Confidence Interval Estimation: Measures the reliability of the results.
