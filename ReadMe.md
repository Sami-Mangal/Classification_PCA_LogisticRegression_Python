
## Executive Summary:

This project will use Principal Component Analysis(PCA) and Logistic Refression to classify music  genre. Various musical features are extracted and patterns are defined to predict the genre of the music.

Principal Component Analysis (PCA) is used to reduce the dimensionality of the dataset. It transforms a set of correlated variables into a set of uncorrelated variables, called principal components. PCA is often used to reduce the number of features in a dataset. This can make machine learning algorithms more efficient and accurate.

Logistic regression is a fundamental statistical method used for modeling the relationship between a binary dependent variable and one or more independent variables. It’s primarily employed for binary classification tasks, where the dependent variable takes on only two possible values, typically represented as 0 and 1.


### Objective: 

Music tracks are required to be catogorized and recommended based on genres for digital streaming.  In the dataset, there are records that lacks genre information. In this project, we are required to predict the genres of these unlabeled tracks.


### Methodology: 

1. Read, clean and transforms the data from the csv file.
 
2. Perform PCA transfomation and build logistic regression model.


### Skills:

Python: Pandas, Matplotlib, Numpy, Scipy, Scikit-learn, Seaborn 

Statistcal concepts: Principal Component Analysis, Logistic Regression


### Results: 

Logistic Regression was performed in original test data and PCA transformed data. It was found that accuracy was slightly better for the PCA transformed data. Hence, model estimatesfrom PCA transformed data was used to make the prediction of the unknown music genre.







