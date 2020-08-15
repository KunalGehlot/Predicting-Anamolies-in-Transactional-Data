# 🚨🚨🚨 Credit-Card-Fraud-Detection 🚨🚨🚨
Many banks use Machine Learning to detect frauds in credit card transactions, but how does it work? Let's have a look at it 🧐

# Synopsis 📝

Since the early 2010s, major banks have used anomaly detection – an AI technique for identifying deviations from a norm – for automating fraud, cybersecurity, and anti-money laundering processes. According to [AI opportunity Landscape research](https://emerj.com/ai-opportunity-landscape-finserv/) by the [Emerj](https://emerj.com/), *approximately 26% of the venture funding raised for AI in the banking industry is for fraud and cybersecurity applications, more than any other use-case category.*

# What is Fraud Detection ⁉

Fraud detection is a set of activities undertaken to prevent money or property from being obtained through false pretenses. Fraud detection is applied to many industries such as banking or insurance. In banking, fraud may include forging checks or using stolen credit cards. Other forms of fraud may involve exaggerating losses or causing an accident with the sole intent for the payout.

Banking Fraud has been an ever-developing issue with enormous outcomes to banks and clients the same, both regarding monetary misfortunes, trust and believability. According to the Nilson report, it is foreseen that card fruads alone would add up to an astounding $30 billion worldwide by 2020. Additionally, with the innovation disturbance in both banking and installments (because of a plenty of installment channels like credit/charge cards, cell phones, kiosks), the quantity of exchanges has expanded exponentially as of late. Fraudsters have additionally gotten incredibly shrewd, receiving innovatory fraud strategies. Accordingly it has intensified the issue.

# Fraud detection techniques ✅

Fraud detection can be separated by the use of statistical data analysis techniques or artificial intelligence (AI).

Statistical data analysis techniques include the use of:

- Calculating statistical parameters
- Regression analysis
- Probability distributions and models.
- Data matching

AI techniques used to detect fraud include the use of:
1. Data mining - Which can classify, group and segment data to search through up to millions of transactions to find patterns and detect fraud.
2. Neural networks - Which can learn suspicious looking patterns, and use those patterns to detect them further.
3. Machine learning- Which can automatically identify characteristics found in fraud.
4. Pattern recognition- Which can detect classes, clusters and patterns of suspicious behavior.

We will be focusing uing Machine Learning to detect fraud.

# Challenges faced during fraud detection 💫

 - Enormous number of transactions and data processed every day. 
 - 99.8% of transactions are not fraudulent which makes it hard to extract and learn features for fraudulent ones, making the data imblaanced.
 - Finding real dataset as it is mostly kept private and safe.
 - Misclassified data as not every fradulent transactions are being reported and caught.
 - Adaptive techniques used against the model by the scamemrs.

# Dataset

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions

It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# References 🔍

1. [fraud detection, definition](https://searchsecurity.techtarget.com/definition/fraud-detection)
2. [AI-Based Fraud Detection in Banking – Current Applications and Trends](https://emerj.com/ai-sector-overviews/artificial-intelligence-fraud-banking/#:~:text=Banks%20can%20use%20predictive%20analytics,involve%20a%20separate%20processing%20service.)
3. [Credit Card Fraud Detection in Python using Scikit Learn](https://medium.com/analytics-vidhya/credit-card-fraud-detection-in-python-using-scikit-learn-f9046a030f50)
4. [Fraud Detection in the Banking Industry and the Significance of Machine Learning](https://medium.com/engineered-publicis-sapient/fraud-detection-in-banking-industry-and-significance-of-machine-learning-dfd31891a0b4)
5. [ML | Credit Card Fraud Detection](https://www.geeksforgeeks.org/ml-credit-card-fraud-detection/)
6. [Credit Card Fruad Detection Dataset: Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud/data#)
7. [Kaggle: Dealing with imblaanced datasets](https://www.kaggle.com/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets)
