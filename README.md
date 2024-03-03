# Krakow weather analyses

This project analyses hourly meteorological data from the Krakow area over the last 20 years. In addition to the analysis itself, the aim was to classify multi-class days into their associated seasons using classical machine learning methods (without neural networks).

> The project was developed for **educational purposes**. And for **fun** :)

The project consists of the following stages:
  1. exploratory data analysis,
  2. visualisation of the data, their relationships and correlations,
  3. pre-processing and cleaning of the data including handling of outliers and missing values,
  4. creation of data processing pipelines,
  5. dimensionality reduction,
  6. feature selection,
  7. models learning and evaluation,
  8. ensemble learning,
  9. hyperparameters optimisation,
  10. error analysis.

### Exploratory analysis
Exploratory analysis, the most extensive part of the project, focuses mainly on in-depth understanding of data relationships, detection of trends, anomalies or identification of other patterns based on qualitative analysis as well as visualisations.

### Visualisations
Visualisations mainly concern correlations and relationships between data, distributions or groups of similar observations. The main variables represented in the graphs are temperature, pressure, humidity or UV index, among others.

### Data preprocessing
Data processing involves determining the daily mean values of the observations, filling in missing values using the chosen method and dividing the data into learning and test sets. Finally, a `sklearn` pipeline was created to encapsulate the data processing.

### Feature selection
Feature selection is based on principal component coefficient analysis and feature importaces obtained from a random forest. 

### Hyperparemeter optimisation
Hyper-optimisation was carried out using Optuna, a software library that allows easy Bayesian optimisation and visulisation of the optimisation process. 

### Model evaluation & error analysis
Standard classification metrics such as accuracy, F1 score, PR curve or confusion matrix were used to assess the quality of model performance. Cross-validation was used to test the stability of the models.

## Tech stack
Technologies and tools used in this project:
  - Python,
  - pandas,
  - NumPy,
  - scikit-learn,
  - matplotlib,
  - seaborn
  - Jupyter,
  - missingno,
  - Optuna.
