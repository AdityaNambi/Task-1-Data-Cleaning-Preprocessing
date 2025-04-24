# Task-1-Data-Cleaning-Preprocessing
Clean and prepare raw data for ML.

Step 1: Load and Explore Data
Load the dataset and check for missing values.

Step 2: Handle Missing Values
Fill missing "Age" with the median, and missing "Embarked" with the most frequent value.

Drop the "Cabin" column due to too many missing values.

Step 3: Encode Categorical Features
One-hot encode "Sex" and "Embarked" columns to numerical values.

Drop "Name" and "Ticket" columns as they are not useful.

Step 4: Standardize Numerical Features
Scale numerical columns ("Age", "SibSp", "Parch", "Fare") to have a mean of 0 and a standard deviation of 1.

Step 5: Visualize Outliers
Use boxplots to identify potential outliers in the numerical columns.
Remove Outliers
Remove data points outside the calculated IQR range (1.5 times the IQR above and below the 25th and 75th percentiles).
