# Data-Science-Projects

## 1.Data Cleaning

Data in the real world is almost never clean. Often before doing anything with it, we have to clean it, which can involve many different steps. In this task, the aim is to explore a messy dataset, and correct any issues you may find. This is a required step before any visualization, which will take place in Data Visualisation part.

Below you are given a data set that contains details of a bank's customers. The task here is to use the preprocessing techniques that we've shown in the class to clean and transform this data set.

1. Uni-variate analysis:
  1.1 Type of each feature
  1.2 Mean, median, quantiles for continues
  1.3 Histogram or frequency tables for categorical

2. Find and remove duplicates.

3. Outliers:
  3.1 Identify the outliers
  3.2 Choose the correct treatment

4. Missing values:
  4.1 Identify missing values
  4.2 Impute missing values 

5. Transform categorical variables 

6. Scale the data set


## 2.Data Visualisation

Note: Before attempting Data Visualisation section, you should have Data Cleaning project as give in one of the files.

You are tasked with doing some exploratory data analysis, which is the first step in building a model to predict churn. Since this process is usually very large, we will look at a subset of

the total plots you would need to complete this.

1. First you should look at the differences in churn rates, split by the different categorical variables. Produce the appropriate visualisation to compare the average churn rate, split by:

  i. Geography

  ii. Gender

  iii. Tenure

2. We would also like to know how the data is distributed. Some models require features to be

normally distributed, and highly skewed variables can affect summary statistics if left

unchecked. Produce the appropriate visualisation for the distribution of:

  i. Geography

  ii. Age

  iii. Credit Score

3. Combine all of the above visualisations into a subplot.

4. Create a bar plot that shows the correlation of each feature with the target.

  4.1. Order the bars so that the feature with the highest correlation is the first bar.

  4.2. Add the correlation value to the top of each bar

  4.3. Add a line to the figure which shows the average correlation (hint: This will require adding an extra trace).
  

## 3.Deep learning Project

**Image classification with the CIFAR10 dataset(included in Keras)**

- Data set of 50,000 images for training and 10,000 for testing
- RGB(fullcolour) images of 32x32 pixels
- Images tagged in 10 different classes

**Objective of the project:**

  - Testing 5(ormore!) different combinations of elements (Network architecture,data augmentation…)
  - Collecting the results and analysing them
  - Giving a global comparison among the(atleast) 5 combinations
