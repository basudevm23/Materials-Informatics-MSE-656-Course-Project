# Materials-Informatics-MSE-656-Course-Project
This repository contains all the codes and resources, required to complete our project "Prediction of Grain Boundary Segregation Energy".

<img width="1267" height="722" alt="image" src="https://github.com/user-attachments/assets/c1c6ad28-979d-42a2-86eb-8f37f8a6b530" />


Members:
Prutha Vinay,
Basudev Mohapatra,
Bakare Shivraj Shivaji,
Khushal Karadiya and Gaurav Kumar.


Contents:

processed_features.csv: This csv file was used as the primary dataset for training the models, namely Linear Regression, DT and Random Forests, and finally Graph Neural Networks.

GB_Energies_datasets.ipynb: Codes for Data cleaning and merging of various datasets, to produce the final raw dataset.

Grain_boundary_features.ipynb: Codes for Data preprocessing. This produces the final, clean dataset i.e., "processed_features.csv".

Linear_Regression_and_its_Variations.ipynb: Training a linear regression model on the primary dataset.

DT and Random Forest.ipynb: Training a DT and Random Forest model on the primary dataset.

Graph Neural Networks.ipynb: Training GNNs on the primary dataset.

Description: 

This project predicts grain boundary segregation energies in alloys using data-driven models. It integrates feature-engineered ML methods and graph neural networks to learn atomic-level interactions. Compared to traditional DFT calculations, the pipeline offers faster, accurate screening of alloy systems, with GNNs achieving the best performance in capturing segregation behavior.


