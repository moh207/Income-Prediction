# Income-PredictionThis Dataset Consists of U.S citizens of different demographics with low income (less than 50k) and high income (more than 50k).

Different demographic and social conditions affect citizens income,
We could make use of data provided and detect patterns in citizen demographics to predict if their income will likely exceed 50k !

-   Why? 

Predicting customer income applications would include offering customized bundles and offers for different users (i.e. Premium packages for higher income customers and vice versa)

Methodology![image](https://github.com/user-attachments/assets/a7f75c47-c332-460d-ab0d-02ff20f83ac3)
Problems faced with Data:
Data had almost no outliers or missing data, however small challenges with data handling was:

Bias of data sampling(i.e. males were twice as much as females )

Some values were capped to maximum value (working hours and capital gain)

Class imbalance 

# Results
Running multiple models and configurations comparing model F1 scores and other metrics, 
LGBM model has achieved the best score of 92% F1 score

Shown is Confusion metrics with Actual V.s. Predicted values

![image](https://github.com/user-attachments/assets/cda5bb73-ad22-471f-93cd-4e6a85bf30b1)







