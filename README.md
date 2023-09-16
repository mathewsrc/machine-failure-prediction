# machine-failure-prediction

<p align="center">
<img src="https://github.com/mathewsrc/machine-failure-prediction/assets/94936606/69177a11-5937-4016-bf17-b41e1c00c4f1" width="400" height="300">
</p>


## Introduction

In the field of industrial maintenance and operations, the timely detection of machine failures is crucial to prevent unexpected downtime, minimize production losses, and optimize maintenance strategies. Machine learning techniques have emerged as valuable tools for predicting and classifying data. However, the effectiveness of such models heavily relies on the quality and balance of the dataset used for training.

Throughout this project, I will explore different techniques for addressing the class imbalance, including oversampling and undersampling methods. Additionally, I will investigate the impact of various feature engineering strategies, such as dimensionality reduction and feature selection, to improve the model's ability to discriminate between healthy and failing machines.

The performance of the developed binary classification models will be evaluated using accuracy, confusion matrix, and area under the receiver operating characteristic curve (AUC-ROC). The results will be compared with a baseline model trained on the original unbalanced dataset, highlighting the effectiveness of the proposed techniques in improving the model's performance on the minority class (failure machines).

Prerequisites:
 * [Databricks community account](https://community.cloud.databricks.com/login.html) or a paid account
 * Machine Learning Databricks runtime. For this project, I used version 13.2 ML

Advantages of using Databricks
* Easy setup
* Scalable. It uses clusters for work distribution
* Pipelines
* Easy integration with the cloud provides
* Delta Lake as the default storage format for all operations
* It already has spark and mlflow installed and is ready for use
* We can use easy change code language in the notebook and use more than one in the same notebook. Available languages: Python, R, Scala, and SQL.
* UI tool in notebooks to create visualizations from SQL queries 
* No need for hardware
  
