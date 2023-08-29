# CreditRisk_HW20

WRITTEN SUMMARY & ANALYSIS

The Objective of this analysis was to determine the accuracy of bank loans statuses using prediction modeling.

The bank loan data provided over 77000 individual loans. These loans are classified as one of two things under the "loan_status" category, "High Risk" or "Healthy," with 0 representing a healthy loan, and 1 representing a high risk loan. The analysis attemptes to determine the accuracy of a linear regression to determine the loan status. With the "loan_status" as the y variable and the rest of the data contained within the x variable, both variables were used in a training and testing model.

Once the data was prepped, the "train_test_learn" module was used to split the data. The data was fit for the LogicRegression model, and the now fitted model was used to create predictions. The accuracy of the predicitions of loan status using the this model was approx. 95%

However, when the classification report is reviewed more closely, we can determine that the regression model produces a prefect score when predicting "Healthy Loan" status, while the model was only capable of predicting "High Risk Loan" status with 85% accuracy. Also, when evaluating items that the model did not predict for was only 88% accurate.

While the model is highly accurate based on "Healthy Loan" predictions, and the "Balanced Accuracy Score," the model is somewhat less accurate when regarding "High Risk Loan" status. Whether the accuracy scores the model produces will be reproducable or are within an acceptable limit will require firther discussion.
