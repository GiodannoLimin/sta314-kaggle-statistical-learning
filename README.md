# STA314 Kaggle Competition – Statistical Learning

This repository contains my solution to an in-class Kaggle-style competition
for **STA314H5: Introduction to Statistical Learning** at the University of Toronto.

## Problem
Predict a continuous response variable using 112 predictors.
Performance was evaluated using Root Mean Squared Error (RMSE).

## Result
- Top 2 lowest RMSE among 69 teams (102 entrants)
- Worked individually
- Strict submission limit (2 submissions over 10 days)

## Approach
- Feature screening to identify informative predictors
- Generalized Additive Models (GAMs) using `mgcv`
- Smoothing splines and smooth interaction terms
- Cross-validation to control overfitting

## Files
- `analysis.Rmd`: Full model development and experimentation
- `report.pdf`: Compiled presentation report

## Data
The dataset was provided as part of a course competition and is not publicly shareable.
This repository focuses on modeling strategy and implementation.
