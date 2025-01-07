# FIFA 2018 Team Performance Analysis using Factor Analysis

## Overview
This project analyzes FIFA 2018 team performance metrics using **Factor Analysis** to identify underlying relationships between variables. The analysis includes preprocessing, correlation analysis, and factor analysis to gain insights into team characteristics.
## Usage

### Preprocessing
- Select relevant columns related to team performance metrics.
- Remove rows with missing values.
- Winsorize data to handle outliers, ensuring the analysis is robust.

### Exploratory Analysis
- Visualize boxplots before and after outlier treatment.
- Calculate correlations to identify highly correlated features.

### Factor Analysis
- Perform Bartlett’s test and KMO test to assess the suitability of Factor Analysis.
- Extract factors using Principal Component Analysis (PCA) and rotation methods.
- Visualize results using a Scree Plot and inspect loadings, communalities, and variance explained.

### Transform Dataset
- Generate transformed data using the extracted factors for further analysis or predictive modeling.

---

## Key Outputs

- **Boxplots**: Displaying data distribution before and after outlier treatment.
- **Correlation Matrix**: Highlighting strongly correlated variables.
- **Bartlett’s Test**: Chi-square and p-values to confirm dataset suitability for Factor Analysis.
- **KMO Test**: Measure of sampling adequacy for Factor Analysis.
- **Scree Plot**: To determine the optimal number of factors based on eigenvalues.
- **Factor Loadings**: Showing the strength of variables on the extracted factors.
- **Communalities**: Explaining shared variance among variables.
- **Variance Explained**: Total variance accounted for by each factor.

---

## Results Summary

- **Latent Factors**: Reduced the dataset to three significant factors based on Eigenvalues and Scree Plot.
- **Variable Contributions**: Highlighted key variables contributing to each factor.
- **Transformed Dataset**: Created a lower-dimensional dataset with significant factors for streamlined analysis.


---

## Author
Reetika Singh

---

## Requirements

### Libraries
The following Python libraries are required to run the code:
- `pandas` (Data manipulation and analysis)
- `matplotlib` (Data visualization)
- `factor_analyzer` (Factor analysis)
- `warnings` (Handling warnings)

To install the required libraries, run:
```bash
pip install pandas matplotlib factor-analyzer
