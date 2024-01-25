# ShAI Assignment
Data Exploration and Preprocessing
Data Overview:

I examined the dataset and found that it comprises 148,654 rows and 13 columns.
Column Types:

Utilizing the info method, we determined that most columns are of the float type.
Handling Null Values:

Identifying null values within the dataset, we observed that two columns, namely "Notes" and "Status," had 148,654 null records. As these columns did not contribute valuable information, we opted to drop them.
Imputation for Missing Values:

For columns with missing numerical values, we chose to impute using the mean. This decision was based on the continuous nature of the data, where using the median or mode could be inappropriate or misleading.
Verification of Null Value Removal:

We confirmed the successful removal of null values after the preprocessing steps.
Descriptive Statistics and Visualization
Descriptive Statistics:

Utilizing the describe method, we extracted key statistics such as mean, standard deviation, minimum, maximum, and range for the numerical columns.
Histogram Analysis:

Our initial histogram analysis revealed that salaries fall within a consistent range. Moving right, a decrease is noticeable, with "BasePay" and "Benefits" exhibiting similar values. In contrast, "OtherPay" and "OvertimePay" show a concentration above $100,000, with fewer records in the lower range.
Grouped Analysis:

The dataset was divided into groups based on job titles, and summary statistics were computed to facilitate a comparison between different job roles.
Correlation Analysis:

Examining correlations, we identified dependencies between certain columns. Notably, "TotalPay" and "BasePay" displayed a strong correlation, as did "TotalPayBenefits" with both "TotalPay" and "Benefits." Additionally, correlations were observed between "Benefits" and "TotalPay," as well as "Benefits" and "BasePay."
