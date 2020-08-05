# *Credit Risk With Supervised Machine Learning*

## *Project Overview*

Fast lending is a lending service company that wants to use machine learning to predict credit risk. Management believes that machine learning will do more accurate identification of good candidates for loans which will lend to lower default rates.

The company wants Ali to assist the lead data scientist in implementing this plan. In this role Ali will build and evaluate several machine learning models or algorithms to predict credit risk. Ali will use techniques such as resampling ans boosting to make most of his models and the data.

Once he designs and implements these algorithms Ali will evaluate their performance and see how well the models predict data.

## *Resources*
* Data Source: LoanStats_2019Q1.csv.
* Open-source distribution software Anaconda and the Jupiter notebook.
* Python libraries: Sklearn, Pandas, Imblearn.
* Visual Studio Code.

## *Results*

#### *I  used 2 models to test out the predictions of low and high risk credit applications. The following are the results:*

#### *Balanced Random Forest Classifier*  
Accuracy Score = 0.761, 
Precision - high risk = 0.03, 
Recall - high risk =  0.66, 
F1 - high risk = 0.06, 
Precision - low risk = 1, 
Recall - low risk = 0.86, 
F1 - low risk = 0.92
#### *Easy Ensemble AdaBoost Classifier*  
Accuracy Score = 0.93, 
Precision - high risk = 0.09, 
Recall - high risk =  0.92, 
F1 - high risk = 0.16, 
Precision - low risk = 1, 
Recall - low risk = 0.94, 
F1 - low risk = 0.97

Both the models used to predict loan risk have good scores.We see that the Easy Ensemble AdaBoost Classifier model does an exceptionally good job with predicting loan risk. We recommend use the Easy Ensemble AdaBoost Classifier model because the Accuracy Score is 0.93, the F1 score for low risk is 0.97, and the Recall score for high and low risk are 0.92 and 0.94, respectively.

#### *I  used 4 models to test out the predictions of low and high risk credit applications. The following are the results:*

#### *Naive Random Oversampling*  
Accuracy Score = 0.689, 
Precision - high risk = 0.01, 
Recall - high risk =  0.74, 
F1 - high risk = 0.02, 
Precision - low risk = 1, 
Recall - low risk = 0.63, 
F1 - low risk = 0.78
#### *SMOTE Oversampling*  
Accuracy Score = 0.66, 
Precision - high risk = 0.01, 
Recall - high risk =  0.64, 
F1 - high risk = 0.02, 
Precision - low risk = 1, 
Recall - low risk = 0.68, 
F1 - low risk = 0.81
#### *Undersampling*  
Accuracy Score = 0.534, 
Precision - high risk = 0.01, 
Recall - high risk =  0.66, 
F1 - high risk = 0.01, 
Precision - low risk = 1, 
Recall - low risk = 0.41, 
F1 - low risk = 0.58
#### *Combination Sampling*  
Accuracy Score = 0.64, 
Precision - high risk = 0.01, 
Recall - high risk =  0.72, 
F1 - high risk = 0.02, 
Precision - low risk = 1, 
Recall - low risk = 0.57, 
F1 - low risk = 0.73

Looking at the results, Naive Random Oversampling has the highest accuracy score.All four models had 0.01 for their precision scores for high credit risk and 1.00 for precision low credit risk. All F1 for high risk scores were low, and for low risk they were roughly the same, with the exception of undersampling with an F1 score for low risk at 0.01.

Both Oversampling models seem to be quite close.if we check their confusion matrix, it looks that Naive Random Oversampling does slightly better than SMOTE Oversampling.I recommend using the Naive Random Oversampling because it has a higher accuracy score and lower predictions. With Credit applications, money can be made from approving credit applications where individuals are less likely to default on their loans.