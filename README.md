# Heart-Disease-Analysis
This analysis focuses on exploring and modeling  heart disease dataset. The primary objective is to understand the distribution and characteristics of heart disease in patients and to build predictive models to identify the likelihood of heart disease.

Data

The dataset, titled heart disease.csv, includes various clinical and demographic variables related to heart disease.

Methodology

Data Import
The dataset is imported into R for analysis.

Data Exploration
Initial data exploration includes viewing the first and last six rows of the dataset, examining the distribution of heart disease, checking for missing data, and summarizing the dataset.

Visualization
Several visualizations are created:

Bar plots to represent the distribution of heart disease overall and in relation to sex.
A line plot and additional bar plots are used to explore relationships between variables.
Data Partitioning
The dataset is partitioned into training and testing sets using a 67% split for training.

Logistic Regression Model
A logistic regression model is developed to predict heart disease. This includes:

Creation of contingency tables.
Model building and summary.
Confidence interval calculation.
Wald Test for statistical significance.
Likelihood Ratio Test.
Prediction probabilities and visualization.
Model Accuracy
The accuracy of the logistic regression model is calculated on the test data.

Decision Tree Model
A decision tree model is also constructed and visualized to predict heart disease.

Anomaly Detection
A plot is created to show the segments of anomalies in the data.

Prediction and Accuracy Testing
The decision tree model's predictions are made, and the accuracy is estimated using a confusion matrix.

Conclusions

The analysis provides insights into the factors associated with heart disease and the effectiveness of logistic regression and decision tree models in predicting heart disease. The logistic regression model's accuracy is quantitatively assessed.
