# ml2

Question 1: Write a function to create a dataframe with variables and their feature importance using GridsearchCV and Random forest as base mode. Use Data_Classification dataset (10 Marks)

Parameters: max_depth = [4,5,6]; min_samples_split = [2,3,4,5] n_estimators = [100,200,300], criterion = ['gini', 'entropy']



Question 2: Build Random Forest model with best parameters derived from GridsearchCV and consider top FOUR variables based on score

Display accuracy score, Confusion matrix and Classification report (5 Marks)
(i) Plot Precision-Recall Curve (ii) Plot AUC_ROC curve (10 Marks)


Question 3:

Determine number of clusters based on plot using elbow method. Use Wholesale_customers dataset (8 Marks)
What is your interpretation from Dunn Index and Davies Bouldin Index for measuring clustering validity? (2 Marks)


Question 4: 

Write a code (PCA) to transform the features  in to two components and calculate explained variance ratio.Use Data_Classification dataset (3 Marks)
Write down two main difference between PCA and LDA (1 Mark)
In t-SNE algorithm, write down any two hyper parameters can be tuned? (1 Mark)


Question 5: 

Build SVM model with best parameters derived from GridSearchCV and display accuracy score and classification report. Use Data_Classification dataset (6 Marks) 
How will be the classification when you set parameter C as close to 0? Also mention whether it will be under-fitting or over-fitting? (2 Marks)
How will be the classification when you set parameter Gamma with very low value? Also mention whether it will be under-fitting or over-fitting? (2 Marks)
