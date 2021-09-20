# ML-AI-Projects

This is a customer segmenation model. It uses the data from "HackerEarth HackLive: Customer Segmentation" https://www.kaggle.com/kunalgupta2616/hackerearth-customer-segmentation-hackathon and the refernce to this dataset defenition is from https://docs.1010data.com/Tutorials/MachineLearningExamples/BankMarketingDataSet_2.html

The given dataset is actually for prediction.

I render a model to get a customer segmentation using this dataset.

I tried modelling with UMAP Estimator for clustering representation. 

Initial check on dataset for clusters is made through Hopkins Score, and received 74%. So proceeded with clustering technique.

I used k-means, k-prototype and k-mode algorithms for this model. 

Visualisation across all features against the cluster labels is provided for k-mode algorithm.

To evaluate the clustering models, I used LGBMClassifier. Also used Shap's TreeExplainer to visualize the summary of the cluster against the dataset.

To fetch rules for clustering, I used DecisionTreeClassifier
