# Data-Mining-and-Predictive-Modeling-Clustering-and-MLP-Forecasting

📝 Project Description
This project, completed for the 5SENG003W module, is a two-part data science investigation focusing on clustering analysis of a vehicle dataset and time-series forecasting using a Multi-layer Perceptron (MLP) Neural Network for exchange rates. The work emphasizes data preprocessing, model selection, and performance evaluation using standard statistical indices.

Based on the project report for the Machine Learning and Data Mining module, which involves two main areas (Partition Clustering and Multi-layer Perceptron Neural Networks), here is a project title and description:

📊 Project Title
Data Mining and Predictive Modeling: Clustering and MLP Forecasting

📝 Project Description
This project, completed for the 5SENG003W module, is a two-part data science investigation focusing on clustering analysis of a vehicle dataset and time-series forecasting using a Multi-layer Perceptron (MLP) Neural Network for exchange rates. The work emphasizes data preprocessing, model selection, and performance evaluation using standard statistical indices.

Part 1: Partition Clustering Analysis (Vehicle Dataset)

Pre-processing: Applied Tukey's method for outlier detection and removal, followed by Z-score scaling (standardization) to normalize the features.
Optimal Cluster (K) Determination: The optimal number of cluster centers was determined using four automated tools:
NBClust Method 
Elbow Method 
Gap Statistics Method 
Silhouette Method 
Dimensionality Reduction: Principal Component Analysis (PCA) was performed to reduce the dataset's dimensionality while preserving at least 85% (or 92% in the code snippet) of the variance.
Clustering: K-means clustering was applied to both the original and PCA-transformed datasets.

Part 2: MLP Neural Network Forecasting (USD/EUR Exchange Rates)

Forecasting Method: Used an Autoregressive (AR) method to construct an Input/Output (I/O) matrix using time-delayed vectors (lagged values) for exchange rate forecasting.
Normalization: Applied Standardization (Z-score) and Min-Max normalization to the I/O matrices to improve convergence and model performance in the MLP.
Evaluation Metrics: Model performance was assessed using standard statistical indices including RMSE (Root Mean Squared Error) , MAE (Mean Absolute Error) , MAPE (Mean Absolute Percentage Error) , and SMAPE (Symmetric Mean Absolute Percentage Error).
