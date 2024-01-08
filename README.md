# Retail Sales Prediction

Project Summary:

Using historical data of Rossman stores which included several factors which affects the sales of the stores which includes several factors like Promotion, State holiday, School holiday and etc.The process followed:

1. Analysed the data- The number of rows and columns it had,type of the features presented,the kind of data each particular feature had,checked for duplicated or missing values.
2. Data manipulation- Checked for outliers and null values and fiixed it with the necessary operations.
3. Data Visualiztion - plotted various graphs and like customers,state holiday,school holiday,types of stores etc. charts to find out their affect on sales.Also plotted heatmap to find the correlation between different features.
4. Perfomed various hypothesis testing to get the select the correct hypothesis based on different types of test.
5. Data Pre-processing and feature selection- Treated categorical values and performed encoding. Dropped the unnecessary columns and rows.
6. Model Implementation - 2 model have been created:Model 1 with the pre-processed data that have selected features and rows and Model 2 having all the data.
7. ML algorithms that were performed were - Linear Regression,Decision Tree, Decision Tree with Hyperparameter tuning and Random forest.
8. In both the models Random Forest performed the best whereas while comparing both models it was found out that Model 2 was performing better than Model 1.
9. It can be seen that while droping rows and columns in Model 1 it lost some information which reduces the model's accuracy.
10. So,Model 2 was better suited for prediction of the provided dataset of Rossman Store.

Conclusion:

1. Initially after performing merge the dataset had 1017209 rows and 20 columns.
2. For model 1 the data was manipulated and all the unnecessary columns and rows were dropped.844392 rows and 20 columns were used.
3. In Model 1:Linear Regression gave 76% accuracy,Decision Tree gave 78% accuracy,Decision Tree(Tuned) gave 96% accuracy and Random Forest gave 97% accuracy. So overall Random Forest performed better for Model 1.
4. For Model 2 the entire dataset was considered.1017209 rows 19 columns.
5. In Model 2:Linear Regression gave 86% accuracy,Decision Tree(Tuned) gave 97% accuracy and Random forest gave 98% accuracy.So overall Random forest performed better in Model 2 as well.
6. So overall it can be clearly seen that Model 2 is performing better than Model 1 which means removing rows where Sales was 0 also removed some informations.
7. So for the given dataset the Model 2 will perform better.
