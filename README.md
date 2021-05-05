# AB Testing

## Project Overview
For this project I performed A/B tests on an e-commerce website. The goal is to understand and correctly interpret the results in order to advise the company if they should implement a new website or keep the old one. 

## Techniques and model used:

- Probability and Bayes Rule
- State Research question
- State Null and Alternative Hypothesis
- Simulate under null for 10,000 samples using Law of Large Numbers and binomial distribution method
- Stating confidence interval
- Calculating mean from null hypothesis and actual (observed) mean
- Using z-test and p-value model form `statsmodels.api` to interpret results
- Using logistic regression model to predict binary outcomes
- Higher order terms and interactions

## Result and Charts from Analysis 
 Comprehensive analysis for AB Testing can be found in [HTML file](Analyze_AB_test.html) or [ipynb file](Analyze_AB_test.ipynb)

<p align="center">
<img src="Visuals/Distribution_of_differences.png" width="55%" height="55%"> </p>

<p align="center">
<i>Figure 1: Distribution of differences for 10,000 samples, difference between observed mean and mead from the null and boundaries for 95% confidence interval</i>
</p>


<p align="center">
<img src="Visuals/Distribution_of_simulation.png" width="55%" height="55%"> </p>

<p align="center">
<i>Figure 2: Distribution of simulation for 10,000 samples binned in 50 bins, standard deviations, z-score and critical value area.</i>
</p>


