# Student dropout prediction

This project is focused on predicting student droput rates by utilizing various machine learning algorithms such as Logistic Regression, SVM, Random Forest, and KNN.

   The dataset contains a lot of features. So, we done features selection by set a correlation threshold equals to 0.1 and remove columns with correlations below that threshold and columns that are likely not related to the students dropout.
  
  The target variable classifies students into one of three categories: those who have dropout, those who have graduated, and those who are still enrolled. Because the dataset is small and use classification models to predict thses three classes, the model accuracies are small. The solution is to classify the target into two class, those who not dropout, and those who dropout, this solution gives us a better accuracy and predict well the dropout rate.
