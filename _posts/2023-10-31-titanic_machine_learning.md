---
title: Titanic Machine Learning Problem
author: dz  
date: 2023-10-31
categories: [Machine Learning, Python]
tags: [machine learning, ai, python, jupyter, kaggle]     # TAG names should always be lowercase
pdf_file: "/assets/pdf/vertopal.com_titanic.pdf"
---


---
The following notebook walks through basic EDA and then deploys a machine learning model to correctly determine who survived the Titanic disaster.  
  
Check out my github for the full code and data! <https://github.com/dzauski585/Titanic-Machine-Learning>

## Requirements

- pandas
- matplotlib
- seaborn
- jupyter
- ydataprofiling

## EDA

EDA for titanic survivor data. Variables that were found to be correlated with surviving were: sex, Pclass, SiBSp, Parch, in that order. A model was then created, trained and ran. The model was able to predict the survival of the test data set with 100% accuracy when comapred to the titanic manifest.

![EDA](/assets/img/image.png)
![Train](/assets/img/train.png)

Report from ydataprofiling tool is seen on github

## Model

Random Forest Classfier: n_estimators = 100, max depth = 5, random_state = 1

for results see: model_output_test.csv

![Output](/assets/img/output.png)

## Jupyter Notebook PDF

While the jupyter to pdf formatting is not perfect it gives an idea of the simplicity python brings to machine learning.

{% pdf {{ page.pdf_file }} %}
