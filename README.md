Report 


* The purpose of this analysis is to predict loan defauting for both the risky loans and healthy loans.

* The model uses loan_size ,interest_rate , borrower_income,debt_to_income,num_of_accounts, derogatory_marks,total_debt to predict future risks.

* in the provided data there was an imbalanced of high risk loans of 2500 and secure loans of 75036

* The model was built using Logistic Regression. The model predicted the results both on original data and resampled the data.

## Results

* Machine Learning Model 1 (original scaled data):
  balanced_accuracy_score: 0.9520479254722232 and the model was accurate 95% 
  

* Machine Learning Model 2(resampled data):
  balanced_accuracy_score: 0.9936781215845847 and the model was 99% accurate
  

 

## Summary


 I consider the both model perform satisfactory and can move to the production since the both accuracy scores are 0.99 which is extremely high.Performance of the model depends of the problem what we are trying to solve. I recommend both models as they perform very similarly.



