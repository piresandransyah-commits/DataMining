# DataMining
Predictive Modeling and Factor Analysis of Agricultural Crop Yield using Data Preprocessing, Decision Trees, and Statistical Visualization.

# Data Preprocessing & Normalization
1. Verified dataset completeness (0 missing values) and cleaned data structure using pandas.
2. Applied StandardScaler to numerical features (suhu, kelembaban, curah_hujan, luas_lahan, hasil_panen) to ensure uniform feature weight across models.
3. Evaluated dataset statistics (mean, std, min, max) before and after scaling.

# Classification Modeling (Decision Tree)
1. Partitioned dataset into 80% training set and 20% testing set.
2. Built a Decision Tree Classifier (DecisionTreeClassifier) to categorize crop yield outcomes.
3. Achieved 100% accuracy on test data with zero false positives or false negatives across all classes (rendah, sedang, tinggi).

# Descriptive Statistics & Correlation Analysis
1. Computed descriptive statistics to understand overall feature distributions.
2. Identified linear relationships between features and the target variable (hasil_panen).

# Data Visualization
1. Plotted a Histogram with Kernel Density Estimation (KDE) for standardized yield scores.

Bivariate Analysis: Generated a Scatter Plot to inspect the linear relationship between rainfall and yield across categories.

Feature Matrix: Created a Correlation Heatmap (RdYlGn) to visualize multi-variable dependencies.
