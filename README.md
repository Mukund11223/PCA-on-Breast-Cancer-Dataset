# PCA-on-Breast-Cancer-Dataset
PCA on Breast Cancer Dataset

Project Overview

This project applies Principal Component Analysis (PCA) on the Breast Cancer dataset to reduce dimensionality and analyze the data in a lower-dimensional space. PCA helps in visualizing the variance across the data features while minimizing information loss.

Dataset

The project utilizes the Breast Cancer dataset available in scikit-learn, which contains features relevant to breast cancer diagnosis.

Libraries Used

The following libraries are used in this project:
	•	Pandas: For data manipulation and analysis.
	•	NumPy: For numerical operations.
	•	Matplotlib: For data visualization.
	•	Seaborn: For enhanced data visualization.
	•	Scikit-Learn: For PCA implementation and data preprocessing.

Data Preprocessing

Before applying PCA, the data is standardized to ensure that each feature contributes equally to the analysis. Standardization is performed using StandardScaler from the sklearn.preprocessing module.

Steps

	1.	Data Loading: Load the Breast Cancer dataset.
	2.	Data Standardization: Standardize the dataset features to have a mean of 0 and a standard deviation of 1.
	3.	PCA Application: Apply PCA to reduce the dataset’s dimensionality.
	4.	Visualization: Use Matplotlib and Seaborn to visualize the results.

Results

The output includes a visualization of the data projected onto the principal components, revealing clusters and patterns that help interpret the variance in the data.
