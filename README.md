# Applied-ML-Algorithms
**Link:** 
**Objective:** 
 - Take dataset from [Kaggle](https://www.kaggle.com/c/titanic/data) and play with various Machine Learning models to get the best model which has highest accuracy in prediction.
 - Preprocess the dataset by explore and cleaning it.
 - Scenarios on when to use each model.
 - Learn practical application of Machine Learning models like:
    - Linear Regression
    - Logistic Regression
    - Support Vector Machines(SVM)
    - Random Forest Classifiers
    - XG Boosting
 - Fine tune hyper-parameters of each model to improve accuracy:
    - Learning Rate
    - Depth of Decision Tree
    - num_estimators of decision tree
    - Regularization parameter C
    - Kernel
    - activation functions
    - hidden_layer_size
    - and much more...
 -  Choosing optimal model by testing each model on test dataset and evaulating against each other's score.

**Result:**
 - After training 5 different models on the titanic dataset, I got an performance metrics as follows:
    - LR -- Accuracy: 0.758 / Precision: 0.778 / Recall: 0.675 / Latency: 2.2ms
    - SVM -- Accuracy: 0.753 / Precision: 0.767 / Recall: 0.675 / Latency: 4.3ms
    - MLP -- Accuracy: 0.742 / Precision: 0.776 / Recall: 0.627 / Latency: 11.5ms
    - RF -- Accuracy: 0.787 / Precision: 0.846 / Recall: 0.663 / Latency: 9.5ms
    - XGB -- Accuracy: 0.798 / Precision: 0.862 / Recall: 0.675 / Latency: 6.9ms
