Loan Repayment Prediction Using Logistic Regression

Group: ASDS 12 Bachelors
Khandoker Toufiq Amin Rumi (Team Leader, 20231235)
Md. Saifullah (20231204)
Moshiur Rahman (20231233)
Kazi Muhtasim Rafid (20231224)

Course: Introduction to Data Science with Python (WM-ASDS04)
Masters in Applied Statistics and Data Science under Weekend Program
Department of Statistics and Data Science
Jahangirnagar University, Savar, Dhaka.

Problem Statement:
Will the borrower pay back the loan ?

Bachkground:
Defaulted loans in the banking sector of Bangladesh reached an all-time high at Tk 1.45 trillion (Bangladesh Bank, December 2023)
Half of the defaulted loans were risky, the banks failed to assess the risk (Chowdhury & Dhar, 2022)

Objectives:
1. Develop regression models to predict the likelihood of loan repayment based on borrower attributes.
2. Determine the relative importance of different borrower characteristics in predicting loan repayment.

Dataset(MetaData):
1. Data Collected by LendingClub.com
2. 9578 Records of Borrower
3. Time Period 2007-2010
4. USA based Platform

Dataset(Variables):
1. Credit Policy
2. Purpose
3. Interest Rate
4. Installment
5. Logarithm of Annual Income
6. Debt-to-Income Ratio
7. FICO Credit Score
8. Days with Credit Line
9. Revolving Balance
10. Revolving Line Utilization Rate
11. Inquiries in the Last 6 Months
12. Delinquencies in the Last 2 Years
13. Public Record

Datatypes:

![image](https://github.com/user-attachments/assets/fac85abf-264b-4409-a8ec-ee0fed95f5cc)

Descriptives Statistics:
![image](https://github.com/user-attachments/assets/f825e44e-3abf-4683-b7d3-5c554da5acf2)
![image](https://github.com/user-attachments/assets/f7015f10-00d5-4649-9e23-717c55454608)
![image](https://github.com/user-attachments/assets/f2a6c264-0985-4816-8125-b66f3f3e9d6f)
![image](https://github.com/user-attachments/assets/6f52123c-4721-4a06-b354-dbae18193908)
![image](https://github.com/user-attachments/assets/fd9c42f2-e8cc-4a30-a03b-70136814d363)
![image](https://github.com/user-attachments/assets/3574ef70-d965-425f-aacb-acea2d7e88c2)
![image](https://github.com/user-attachments/assets/5a1533f5-0192-463a-baff-c258e9871e56)
![image](https://github.com/user-attachments/assets/3bafeeb7-e9f7-468a-bea1-ff873cab79ac)
![image](https://github.com/user-attachments/assets/047cb6ce-bc39-40c1-a895-a275d715f32e)
![image](https://github.com/user-attachments/assets/9fe37043-2ebe-43d1-bad6-42249892b5c1)
![image](https://github.com/user-attachments/assets/b3ea22c4-eeb0-4d72-a0a2-93a23ed22ba6)
![image](https://github.com/user-attachments/assets/d2cbd4d4-8b7d-4bfc-8268-be80018fc393)
![image](https://github.com/user-attachments/assets/23ac4362-6aeb-4019-9901-3f1b292dc65a)
![image](https://github.com/user-attachments/assets/71818f3f-a674-4c94-8d56-3ee401cc1cdc)
![image](https://github.com/user-attachments/assets/47a9aa40-22a3-4cb4-874e-6868954f733a)

Model:
Logistic Regression 
Accuracy 87.7 % 

Findings:
1. The  ML Model’s Accuracy is 87.7 % and it is implying that it correctly predicts loan eligibility for approximately 87.7% of the test instances.
2. A precision of 0.87 indicates that out of all instances predicted as eligible for a loan, approximately 87% are indeed eligible.
3. A recall of 0.89 suggests that the model captures approximately 89% of all eligible loan applicants.
4. In this case, the MSE is approximately 0.123. Since MSE values closer to 0 indicate better model performance, this indicates that, on average, the model's predictions have a squared error of about 0.123.
5. Confusion Matrix:
  True Positive (TP)  - 158
  False Positive (FP) - 25
  False Negative (FN) - 21
  True Negative (TN)  - 170

Evaluation:

![image](https://github.com/user-attachments/assets/7560afc6-64ad-4683-aa16-e8357d26b88b)

Conclusion:
The logistic regression model shows potential for accurately predicting loan eligibility based on the provided features. Future work could involve further refinement of the model, exploration of additional algorithms such as Random Forest and Boosting, and incorporation of additional features to enhance predictive performance and robustness. Overall, leveraging machine learning techniques offers a promising approach to optimizing loan approval processes and minimizing the risk of default for lending institutions.

Reference:
Chowdhury, R., & Dhar, B. K. (2012). The perspective of loan default problems of the commercial banking sector of Bangladesh: A closer look into the key contributory factors. University of Science and Technology Annual (USTA), 18(1), 71-87.



















