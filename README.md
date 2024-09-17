# Dimensionality Reduction with PCA and t-SNE for Automobile Pricing

## Project Overview
This project applies Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) to identify key automobile specifications influencing selling prices. The dataset includes 205 rows and 26 features, providing an opportunity to explore how dimensionality reduction can enhance predictive analysis. These techniques can be extended to other contexts such as feature selection for machine learning models, clustering for customer segmentation, and improving data visualisation.

## Key Skills and Techniques
- **Data Preprocessing:** Encoding categorical features and normalising continuous variables.
- **Dimensionality Reduction:** Implemented PCA to capture maximum variance and used t-SNE for detailed visualisation of clusters.
- **Evaluation:** Assessed explained variance for PCA components and experimented with various perplexity values in t-SNE to identify optimal clustering.
- **Visualisation:** Employed visual tools to interpret the relationship between automobile specifications and prices.
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.

## Results & Insights
- **PCA:** Identified that 26 components account for about 95% of the dataset's variance, with the first few components showing a strong relationship with the target variable (price).
- **t-SNE:** Found that a perplexity range between 10 and 30 offered the best visualisation, revealing distinct clusters within the data.
- **Predictive Potential:** The clear patterns identified in PCA and t-SNE suggest that dimensionality reduction is effective for feature selection in predictive modelling.

## Usage
Refer to the notebook for a full analysis, including data preprocessing, PCA, t-SNE implementation, and insights on automobile price prediction.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
