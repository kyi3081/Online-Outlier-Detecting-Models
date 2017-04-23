# Online-Outlier-Detecting-Models
Build online outlier detecting models with two unsupervised algorithms: one-class SVM and DBScan


In this project, we explore the German Credit Dataset which consists of 24 features of 1000 loan applicants and the classification whether each applicant is considered good or bad credit risk. This dataset can be downloaded from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data).

We will approach this problem of identifying bad credit risks using two different unsupervised algorithms: one-class SVM (Support Vector Machine) and DBScan (Density-based Spatial Clustering of Application with noise). We will tweak these algorithms a little to build two disparate online outlier detectors. After trainig our models with the initial dataset, we will update models sequentially instead of retraining them from scratch when new sets of data come in.
