Diabetic Readmission Predictive Model
The aim of the assignment is to build a predictive machine-learning model to determine the likelihood of diabetic patients being readmitted to the hospital within 30 days of their discharge.
Data Cleaning and Transformation
1.  Libraries Used:  'pandas', 'seaborn', 'matplotlib'
Pandas is a powerful data manipulation library used for data cleaning, transformation, and preprocessing. Seaborn and Matplotlib are visualization libraries that help explore and understand the data.
2.  Missing Value Handling:  Replaced'?' with NaN and dropped columns with more than 90% missing values.
Columns with a high percentage of missing values may not contribute significantly to the model, and imputing such a large number of values could introduce bias.
3.  Near-Zero Variance Columns:  Dropped columns with near-zero variance.
4.  Encoding Categorical Variables:  Used 'LabelEncoder' from 'sklearn.preprocessing' to encode the categorical variables.
Data Visualization
1.  Libraries Used:  'seaborn', 'matplotlib'. Seaborn and Matplotlib are powerful visualization libraries that provide a wide range of plotting options for exploring and understanding the data.
2.  Visualizations Created:  Count plots, scatter plots, box plots, bar plots, histograms, and correlation matrices are used for visualizations.
Model Building
1.  Libraries Used:  'sklearn', 'imblearn'. Scikit-learn is a widely used machine learning library in Python, providing tools for preprocessing, model building, and evaluation.
2.  Model Selection:  Logistic Regression, Logistic Regression is a popular choice for binary classification problems, and it provides interpretable results.
3.  Evaluation Metrics:  Accuracy, precision, recall, F1-score, confusion matrix, classification report. These metrics provide a comprehensive understanding of the model's performance, taking into account different aspects such as true positives, false positives, and false negatives.
4.  Data Balancing:  Used 'RandomUnderSampler' from 'imblearn' to balance the dataset.
The dataset was imbalanced, with a higher number of non-readmitted cases. 
Improved Model
1.  Pipeline:  Used 'Pipeline' and 'ColumnTransformer' from 'sklearn' to create a preprocessing and modelling pipeline.
2.  Clustering:  Used 'KMeans' from 'sklearn.cluster' to cluster the dataset and build local classifiers for each cluster. Clustering the data and building local classifiers can improve the model's performance by capturing the unique patterns and characteristics of each and every cluster.
