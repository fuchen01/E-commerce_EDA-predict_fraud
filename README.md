# E-commerce_EDA-predict_fraud

he goal of this project is to build a machine learning model that predicts the probability that the first transaction of a new user is fraudulent.

here is the data variable explaination:

user_id : Id of the user. Unique by user

signup_time : the time when the user created her account (GMT time)

purchase_time : the time when the user bought the item (GMT time)

purchase_value : the cost of the item purchased (USD)

device_id : the device id. You can assume that it is unique by device. I.e., same device ID means that the same physical device was used for the transaction

source : user marketing channel: ads, SEO, Direct (i.e. came to the site by directly typing the site address on the browser)

browser : the browser used by the user

sex : user sex: Male/Female

age : user age

ip_address : user numeric ip address

class : this is what we are trying to predict: whether the activity was fraudulent (1) or not (0)

