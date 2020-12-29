# Credit Card Fraud

### Purpose
The purpose of this project is to detect fraud by comparing different Machine Learning models. 

### Analysisuse
Scikit learn's train_test_split function was used to split 60% and 40% of the dataset into train and test set. 3 kinds of algorhitms were also used in the analysis, which include:
1. Random Forest
2. Logistic Regression
3. SVM

The data is also highly imbalanced, with only 17% of the data being "Fraud" cases. That being said, on top of accuract metrics, AUC will also be used as the evaluation metric. Below figures show the AOC of the models used. 

![alt text]()
 
 ![alt text]()
 
 ### Conclusion
 Out of three models, Random Forest yields the highest AUC score of 0.96, which is quite high, although the rest of the models' scores were slightly lower. However, it is important to note that the data used in this project have been cleaned and manipulated. Thus, the accuracy of the model applied to the data must not be taken for granted. 
 
