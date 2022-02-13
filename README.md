# credit-card-fraud-detection

The idea of the project is to detict fraud transactions by train classification model that fit this huge
data and apply them into multiple transaction to check whither it's fraud or not.<br><br><br><br>

## DATASET
This dataset contains credit card transactions for fictitious users resident within the United States,
but who travel the world in making purchases.<br>
This dataset has a header line followed by transactions -- with one line per transaction. The header
describes the fields of each transaction, which are similar to the fields in a monthly credit card
statement, e.g. (1) date and time of purchase, (2) merchant name, and (3) merchant location (city,
US state, US zipcode -- with US state replaced by country name for purchases made outside the
United States). Another field is the MCC (Merchant Category Code) -- a number from 1 - 9999,
which describes the broad area of the merchant, e.g. groceries, clothing, hair care, jewelry, etc.<br>
These MCC values are standard values from the credit card industry.<br>
The final columns are "Errors" and "Is Fraud". The "Is Fraud" column is the text string Yes when
transactions are fraudulent, i.e. made with a stolen card and the text string No when transactions
are made by the legitimate owner of the card. This "Is Fraud" baniry values that hold only yes or
no, whenever training an unsupervised model to detect fraud, and later when assessing the
accuracy of fraud inference.<br>
The "Errors" field enumerates whether a problem like "Technical Glitch", "Bad PIN", "Insufficient
Funds", etc occurred. A blank value for "Errors" indicates no errors were present.<br>
The "User" field in the first column is a numeric index from 0 - 1999 indicating which of the 2000
users generated each transactions. The "Card" field in the second column is similarly an index
among all of the credit (and debit) cards owned by "User". The transactions in the file are ordered
as follows: By User By Card of Use<br>
