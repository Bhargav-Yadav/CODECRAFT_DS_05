# CODECRAFT_DS_05
 Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.
 
# Road Traffic Accident Data Analysis

This notebook performs an analysis of the Road Traffic Accident Dataset.

## Steps Performed:

1.  **Loading Libraries and Data**: Necessary libraries were imported and the dataset was loaded.
2.  **Exploratory Data Analysis**: Initial data exploration was done, including checking for duplicates and examining the distribution of accident severity.
3.  **Handling Missing Values**: Missing values in the dataset were identified and addressed by dropping columns with a high number of missing values and filling remaining missing values in categorical columns with the mode.
4.  **Data Visualization**: Various visualizations were created to understand the relationships between variables, including scatter plots, joint plots, and histograms. Correlation between numeric variables was also visualized using a heatmap.
5.  **Handling Categorical Values**: Categorical variables were transformed into numerical format using Label Encoding and one-hot encoding for further analysis. Feature selection was performed using the chi-squared test to identify relevant categorical features.
6.  **Separating Independent and Dependent Variables**: The dataset was split into independent variables (features) and the dependent variable (Accident Severity).
7.  **Oversampling**: SMOTE was used to address the class imbalance in the target variable.
8.  **KNN Model Creation**: A K-Nearest Neighbors model was created and trained on the processed data.
9.  **Prediction**: Predictions were made using the trained KNN model on the test set.
10. **Model Evaluation**: The performance of the KNN model was evaluated using accuracy score, classification report, and confusion matrix.
