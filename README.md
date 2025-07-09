# Supervised Learning - Coursework

This repository presents the submitted work for the COMP0078 courseworks 1 and 2 (UCL 2024/2025).

---

## Coursework 1

### Coursework Overview:
| Part     | Topics                                                                                                                              |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Part I   | Linear regression (with/without basis functions, kernels); Filtered Boston housing & kernel methods; Kernelised ridge regression    |
| Part II  | k-Nearest Neighbors: data generation; estimating generalisation error vs. k; optimal k vs. training size; additional clarifications |
| Part III | Theoretical questions: kernel modification; β→1-NN equivalence; No-Free-Lunch theorem and learnability                              |


**Overall Grade:** 95.00 / 100.00

### Detailed Commentary

| Question          | Score/Max | Comments                                                                                                                              |
| ----------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Q1                | 5/5       |                                                                                                                                       |
| Q2                | 10/10     |                                                                                                                                       |
| Q3                | 5/5       |                                                                                                                                       |
| Q4                | 10/10     |                                                                                                                                       |
| Q5                | 20/20     |                                                                                                                                       |
| Q6                | 5/5       |                                                                                                                                       |
| Q7                | 7/7       |                                                                                                                                       |
| Q8                | 6/8       | Incorrect explanation; need to explicitly mention or sufficiently allude to how the density of points in some ε-neighborhood changes. |
| Q9a               | 2/3       | Your condition needs to hold for all x and z, hence it becomes c ≥ 0.                                                                 |
| Q9b               | 0/2       | c acts as a bias but not as a regulariser; the value of c > 0 does not impact the solution.                                           |
| Q10               | 3/10      | Your condition is satisfied for small β, which is incorrect; the correct condition holds only for large β.                            |
| Q11a              | 1/1       |                                                                                                                                       |
| Q11b              | 1/1       |                                                                                                                                       |
| Q11c              | 2/2       |                                                                                                                                       |
| Q11d              | 2/2       |                                                                                                                                       |
| Q11e              | 2/2       |                                                                                                                                       |
| Q11f              | 2/2       |                                                                                                                                       |
| Q11gi             | 1/2       |                                                                                                                                       |
| Q11gii            | 2/2       |                                                                                                                                       |
| Q11giii           | 2/2       |                                                                                                                                       |


---

## Coursework 2 

### Coursework Overview:
| Part     | Topics                                                                                                                                                                              |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Part I   | Rademacher complexity; Hoeffding’s Lemma; finite hypothesis classes; logarithmic generalization bound; empirical Rademacher complexity                                                         |
| Part II  | Bayes decision rule; 0–1 loss; surrogate risk minimization; squared/exponential/logistic/hinge losses; Fisher consistency; comparison inequality (least‐squares)                               |
| Part III | Kernel perceptron; polynomial & Gaussian kernels; online training; multiclass schemes (one-vs-rest, one-vs-one); cross-validation; error analysis; confusion matrix; hard-sample visualization |


**Overall Grade:** 100.00 / 100.00

### Detailed Commentary

| Question          | Score/Max |
| ----------------- | --------- |
| Q1.1              | 2/2       |
| Q1.2              | 5/5       |
| Q1.3              | 3/3       |
| Q1.4              | 3/3       |
| Q1.5              | 7/7       |
| Q2.1              | 4/4       |
| Q2.2              | 4/4       |
| Q2.3              | 4/4       |
| Q2.4              | 4/4       |
| Q2.5.1            | 8/8       |
| Q2.5.2            | 8/8       |
| Q2.5.3            | 8/8       |
| Q3                | 40/40     |

  *Feedback:* Well done!

 ## Repository structure: 
```
├── supervised-learning-cw-1/    
│   ├── boston_filtered.csv       
│   ├── code_supervised_learning_coursework_1.ipynb  
│   └── COMP0078_cw_1_report.pdf  
├── supervised-learning-cw-2/    
│   ├── COMP0078_cw_2_report.pdf        
│   └── code_supervised_learning_coursework_2.ipynb      
├── instructions-cw-1.pdf         
├── instructions-cw-2.pdf         
└── README.md                      
```
