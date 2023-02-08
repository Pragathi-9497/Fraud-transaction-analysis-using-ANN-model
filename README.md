# Fraud-transaction-analysis-using-ANN-model
### Problem Definition : Fraud detection

Everyone is exposed to financial fraud if you're selling or buying something online providing financial services or simply processing tons of payments we face fraud risks every day for. businesses scams are especially scary because
we are not only losing money but also customers who may no longer trust banks. Detecting and preventing fraud is essential and there are two approaches to catching fraud:
1. Using rule based system.
2. By machine learning.


Rule-based systems work on detect fraudulent encounters and looks for similarities between accounts that committed fraud using analytics
<br>

**For example:** finding that many fraudulent accounts were registered in asia while making the trips in the biggest cities around the world like london or new york. These accounts were also created within mere seconds from one another and has gibberish in their email addresses and often use the same credit card the geolocation of account creation revealed.

<br> 
Machine learning based systems are extremely good at finding patterns that humans can't. Machine learning knows very nuanced distinctions between normal and fraudulent activities and finds way more signals than human analysts do.

#### Step 1: Understanding what is normal.
Frauds don't happen that often and we don't want to be alerted about suspicious behavior all the time. We need to minimize false positives like people who simply want to use their credit card on vacation so a model has to know what behavior is normal to identify what deviates from that normal and what signals point to fraudulent activity.

It's first trained on historical data historical data are past transactions both fraudulent and not each transaction stores all different attributes. Features like exact time of transaction,  purchase amount, credit card number, shipping address  and sometimes several attributes are combined to create a feature like the transaction date and the date of the customer's past transaction. 

#### Step 2: Finding anomalies 
One of the most common targets of financial fraud today are e-commerce merchants because opening new accounts or accessing customer accounts is not that hard online stores are prone to scam. Fraud is also solved by distinguishing normal customer behavior from abnormal and this is called **behavioral analytics**. All customers are segmented into groups so the system can easily identify if one customer's behavior fits the behavior of the group.

#### Step 3: Eliminating mistakes 
Many advanced fraud detection systems are effective in 99 of cases the remaining 1 are errors false positives and false negatives. False positives occur when the model detects fraud where there's none false negatives are fraudulent transactions that slip through but since there are many more valid transactions than fraudulent ones increasing the effectiveness of
the model. This will also boost the number of false positives which is a hit to customer satisfaction a card declined can cost a customer.

### Approach

#### Model used : Artificial Neural Network (Deep Learning)


A machine learning model calculates a fraud score an algorithm doesn't make decisions based on a yes or no answer. It actually returns the probability of the fraud as a customer's purchase activity is rarely squeaky clean. The system calculates how likely it is that this exact purchase is fraud when the fraud score is low. The purchase is approved when high the system flags the transaction as suspicious to be reviewed by the store or the customer.

####  Why ANN ?
This problem is handled by using Deep neural networks neural networks. They allow us to find non-linear relations between a massive amount of data points without manually selecting features these relations can be so nuanced that we would fail to understand the logic behind the final decision this complex processing allows neural networks to learn from much more pieces of information than traditional machine learning models.
