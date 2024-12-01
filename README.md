# CryptoClustering
## Overview
This project uses unsupervised machine learning techniques to analyze and cluster cryptocurrencies based on their price changes over different timeframes. The clustering process involves:
- Data preprocessing and scaling
- Dimensionality reduction using Principal Component Analysis (PCA)
- K-Means clustering to identify patterns in the data

## Tools and Libraries
The following tools and libraries were used in this project:
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **hvPlot**: Interactive visualizations
- **scikit-learn**: Machine learning library for scaling, clustering, and PCA
- **Matplotlib**: Data visualization library for plots

## Files in Repository
- **`Crypto_Clustering.ipynb`**: Main Jupyter Notebook containing the code for the assignment.
- **`crypto_market_data.csv`**: The dataset used for clustering cryptocurrencies.
- **`README.md`**: This file, explaining the project structure and instructions.

## Project Workflow
1. **Data Preparation**:
   - The data from `crypto_market_data.csv` is loaded into a Pandas DataFrame.
   - Data is normalized using the `StandardScaler` module from scikit-learn.

2. **Finding Optimal Clusters**:
   - The elbow method is used to determine the best number of clusters (k) for the K-Means algorithm.
   - The process is applied to both the original scaled data and the PCA-reduced data.

3. **Principal Component Analysis (PCA)**:
   - PCA is used to reduce the dataset's dimensions to three principal components while retaining most of the variance.

4. **K-Means Clustering**:
   - K-Means is performed on both the original scaled data and the PCA-reduced data to assign cryptocurrencies into clusters.

5. **Visualizations**:
   - Scatter plots and elbow curves are generated to visualize clustering results and compare clustering efficiency.

6. **Comparison and Analysis**:
   - The results of clustering with and without PCA are compared and analyzed.

## Repository Structure
CryptoClustering/ ├── Resources/ │ ├── crypto_market_data.csv # Dataset ├── Crypto_Clustering.ipynb # Jupyter Notebook with code and analysis ├── README.md # This README file

