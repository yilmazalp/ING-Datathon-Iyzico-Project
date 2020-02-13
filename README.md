# ING-Datathon-Iyzico-Project
This competition is organized with the cooperation of ING, iyzico, and the Student Club of Operational Research at Bogazici University. 
iyzico founded in 2013, iyzico is the brainchild of German-born Turks, Barbaros Özbuğutu and Tahsin Isın, who moved from Germany to Turkey to set up the business. Started out with 3 people, iyzico is now Turkey’s fastest growing fintech company composed of more than 130 people providing secure payment solutions to online sellers of different sizes as well as online shoppers.

In this challenge we will encounter with payment transactions fraud case. Solution of fraud cases are one of the most popular machine learning application in fin-techs. When we consider how hard to find fraud data, we hope you enjoy this case.

## File descriptions

- train.csv - the training set, Every data point refers a transaction. Our data have been anonymized to protect our customer’s privacy. During that process we used method which keeps patterns but changed business insides.
- test.csv - the test set, As an end product you need to predict these transactions.
- samplesubmission.csv - a sample submission file in the correct format, Example of how you will submit your results.

P.S: Some of our emails are dummy. You can detect them by probabilistic programming methods.

## Data fields
- BASKETPAIDPRICE - Price of transaction
- BASKETINSTALLMENT - Number of instalments of payment
- BASKETPAYMENTCHANNEL - Channel of payment
- BASKETPAYMENTSOURCETYPE - Source of payment
- BASKETISTHREEDS - Is 3DS used in this transaction
- BASKETREGISTERCARD - Is registered card used in this transaction
- BASKETHASVIRTUALITEM - Is item in basket virtual? (ie. game Money)
- CARDTYPE; - Type of card
- CARDASSOCIATION - Association of card
- EMAIL - Email of user. (Emails replaced with numbers. Every number refers to uniq email.)
- CARDBANKID - Bank of card
- MERCHANT_ID - Id of merchants.
- ISFRAUD - Is that transaction fraud.
