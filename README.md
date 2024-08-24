# Estimating the Risk of Chronic Kidney Disease with Machine Learning and Deep Learning
# Introduction
This Project Aims to estimate the risk of CKD using the Real time [dataset](https://www.kaggle.com/datasets/mansoordaku/ckdisease) by applying our own customized ANN model, Support Vector Classifier followed by stacking them together for predicting with Random Forest with an accuracy of 90.32%.
# Data Preprocessing
The data is preprocessed by removing unnecessary columns (manually), followed by removing the null values rows and then converting into numerical variables with the help of Label Encoder. and then followed by applying principal component analysis to check if there are any unwanted columns (low variance).
# Model Results
![download](https://github.com/user-attachments/assets/0ace9cb4-9d8a-45de-9dd0-610e2bc8ffe9)
![download](https://github.com/user-attachments/assets/3a79fd88-bd94-4d0f-b53c-a96eb4560b57)
# Data Training and Testing
This involved implementing our own customized ANN models with (9 hidden layers and each input and output layer) drop out of 0.2% was used ans Cross-validator is used along with hypertuning of the parameters to avoid overfitting. and SVC(support Vector Classifier) was also used in the similar way and then they were stacked together once Random Forest Classifier to predict the final Output.
# Model Evaluation
Accuracy was used for evaluating the model performance

- Accuracy of Custom ANN : 72.82%
- Accuracy of SVC : 94.29%
- and after stacking the 
- Accuracy of Random Forest : 90.32%
# References
- [Dataset](https://www.kaggle.com/datasets/mansoordaku/ckdisease)
- [Keras](https://keras.io/)
- [Hypertuning Parameters](https://www.geeksforgeeks.org/hyperparameter-tuning/)
