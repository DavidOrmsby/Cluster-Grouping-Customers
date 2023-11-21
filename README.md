# machine_learning_project-unsupervised-learning

## Goals
- In this project I will take data gathered on clients of a wholesale distributor and attempt to group them into clusters using unsupervised machine learning techniques.  The data is available here [Kaggle Link](https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set)

## Process
- EDA / Data Cleaning
    - There were a few outliers that needed removing

- K-means Clustering

- Heirarchical Clustering

- Feature reduction with PCA

## Files
- Unsupervised Learning - Project.ipynb
    - All the work is done here

- data / Wholesale_Data.csv
    - A copy of the dataset used

## Conclusion
- There is a positive correlation between the amount of detergent, paper, milk, and groceries that clients order. 

- Both K-means and Heirarchical Clustering identified 3 main groups that we can seperate customers into.  This can be used to create seperate marketing strategies for each of the 3 groups.

- PCA identified 2 main components that can capture 90% of the variance.  In the future if we want to reduce the dimensions of our models we could use only those 2.