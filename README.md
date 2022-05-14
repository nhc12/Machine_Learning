# Machine_Learning Homework
1. Performed the analysis following the starter code
2. CSV files added for reference
3. Credit Risk Resampling:
    * Data Preparation: Split the Data into Training and Testing
    * Data Pre-Processing: Scale the training and testing data using the StandardScaler from sklearn.(following the starter code)
    * Performed: Simple logistic regresion, Oversampling using the SMOTE Algorithm, undersampling using the Cluster Centroids algorithm, and Combination (Over and Under)     Sampling using the SMOTEENN algorithm
4. Ensemble Learners :
    * Data Preparation: Split the Data into Training and Testing
    * Data Pre-Processing: Scale the training and testing data using the StandardScaler from sklearn
    * 2 Algorithms: Balanced Random Forest Classifier and Easy Ensemble Classifier
    * For each algorithms:
      * Trained the model using the training data.
      * Calculated the balanced accuracy score from sklearn.metrics.
      * Displayed the confusion matrix from sklearn.metrics.
      * Generated a classication report using the imbalanced_classification_report from imbalanced-learn.
  5. Sources:
      *  https://imbalanced-learn.org/stable/references/generated/imblearn.ensemble.EasyEnsembleClassifier.html
      *  https://www.analyticsvidhya.com/blog/2021/12/a-detailed-guide-to-ensemble-learning/
      *  https://stackoverflow.com/questions/53032754/python-sklearn-accuracy-score-name-not-defined 
  6. Special note for submission: Please consider the one day delay in submission was due to a a personal COVID-19 positive result during the week of preparation for this homework which didn't allow me to be at 100% to work on this assignment. I kindly request to not consider a penalty for the short delay on this submission
