# EDA-Use-Case uing breast cancer dataset. 

## Exploratory Data Analysis(EDA):  

Exploratory Data Analysis is all about analysing the dataset and summarizing the key insights and characteristics from the data which are meaningful.


### EDA Checklist:

1. Understanding the dataset and check its shape.

2. Checking the datatype of each column.

3. Categorical and Numerical Columns.

4. Checking for the missing values, Iff there handle them by dropping them or imputation.

5. Descriptive summary of the dataset.

6. Groupby for classification problems.



### Summary and Inferences about the dataset from our Exploratory Data Analysis:

1. There are missing values in our dataset, so its not a problem here. If we would be having the missing values in our dataset then we will have to handle them.

2. Here all the values of the features are continuous, other than just the diagnosis column and we have done encoding for that also. So its not a problem now.

3. The mean of the all the values is slightly more than the median(50th percentile values). So, Our dataset is kind of rightly skewed. And we have to make it normally skewed by using some techniques like log transform.

4. There is slight imbalance in our data set as there is more cases of benign than the malignant cases, here the imbalance is not that high. So, we can just avoid handling it.

5. Using groupby we could see that the mean values of malignant cases are more than the benign cases.


