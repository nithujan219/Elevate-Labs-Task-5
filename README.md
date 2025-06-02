# Elevate-Labs-Task-5

Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract insights using statistical and visual methods.

Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **File Used**: `train.csv`

Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

Steps Performed

1. **Data Loading and Inspection**
   - Checked dataset shape and data types
   - Used `.info()` and `.describe()` for initial overview

2. **Missing Values Handling**
   - Dropped irrelevant columns: `Cabin`, `Ticket`
   - Imputed missing `Age` values with median
   - Filled missing `Embarked` values with mode

3. **Univariate Analysis**
   - Analyzed single variables like `Survived`, `Sex`, `Pclass`, and `Age`
   - Plotted histograms and bar plots

4. **Bivariate and Multivariate Analysis**
   - Examined relationships between `Survived` and other features (`Sex`, `Pclass`, `Fare`)
   - Used seaborn's `pairplot` and `heatmap` for visual correlation

5. **Outlier Detection**
   - Used boxplots to identify outliers in `Fare` and `Age`

Key Insights
- Females had a significantly higher survival rate
- Passengers in 1st class had better survival outcomes
- Higher fare correlated with increased survival
- Family size (from `SibSp` and `Parch`) had minor influence on survival

Summary
The analysis helped uncover survival patterns based on demographic and socio-economic factors. The most influential features were `Sex`, `Pclass`, and `Fare`.
