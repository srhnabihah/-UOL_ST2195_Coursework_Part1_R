ST2195 Coursework: Programming for Data Science 
-

This coursework covers two parts: 

Part 1: Metropolis-Hastings Sampler
- 
- Draws samples from a Laplace distribution using Random Walk Metropolis
- Runs 4 independent chains and uses the R-hat diagnostic to assess convergence across a grid of 1000 proposal standard deviations
- ***Result*** : Monte Carlo estimates closely match the theoretical mean (0) and standard deviation (√2≈ 1.414) in both R and Python

Part 2: Flight Delay and Diversion Analysis
- 
Using US domestic flight data from 2004 to 2008, this part answers three questions:
1. Best time and day to fly: Which times and days of the week have the lowest average delays?
2. Plane age: Do older planes experience more delays?
3. Diversions: Which factors predict whether a flight is diverted? (logistic regression,fitted per year)

***Key Findings***: 
- Delays are lowest between 0400 and 0800,and on Saturdays
- Plane age alone is not a reliable predictor of delays
- Distance is the strongest predictor of diversion risk

Requirements
-
- R: data.table, ggplot2, patchwork, broom
- Python: pandas, numpy, scipy, matplotlib, seaborn, scikit-learn

Data
- 
Downloaded the yearly flights CSVs (2004-2008), plus plane-data.csv, airports.csv, and carriers.csv, from the 2009 ASA Data Expo.
