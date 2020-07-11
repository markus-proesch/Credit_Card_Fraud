# Fraud Credit Card Project w/ manual sub-sampling

### Context and data
Credit Card fraud happens every day and as consumers we put the responsibility on the credit card provider to keep our cards and money safe. For credit card companies it is important to be able to recognize fraudulent credit card transactions in order to reject them, but at the same time rejecting a transaction that is not-fraudulent can result in unsatisfied customer and potentially loss of that client. It's a fine line!

The dataset I have worked with contains transactions made by credit cards in September 2013 by european cardholders. The dataset presents transactions that occurred in two days, where 492 are fraudulent out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

### Additional information
The dataset contains only numerical input variables which are the result of a PCA transformation. Even the feature/variable names have been deleted due to confidentiality issues. The only 2 features that have not been standardized are "Time" and "Amount". The "Time" feature is given in seconds from the first transaction of day one.

### The job
The task is to develop a model that can recognize/predict if a transaction is fraud (1) or not fraud (0). I will not be using the Near Miss under-sampling technique or the SMOTE over-sampling technique to balance the dataset. Those will most likely be featured in a later project.
