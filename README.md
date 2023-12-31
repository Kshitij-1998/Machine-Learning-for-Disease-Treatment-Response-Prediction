# Machine-Learning-for-Disease-Treatement-Response-Prediction
Breast cancer is the most common cancer in the UK, with a woman’s lifetime risk being 12.5% and is usually treated with a combination of surgery, chemotherapy and radiotherapy, as well as hormonal treatments, depending on the type of breast cancer. Chemotherapy is typically used to reduce the size of the tumour before surgery. Chemotherapy, however, is toxic to the human body and is not always effective. Complete tumour resolution at surgery is known as Pathological Complete Response (PCR), which has a high likelihood of achieving cure and longer Relapse-Free Survival (RFS) time. RFS is the length of time a patient survives after primary treatment, without any further signs or symptoms of that cancer.  

This project attempted to predict PCR and RFS using information prior to chemotherapy treatment, to achieve better patient stratification and better treatment overall. The models were compared, and the best models were chosen based mainly on accuracy, among other parameters. In the second phase of evaluation, these models were further tested by our tutor on an unseen dataset for performance evaluation. 

The algorithm used in this project included:
1. VM (SVC and SVR)
1. ANN
1. Decision Trees
1. Random Forest
1. Logistic and Linear Regression 
1. XGBoost
1. KNN

During the first phase of testing the team found SVC (Support Vector Classifier) to be the best classification model for PCR with an accuracy of 75.7%. Additionally, Random Forest turned out to be the best regression method to predict RFS with a mean absolute error (MAE) of 20.73. In the second round of testing, the Final accuracy for classification accuracy (PCR) = 62.41. On the other hand, the MAE for the best regression model (RFS) turned out to be 19.42.  


