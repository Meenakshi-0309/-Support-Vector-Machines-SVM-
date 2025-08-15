Task 7 —   Support Vector macine
📖 Overview
This updated version of Task 7 ensures that any missing values (NaNs) in the dataset are addressed before running the main logic.
By handling NaNs in advance, the process becomes more stable and avoids errors during analysis, visualization, or model training.

Changes Made
Added a step to clean missing data before executing Task 7.
Provided two strategies:
Removal of rows with missing values.
Optional filling of missing values with an appropriate substitute (e.g., column mean for numeric data).

 Why This Change?
Prevents crashes caused by NaN values during execution.
Ensures that the dataset is consistent and ready for further processing.
Gives flexibility to choose between removing or replacing missing data based on project needs.

 How to Use
By default, the NaN-handling step removes any rows containing missing data.
If you prefer to retain all rows, you can replace missing values instead of removing them.
The choice depends on your dataset size and the importance of preserving every record.
Notes
For numeric columns, replacing NaNs with the mean or median is often effective.

For categorical columns, replacing NaNs with the most frequent value (mode) or a placeholder is recommended.

Always review the dataset after NaN handling to ensure the data still reflects real-world conditions.
