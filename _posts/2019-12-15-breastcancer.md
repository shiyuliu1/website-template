---
layout: post
title:  Breast Cancer Cell Classification
subtitle: Prediction Accuracy and Sensitivity Analysis on Different Models for Breast Cancer Wisconsin Dataset
image: /img/breastcancer_cover.png
tags: [Machine Learning, Classification, Data Visualization]
---

Forecasting breast cancer can significantly increase the survival rate of patients, and classifying the
sample tumor cells as malignant or benign is one of the best and most direct ways to make accurate
predictions. Breast Cancer Wisconsin from UCI Machine Learning Repository was chosen as the dataset
to implement machine models and predict diagnosis result on practical cases. The target variable in this
dataset is the final diagnosis whether the tumor is malignant or benign. There are 30 real-valued
columns as independent variables with three properties, mean, standard error and worst cases, for
10 cytological features.


![](/img/breastcancer_hist.png){:height="49%" width="49%"} ![](/img/breastcancer_class.png){:height="49%" width="49%"}

Explotatry data analysis(EDA) was first conducted to explore both independent variables and target variables. For machine learning algorithms, LASSO regression, support vector machine, random forest, gradient boosting and Gaussian naive bayes classifier, were applied to this classification problem. In addition to the prediction accuracy, confusion matrix was then analyzed for the purpose of reducing Type II error. This is becasue clinical trials do not want to classify any positive cases as negative cases, resulting in delaying the treatments. 

To download my final repoert, follow this [link](https://github.com/shiyuliu1/data1030_project/raw/master/reports/Final_Report.pdf)
My code can be found in my [Github Repository](https://github.com/shiyuliu1/data1030_project).


![](/img/breastcancer_confusion.png){:height="49%" width="49%"} 
