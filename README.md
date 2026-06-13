Task 2: Data Cleaning & Preprocessing

Internship Details
- Organization: Edutech Solution
- Program:Data Science Internship
- Task: Task 2 — Data Cleaning & Preprocessing

 Objective
Clean the Titanic dataset by handling missing values, removing
duplicates, converting data types, scaling features, and
handling outliers.

 Dataset Used
- Name:Titanic Dataset
- Source: Kaggle 

Tools & Libraries
- Python 3
- Pandas
- NumPy
- Scikit-learn (MinMaxScaler)
- Google Colab (Jupyter Notebook)

Steps Performed
1. Loaded dataset using Pandas
2. Handled missing values (Age→mean, Embarked→mode, Cabin→dropped)
3. Removed duplicate records
4. Converted Sex and Embarked to numerical values
5. Normalized Age and Fare using MinMaxScaler
6. Identified and handled outliers using IQR method
7. Exported clean dataset as titanic_clean.csv

 Key Results
- Missing values: Fully handled
- Duplicates removed: 0 found
- Columns after cleaning: 11
- Clean file: titanic_clean.csv

Learning Outcome
Understood data preprocessing basics — missing value imputation,
encoding, normalization, and outlier handling.
