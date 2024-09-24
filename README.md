# Machine learning models for glioma grading
Development and testing of machine learning models for glioma grading (low grade vs glioblastoma multiforme) using a publicly available dataset from UCI.

## Dataset
The data used in this project is from the UC Irvine Machine Learning Repository. The dataset "Glioma grading clinical and mutation features" consists of 839 instances. For each record, the most frequently mutated 20 genes and 3 clinical features (collected from TCGA-LGG and TCGA-GBM brain glioma projects) are reported. The main task is to discriminate between Low-Grade Glioma (LGG) and Glioblastoma Multiforme (GBM). The dataset was donated to the UCI on 12/13/2022.
### ACKNOWLEDGEMENTS:
Tasci,Erdal, Camphausen,Kevin, Krauze,Andra Valentina, and Zhuge,Ying. (2022). Glioma Grading Clinical and Mutation Features. UCI Machine Learning Repository. https://doi.org/10.24432/C5R62J.

## Tools
This project is being carried out using Python 3.9.13 with the Spyder IDLE (Anaconda).

## Tasks and libraries
1 - Data cleaning: *pandas* /
2 - Data visualization: *matplotlib*, *seaborn* /
3 - Imbalanced data handling: *raw data*, *over-sampling* /
4 - Hyperparameters tuning: *Bayesian optimization* /
5 - Machine learning models: *support vector machine*/
6 - Explainable AI: *SHAP* (SHapely Additive exPlanations)
