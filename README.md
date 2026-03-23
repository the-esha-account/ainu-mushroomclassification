# ainu-mushroomclassification

Can a machine learning model predict if a mushroom will kill you?

Results:

========================================
  Logistic Regression
========================================
              precision    recall  f1-score   support

      Edible       1.00      1.00      1.00       842
   Poisonous       1.00      1.00      1.00       783

    accuracy                           1.00      1625
   macro avg       1.00      1.00      1.00      1625
weighted avg       1.00      1.00      1.00      1625


========================================
  Decision Tree
========================================
              precision    recall  f1-score   support

      Edible       1.00      1.00      1.00       842
   Poisonous       1.00      1.00      1.00       783

    accuracy                           1.00      1625
   macro avg       1.00      1.00      1.00      1625
weighted avg       1.00      1.00      1.00      1625


========================================
  k-NN (k=5)
========================================
              precision    recall  f1-score   support

      Edible       1.00      1.00      1.00       842
   Poisonous       1.00      1.00      1.00       783

    accuracy                           1.00      1625
   macro avg       1.00      1.00      1.00      1625
weighted avg       1.00      1.00      1.00      1625

Model                     Train Acc    Test Acc    
=======================================================
Logistic Regression       0.9998       0.9988      
Decision Tree             1.0000       1.0000      
k-NN (k=5)                1.0000       1.0000      
=======================================================
