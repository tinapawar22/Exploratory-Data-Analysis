# Exploratory-Data-Analysis
Risk analytics  : EDA(numpy , pandas, matplotlib and seaborn libraries)


--dataset has 3 files as explained below: 
1. 'application_data.csv'  contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.


2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused or Unused offer.


3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.

  
  -- When a client applies for a loan, there are four types of decisions that could be taken by the client/company):
Approved: The Company has approved loan Application
Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client, he received worse pricing which he did not want.
Refused: The company had rejected the loan (because the client does not meet their requirements etc.).
Unused offer:  Loan has been cancelled by the client but at different stages of the process.



--Result:
This case study aims to identify patterns which indicate if a client has difficulty paying their instalments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
