# KNN Classification using scikit-learn
The data description is available at: http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html.
The data was preprocessed i.e. missing values were dropped, min-max normalization performed on numerical/ordinal data and one-hot encoding for categorical/nominal data. 
The binary classification is done to predict income >50K or <=50K.

## Important information
I have done the following mapping in income column: 
income > 50K -> 2
income <= 50K -> 1


### Accuracy: 81.2%