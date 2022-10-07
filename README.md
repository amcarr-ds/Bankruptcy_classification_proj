# Final Team 1 Project for ADS-505: Applied DS for Business

#### -- Programming Language: Python 3+
#### -- Project Status: [Active]

## Project Intro
In current state, perspective lenders apply for a business loan with a financial institution of their choice, where a manual review of financial statements is usually performed by a junior analyst with 0-2 years of experience, using an Excel based template. This template is manually developed and can often contain data entry errors that are caught by supervisors when reviewing for accuracy and completeness. However, with competing strategic and operational priorities facing today’s management teams, this review can often be quick and heavily reliant on the correctness of the initial assessment performed by the junior analyst. This presents a cause of concern for the financial institutions solvency if loans are extended to high-risk applicants. 

## Project Objective
To provide for an automated, non-biasd evaluation of a company’s current financial position and mitigate the financial risk associated with a business lending applicant. The output of this analysis will complement the manual review provided by junior financial analyst and be provided as supplemental analysis to business lending management teams. 

### Partners/Contributors
* Uyen Pham
* Ryan Dunn
* Aaron Carr

### Methods Used
* Data preprocessing: E.g., importing csv files, merging multiple dataframes (df's), pandas df manipulation
* Binary Classification
* Exploratory Data Analysis (EDA): E.g., examining variable correlations, univariate analyses (e.g., boxplots, scatter plots, descriptive stats, histograms), check for outliers
* Feature values transformations: Scaling, adjust for skew, KNN imputation for null values
* Feature elimination: Highly correlated features (>.95 *r* for pair-wise variables), count of null values over a threshold (15% of data set *N*)
* Train/Test splitting
* Machine Learning: neural networks (NN), Gradiant Boosted trees, *k*-nearest neighbors (KNN), quadratic/linear discriminant analysis (Q/LDA), single classification tree, Random Forests
* Predictive model evaluation, e.g., confusion matrices, accuracy, recall, precision, *F1*-score

## Getting Started
1. Clone this repo for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/).
2. Raw Data is being kept [here](data) within this repo.
3. Data processing/transformation scripts are being kept [here](notebooks)

## License
TBD

## Acknowledgments/References
Zięba, M., Tomczak, S. K., & Tomczak, J. M. (2016). Ensemble boosted trees with synthetic features generation in application to bankruptcy prediction. *Expert Systems with Applications*, *58*, 93-101. https://doi.org/10.1016/j.eswa.2016.04.001.