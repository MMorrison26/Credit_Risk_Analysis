# Credit Risk Analysis
## Which Model Works Best

### *Overview*
At Fast Lending, they would like Jill and I to use Machine Learning to predict credit risk so they can identify good candidates and ultimately lower their default rates. We've obtained some data from LendingClub, a peer-to-peer lending services company, to oversample, undersample, and look at a combinatorial approach versus two other Machine Learning models to see which model is best at predicting risk.

### *Results*
* Naive Random Oversampling: Balanced Accuracy is 62.9%, Precision is 99%, and Recall is 68%.
![image](https://user-images.githubusercontent.com/87578449/145691022-b4207769-51fb-4ef7-bdd3-4bd1e2d72cec.png)

* SMOTE Oversampling: Balanced Accuracy is 62.8%, Precision is 99%, and Recal is 63%.
![image](https://user-images.githubusercontent.com/87578449/145691067-2d5acc4e-9a49-4932-8c0b-92bb1b42ba27.png)

* Undersampling: Balanced Accuracy is 51.6%, Precision is 99%, and Recall is 44%.
![image](https://user-images.githubusercontent.com/87578449/145691092-efe50600-2ca4-44a6-b56a-f116af8f0d2f.png)

* Combinatorial SMOTEEN: Balanced Accuracy is 65.5%, Precision is 99%, and Recall is 61%.
![image](https://user-images.githubusercontent.com/87578449/145691121-5d8ad10b-7500-4742-8747-5809e8cfd964.png)

* Balanced Random Forest Classifier: Balanced Accuracy is 79.6%, Precision is 99%, and Recall is 91%.
![image](https://user-images.githubusercontent.com/87578449/145691154-cf6a0d2a-f7c7-4e64-9901-498b61703d82.png)

* Easy Ensemble AdaBoost Classifer: Balanced Accuracy is 72.7%, Precision is 100%, and Recall is 100%.
![image](https://user-images.githubusercontent.com/87578449/145691190-52fbe6d5-37d5-447a-9b06-a85cb7b7f592.png)


### *Summary*
