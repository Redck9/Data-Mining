# Data-Mining

A repository for the assignments in the Data Mining

This project encompasses a broad application of data mining techniques across several domains and datasets, each assignment designed to focus on a specific subfield such as classification, regression, association rules, clustering, and biological data mining. Each task was approached with a strong emphasis on model selection, feature engineering, validation procedures, and interpretability.

## **Assignment 1 - Naive Bayes Classification on Music Genre Data**

The first assignment involved building and optimizing Naive Bayes models — both Gaussian and Categorical — to classify music genres from an edited Kaggle dataset. The goal was to create both a multiclass classifier and a binary classifier, with the positive class based on a deterministic transformation of the group number. This work explored different combinations of variables and Laplace smoothing values to find the best-fitting model, balancing simplicity and performance.

## **Assignment 2 - Regression and Feature Selection on Superconductivity Data**

The second task involved regression on UCI’s Superconductivity dataset. The work focused first on feature importance, using selection techniques to identify the most relevant predictors for critical temperature. Then, dimensionality reduction (e.g., PCA/Kernel PCA) was applied and analyzed. Finally, multiple regression models were built — including linear regression, decision trees, and ensemble methods (AdaBoost, Gradient Boosting, Random Forests) — and evaluated using 5-Fold Cross-Validation. A table summarizing the top 10 models, their features, and hyperparameters was presented with analysis.

## **Assignment 3 – Association Rules and Itemsets on Retail Transactions**

This assignment focused on mining frequent patterns and association rules from a retail dataset. The work identified the top association rules based on support, confidence, and lift, and also derived the most significant maximal itemsets. Justifications were provided for the rule selection criteria, and both interpretability and business relevance were considered when evaluating the results.

## **Assignment 4 – Clustering on Weather Data**

Clustering techniques were applied to a weather dataset from the Max Planck Institute in Jena. The analysis was split into three parts:

 - Clustering rows collected at noon only


 - Clustering rows at noon and midnight


 - Clustering all 420,000+ data points


Algorithms such as K-Means, DBSCAN, and hierarchical clustering were tested with various configurations. Results were compared across the different temporal slices, highlighting how feature scaling and temporal inclusion affected the clustering structure. The third objective emphasized scalability and interpretability when working with large-scale data.

## **Final Assignment – Biological Activity and Molecular Fingerprints (ChEMBL/FDA)**

In the final project, the goal was to extract meaningful biological insights from molecular fingerprint data and their known biological targets. With over 2000 binary features per molecule, this dataset presented high dimensionality and sparsity. Several analysis paths were explored, including classification models to predict whether a molecule would be active on a particular biological target and clustering to group molecules by functional similarity. The approach prioritized a single clear goal and followed a rigorous evaluation pipeline to ensure statistical soundness and interpretability.
