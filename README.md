# Experiment-13

Name -> Madhur Gupta

PRN-> 25070123070

Batch-> B1

AIM

To study and implement data preprocessing techniques in Python using Pandas and Scikit-learn for cleaning, transforming, and preparing datasets for analysis and machine learning.

________________________________________________________________________________________________________________

THEORY

Data preprocessing is an essential step in data analysis and machine learning, where raw data is cleaned and transformed into a suitable format for further processing. Real-world datasets often contain missing values, duplicate records, categorical text data, and numerical features with varying scales. Python libraries such as Pandas and Scikit-learn provide powerful tools to handle these issues efficiently. Common preprocessing steps include handling missing values, removing duplicates, encoding categorical variables, scaling numerical features, and splitting the dataset into training and testing sets. Proper preprocessing improves data quality and enhances the performance of machine learning models.

One-line explanation of functions used:

1-> read_csv() – Loads the dataset from a CSV file into a DataFrame.

2-> isnull() – Checks the dataset for missing values.

3-> sum() – Counts the total number of missing or duplicate values.

4-> fillna() – Replaces missing values with specified values such as mean, median, or mode.

5-> dropna() – Removes rows or columns containing missing values.

6-> duplicated() – Identifies duplicate rows in the dataset.

7-> drop_duplicates() – Removes duplicate records from the dataset.

8-> LabelEncoder() – Converts categorical text labels into numerical form.

9-> get_dummies() – Performs one-hot encoding by creating binary columns.

10-> StandardScaler() – Standardizes numerical features to zero mean and unit variance.

11-> train_test_split() – Splits the dataset into training and testing subsets.

12-> info() – Displays the structure and data types of the processed dataset.

________________________________________________________________________________________________________________

CONCLUSION

Thus, we successfully studied and implemented data preprocessing techniques using Pandas and Scikit-learn. We learned how to clean raw data, handle missing and duplicate values, encode categorical variables, scale numerical features, and split datasets, which are essential steps for accurate data analysis and machine learning.
