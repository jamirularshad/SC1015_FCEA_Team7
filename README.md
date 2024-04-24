# SC1015_FCEA_Team7

# Predictive Analysis of Leading Death Causes in Southeast Asia

## About the Project

This repository contains the work for a data science project aimed at analyzing the leading causes of death in Southeast Asian countries. The goal is to identify major health challenges, cluster countries based on mortality profiles, and use predictive modeling to forecast future trends in mortality without relying on time series analysis.

### Objectives

- Identify Leading Causes: Calculate and visualize the leading causes of death in each Southeast Asian country.
- Cluster Analysis: Perform hierarchical clustering to find similarities among countries based on mortality data.
- Predictive Modeling: Develop models to predict future changes in the leading causes of death.

## Project Structure

### Notebooks

1. Data Preparation and Exploration.ipynb
   - Data Cleaning: Handling missing values, outliers, and inconsistencies.
   - Data Transformation: Normalization and formatting adjustments.
   - Initial Data Analysis: Summary statistics and initial visualizations.

2. Identifying Leading Causes of Death.ipynb
   - Calculation of total deaths per cause for each country.
   - Visualization using heatmaps and bar charts to depict the leading causes.

3. Similarity Analysis between Countries.ipynb
   - Application of hierarchical clustering.
   - Visualization of clusters using dendrograms.
   - Detailed cluster analysis.

4. Feature Engineering and Predictive Modeling.ipynb
   - Creation of synthetic features to enhance model performance.
   - Comparison of machine learning models including Random Forest, SVM, and Gradient Boosting.
   - Model training, validation, and evaluation using cross-validation and appropriate metrics.

5. Advanced Techniques.ipynb
   - Implementation of PCA and t-SNE for dimensionality reduction.
   - Use of ensemble methods to improve predictions.
   - Analysis of feature importance to understand model drivers.

### Data

Data used in this project is sourced from publicly available health databases and includes detailed mortality statistics for Southeast Asian countries. The exact sources and data descriptions are provided within each notebook.

## How to Use

1. Clone this repository.
2. Ensure you have Jupyter Notebook installed, or use Google Colab to open the .ipynb files.
3. Follow the notebooks in order to understand the data preparation, analysis, and modeling steps.

## Dependencies

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Contributors

- [Azad Mohamed Jamirul Arshad] - 
- [Preet Singh Chawla] 
- [Dharshak] 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special appreciation to all the data providers and open-source communities that have made their resources available for educational and research purposes.
