##Report 


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


 I consider the both model perform satisfactory and can move to the production since the both accuracy scores are 0.99 which is extremely high. The oversampled model generated an accuracy score of 99% which turned out to be higher than the model fitted with imbalanced data. The oversampled model performs better because it does a exceptional job in catching mistakes such as labeling non-healthy (high-risk) loans as healthy (low-risk). This is analyzed based off of the recall score increasing from the imbalanced model to the oversampled model 0.91 --> 0.99.A lending company might want a model that requires a higher recall because: 

    * healthy loans being identified as a non-healthy loan might be more costly for a lending company since it might cause the loss of customers but it would not be as big of a deal since they have not provided any funds to the customer indicating no loss in terms of money
  
    * non-healthy loans being identified as a healthy loan might surely be more costly for a lending company due to the loss of funds being provided by the lender

Performance of the model depends of the problem what we are trying to solve. 

