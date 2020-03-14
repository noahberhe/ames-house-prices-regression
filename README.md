# Ames House Prices
<img src="http://imgur.com/1ZcRyrc.png" width="60">

## Introduction
You have just joined a new "full stack" real estate company in Ames, Iowa. The strategy of the firm is two-fold:
- Own the entire process from the purchase of the land all the way to sale of the house, and anything in between.
- Use statistical analysis to optimize investment and maximize return.
The company is still small, and though investment is substantial the short-term goals of the company are more oriented towards purchasing existing houses and flipping them as opposed to constructing entirely new houses. That being said, the company has access to a large construction workforce operating at rock-bottom prices.

## 1. Estimating the value of homes from fixed characteristics
Develop an algorithm to reliably estimate the value of residential houses based on fixed characteristics.

## 2. Determine any value of changeable property characteristics unexplained by the fixed ones
Identify characteristics of houses that the company can cost-effectively change/renovate with their construction team.

## 3. What property characteristics predict an "abnormal" sale?
Evaluate the mean dollar value of different renovations.

## Overall Approach

## Data Pre-processing
- Cleaning and Feature-Engineering of data
- Identify fixed vs changeable features
- For the 3rd step, my first use of SMOTE to address class imbalance.

## Modelling
- Linear Regression used to regress vs fixed characteristics, with Regularizaion to effectively remove unimportant features and colinearity
- Isolate residuals and model those separately as being influence by changeable features

## Evaluation
- Evaluate coefficients for reasonableness
- Train a model on pre-2010 data and evaluate its performance on the 2010 houses.
