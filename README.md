# Data Mining: Master's Degree Exam

<div align="center">
<img hight="300" width="700" alt="GIF" align="center" src="https://gifdb.com/images/high/going-for-mining-1w8cmnpq9lhhrw7i.gif">
</div>

</br>
</br>

The project involved conducting as a team data analysis using Python and data mining tools. The dataset comprised three CSV files:
- incidents.csv, 
- povertyByStateYear.csv,
- year_state_district_house.csv.

The incidents dataset contained information on gun incidents in the USA, including various variables such as date, location, participant details, and incident characteristics. The second file provided poverty percentages for each state and year, while the third file details winners of congressional elections.

## Tasks:
- Task 1: Data Understanding and Preparation
    - Task 1.1: Data Understanding \
Explore incidents dataset using analytical tools, assessing data quality, variable distributions, and pairwise correlations.
    - Task 1.2: Data Preparation \
Extract new features describing incidents, such as ratios of males, injured/killed people, and other indicators.
Conduct transformations, handle missing values, outliers, and assess data quality.

- Task 2: Clustering Analysis \
Explore dataset using clustering techniques.
Subtasks include K-means analysis, density-based clustering, and hierarchical clustering.
Evaluate clustering results and explore alternative techniques.

- Task 3: Predictive Analysis \
Predict the binary label indicating if an incident involves at least one killed person.
Define new features suitable for classification.
Compare different models, discuss results, and address preprocessing challenges.

- Task 4: Address one of the two tasks:
    - Task 4.1: Time Series Analysis \
Extract time series for each city from incidents in 2014-2017.
Subtasks include clustering and motif/anomaly extraction, and shapelet extraction based on the binary variable isKilled.
    - Task 4.2: Explanation Analysis \
Explain non-interpretable models (trained in Task 3) using LIME and SHAP.
Train an interpretable model (EBM or TabNet) and compare explanation approaches.


## Requirements by task:
- Task 1:
    - pandas
    - numpy

- Task 2:
    - seaborn
    - plotly
    - pyclustering
    - nbformat

- Task 3:
    - pydotplus
    - mlxtend
    - scikit-plot

- Task 4:
    - tslearn
    - tensorflow
    - matrixprofile-ts
    - wittgenstein