# COMP0078 Coursework

This document provides an overview of the coursework submissions and detailed feedback for each component. Below, you will find the breakdown for coursework 1 and 2.

---

## Coursework 1

**Coursework Overview**:
The coursework starts with linear regression, fitting polynomial and sinusoidal basis functions, and explores over and under fitting via train/test curves and noise averaged studies. Next is a problem on kernel ridge regression on the Boston housing dataset using Gaussian kernels and cross validation to select hyperparameters and compare against baseline and single feature models. Finally is the implementation of k-Nearest Neighbors, visualising its decision regions, studying how generalisation error varies with _k_ and training set size, and  deriving theoretical guarantees.

**Overall Grade:** 95.00 / 100.00

### Detailed Commentary

- **General Grade:** 88 / 100
- **Q1:** 5 / 5
- **Q2:** 10 / 10
- **Q3:** 5 / 5
- **Q4:** 10 / 10
- **Q5:** 20 / 20
- **Q6:** 5 / 5
- **Q7:** 7 / 7
- **Q8:** 6 / 8  
  *Issue:* Incorrect explanation; need to mention explicitly or sufficiently allude to how the density of points considered in some epsilon neighborhood changes.
- **Q9a:** 2 / 3  
  *Issue:* Your condition needs to hold for all x and z, hence it becomes c ≥ 0.
- **Q9b:** 0 / 2  
  *Issue:* c acts as a bias but not as a regulariser; the value of c > 0 does not impact the solution.
- **Q10:** 3 / 10  
  *Issue:* Your condition is satisfied for small beta, which is incorrect; actually, the correct condition is only satisfied for large beta.
- **Q11a:** 1 / 1
- **Q11b:** 1 / 1
- **Q11c:** 2 / 2
- **Q11d:** 2 / 2
- **Q11e:** 2 / 2
- **Q11f:** 2 / 2
- **Q11gi:** 1 / 2
- **Q11gii:** 2 / 2
- **Q11giii:** 2 / 2

---

## Coursework 2 

**Coursework Overview**:
In Part I, I prove Rademacher complexity bounds for finite hypothesis spaces with logarithmic dependence on sample size. Part II covers Bayes decision rules and surrogate loss frameworks (squared, exponential, logistic, hinge), establishing Fisher consistency and comparison inequalities. Part III is a kernel perceptron project, where I implement one-vs-rest and one-vs-one classifiers on hand written digit data, experiment with polynomial and Gaussian kernels (including cross-validation and confusion-matrix analysis), and visualise the most challenging samples to predict.

**Overall Grade:** 100.00 / 100.00

### Detailed Commentary

- **General Grade:** 100 / 100
- **Q1.1:** 2 / 2
- **Q1.2:** 5 / 5
- **Q1.3:** 3 / 3
- **Q1.4:** 3 / 3
- **Q1.5:** 7 / 7
- **Q2.1:** 4 / 4
- **Q2.2:** 4 / 4
- **Q2.3:** 4 / 4
- **Q2.4:** 4 / 4
- **Q2.5.1:** 8 / 8
- **Q2.5.2:** 8 / 8
- **Q2.5.3:** 8 / 8
- **Q3:** 40 / 40  
  *Feedback:* Well done!
