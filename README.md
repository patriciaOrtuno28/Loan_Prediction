# Loan Prediction Challenge

* Laura Fernández Galindo: 
&nbsp;
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/laura-fern%C3%A1ndez-galindo-6113bb221/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/Laurafdez)

* Luis López Álvarez: 
&nbsp;
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/luis-l%C3%B3pez-%C3%A1lvarez-90ba57213/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/Luislopal)

* Álvaro de Rojas Maraver: 
&nbsp;
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/%C3%A1lvaro-de-rojas-maraver-42a4641b2/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/alvarodRM)

* Andrea Carballo Torres: 
&nbsp;
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/andrea-carballo-torres/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/AndreaCarballo)

* Pablo Rubio Noguera: 
&nbsp;
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/pablo-rubio-noguera-2ba646216/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/Pabloj20)

* Patricia Ortuño Otero: 
&nbsp;
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/patricia-ortu%C3%B1o-otero-55b102215/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/patriciaOrtuno28)

# License

<a href="LICENSE">LICENSE</a>

# Development

## Original Dataset

Given the following dataset, the aim is to predict whether a loan will be approved or not:

<img src="img/dataset_pt1.jpeg" width="400" /> <img src="img/dataset_pt2.jpeg" width="400" />

## Feature engineering

The data in the columns is modified to be treated as generalized groups represented as integers to avoid using categorical data, and avoid overfitting.

New columns are obtained to capture non-linear relationships between existing ones, and others are analyzed to understand their effect over the Accept column (the one to be predicted), such as ApprovalFY and the FranchiseCode:

<img src="img/franchise_approval.jpeg" width="400" />

## Final Dataset

The final dataset to train the model with has new columns such as if the loan was approved during the Recession.

<img src="img/dataset_pt3.jpeg" width="400" /> <img src="img/dataset_pt4.jpeg" width="400" />

## Correlation

<img src="img/corr.jpeg" width="400" />

## Geometric Models

### Logistic Regression

<img src="img/rl_report.jpeg" width="400" /> <img src="img/rl_roc.jpeg" width="400" />

### SVM

<img src="img/svm_report.jpeg" width="400" /> <img src="img/svm_roc.jpeg" width="400" />

### kNN

<img src="img/knn_report.jpeg" width="400" /> <img src="img/knn_roc.jpeg" width="400" />

### Stacking

<img src="img/stack_report.jpeg" width="400" /> <img src="img/stack_roc.jpeg" width="400" />

## GaussianNB

<img src="img/gnb_report.jpeg" width="400" /> <img src="img/gnb_roc.jpeg" width="400" />

## Trees

### Random Forest

<img src="img/rf_report.jpeg" width="400" /> <img src="img/rf_roc.jpeg" width="400" />

### XGBClassifier

<img src="img/xgb_report.jpeg" width="400" /> <img src="img/xgb_roc.jpeg" width="400" />

## Neural Networks

<img src="img/nn_report.jpeg" width="400" /> <img src="img/nn_roc.jpeg" width="400" />


