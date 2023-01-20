# Module_18_Challenge

## Overview of the analysis: 
### Explain the purpose of this analysis.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The purpose of this analysis is to investigate how the factors present in our loan stats CSV predict low or high risk loans. Using randomoversampler and smote algorithms in order to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report ultimately to to predict credit risk. We then compared different models to minimize bias in predicting credit risk.



## Results: 
### Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

* Naive Random Oversampling results showed that the balanced accuracy test it 67% the recall is 74%

![1](https://user-images.githubusercontent.com/69175360/213595018-a2e51911-2f70-453c-a99a-5f7368c157ae.JPG)


* SMOTE oversampling results showed that the accuracy score is 66.2%  and recall is 69% 

![2](https://user-images.githubusercontent.com/69175360/213595022-ab1449aa-0929-439d-952b-a9f4d7cf87b3.JPG)


* Undersampling results showed that the balanced accuracy score is 66.2% and the recall is 41% 

![3](https://user-images.githubusercontent.com/69175360/213595027-fac73160-db44-4c2d-b992-f7fb6e062ac2.JPG)


* The Combination of over and undersampling resulted in a balanced accuracy score is 54.7% and the recall is 57% 

![4](https://user-images.githubusercontent.com/69175360/213595048-7872ffc4-e553-4cc8-8f26-297c8275afc8.JPG)


* Balanced Random Forest Classifier results showed that the accuracy score is 77.2% and the recall is 88%

![5](https://user-images.githubusercontent.com/69175360/213595056-e2a41aa8-66d1-4ed0-937f-1f06a60d89e4.JPG)


* Easy Ensemble AdaBoost Classifier results showed the accuracy score is 91.7% and the recall is 94%

![6](https://user-images.githubusercontent.com/69175360/213595061-8f0c54e9-6532-4d89-b1a0-81c76f33e6c6.JPG)



## Summary: 
### Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

When using machine learning models, we are aiming for a good balance of recall and precision scores. Based on this necessity I would recommend using the ensemble classifiers over the first four models we used. The Easy Ensemble model would be my choice due to it's high accuracy score and good balance of precision and recall scores. While the other models worked to achieve our goals, they suffered from issues such as our accuracy score not being as high as the ensemble models and the recall scores being on the lower end as well. 
