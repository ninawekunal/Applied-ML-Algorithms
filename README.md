# Applied-ML-Algorithms
**Link:** [Titanic Prediction 5 models:](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/Final/Titanic_Predictions_5_models.ipynb)
**Objective:** 
 - Take dataset from [Kaggle](https://www.kaggle.com/c/titanic/data) and play with various Machine Learning models to get the best model which has highest accuracy in prediction.
 - [Preprocess](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/Data%20preprocessing/Titanic_data_preprocessing.ipynb) the dataset by explore and cleaning it.
 - Scenarios on when to use each model.
 - Learn practical application of Machine Learning models like:
    - Linear Regression
    - [Logistic Regression](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/Logistic%20Regression/Logistic_Regression_Tutorial.ipynb)
    - [Support Vector Machines(SVM)](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/SVM/SVM_Tutorial.ipynb)
    - [Random Forest Classifiers](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/Random%20Forest%20Classifier/Random_Forest_Tutorial.ipynb)
    - [XG Boosting](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/XGBoosting/GradientBoosting.ipynb)
    - [Multi-Layer Perceptron](https://github.com/ninawekunal/Applied-ML-Algorithms/blob/main/Multi%20Layer%20Perceptron/multi_layer_perceptron.ipynb)
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
 - After training 5 different models on the titanic dataset's *validation* data, I got an performance metrics as follows:
    - LR -- Accuracy: 0.758 / Precision: 0.778 / Recall: 0.675 / Latency: 2.2ms
    - SVM -- Accuracy: 0.753 / Precision: 0.767 / Recall: 0.675 / Latency: 4.3ms
    - MLP -- Accuracy: 0.742 / Precision: 0.776 / Recall: 0.627 / Latency: 11.5ms
    - RF -- Accuracy: 0.787 / Precision: 0.846 / Recall: 0.663 / Latency: 9.5ms
    - ***XGB*** -- Accuracy: 0.798 / Precision: 0.862 / Recall: 0.675 / Latency: 6.9ms
 - XGB performs the best in terms of Accuracy of 79.8% and Precision of 86.2%, and ties with LR with a high recall of 67.5% with a low latency.
 - On the *test* data, metrics were:
    - XGB -- Accuracy: 0.832 / Precision: 0.792 / Recall: 0.655 / Latency: 4.5ms
    - High Accuracy with a slightly low precision and recall with a low latency.
