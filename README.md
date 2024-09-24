# ABSTRACT
 - The  project mainly focuses on handling imbalanced data and detecting fraud cases following machine learning algorithms:

     a) logistic regression

     b) Randomforestclassifier

     c)DecisionTreeClassifier

     d)KNeighbourClassifier


     
These modelss are fitted to diffirent dataset acquired after standard scaler ,oversampling,undersampling and smote techniques.separate files are created for every  machine learning model so that every datasets acquired after above mentioned technique are fitted to our model using single function




# About Dataset
- My dataset was downloaded from kaggle website.

- The dataset included 21,693 transactions  each described by 28 features that is (V1-V28), with our target variable being the 'Class ' column.

- The class category had class [0] indicating the  non-fraudulent data and class[1] indicating the fraudulent data.

# Problem Statement

- My main aim was to develop a machine learning model that can accurately identify Fraudulent transactions based on the features given.

- Detecting Fraud is crucial in minimizing financial losses and maintaining  the intergity of financial system.

- # steps

1) importing libraries and loading datasets


2) Data preprocessing and preparing dataset:

 - have a general understanding of the data,i.e check for missingness,perform basic statistical analysis

3) Exploratory Data Analysis(EDA) and visualization:

  - visualize the data using  the bar graphs ,pie charts and get to understand the relationship between different entity columns.

4) Handling imbalanced dataset:

 - SMOTE method was the most appropriate although there are other methods to balance the data.

5) Model Selecction:

  - simple models(logistic regression)

  - Advanced model(Random forest)

  - Hyperparameter tuning (grid search)

6) Further Enhancement:

  - model training - training selected model on the training data by evaluating performance using metrics such as Accuracy,Recall,F1 score and AC-ROC curves

  -  Model evaluation- test the trained data on the test data and analyze false positive and false negatives to  understand the model weeknesses.


7) Best model :

 - identify the best model among the trained models for detecting the Fraudulent data.

 8) Recomendation.




