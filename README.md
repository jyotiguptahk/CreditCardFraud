# CreditCardFraud
 This project is for the kaggle competition related to Credit Card Fraud. The aim of the project is to predict the probability that an online transaction is fraudulent. The data is provided by the world’s leading payment service company, Vesta Corporation. More details of the competition can be found [here](https://www.kaggle.com/c/ieee-fraud-detection/). 

### Exploratory Data Analysis
<img src="target.png" width="400px">

0.03% of the cases are fraud - a very skewed dataset. Techniques such as undersampling, oversampling or SMOTE can be used to get better results. Also, the evaluation metric should take into account the skewness of the dataset.

<img src="transactiondt.png" width="600px">

Transaction Dates do not overlap between the train and test dataset. Time based split can be used in cross validation of models.

<img src="transactiondt.png" width="600px">

Distribution of Transaction Amounts