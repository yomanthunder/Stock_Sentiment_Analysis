
# STOCK SENTIMENT ANALYSIS USING PYTHON

 this is a project made inorder to create a strategy based on the daily sentiments such as new articles etc. and make prediction on whether the stock would soar or fall.

 


## WHATS THE STRATEGY !!!

I have planned to test my strategy on BERSHIRE HATHWAY, NIKE, AND VISA. Hence I have collected nearly a months old data off all the all the three stocks. As there are various sentiments that are out in a day I would be trading on every positive or negative sentiment I have come across.

If a positive sentiment is encountered and soar in prices in expected I would buy a share in that stock on that day. Here multiple positive predictions would just increase the number of shares I buy. 

If a negative sentiment is encountered and a dip in prices is anticipated I would short a share of that stock on that day.Here multiple negative predictions would just increase the number of shares I short. 

hence i would be placing orders every day only if a +1 or -1 is encountered.


## MACHINE LEARNING
 
 Here for the prediction part I have used Decision Trees so after training it on around 20 stocks with their daily trends mapped with their particular sentiments.

### NOTE
 here in the project i have combined all the data of the three testing stocks into a single dataset hence it should not be confused for a single stock. While on some days we have both positive news and negetive news of a company. here as per the strategy orders are placed keeping in mind the net sentiment of the day(sum of all sentiments)  and the decision would be take based on that net value. these calculation were made a bit different in the notebook so follow this note. Anyway the end result would result in the same amount of return.


 ## PORTFOLIO METRICS

# STOCK SENTIMENT ANALYSIS USING PYTHON

 This is a project made in order to create a strategy based on the daily sentiments such as new articles, etc., and make predictions on whether the stock would soar or fall.

 


## WHATs THE STRATEGY !!!

I have planned to test my strategy on BERSHIRE HATHWAY, NIKE, AND VISA. Hence I have collected nearly a months old data off all the all the three stocks. As various sentiments are out in a day I would be trading on every positive or negative sentiment I have encountered.

If a positive sentiment is encountered and soar in prices as expected, I would buy a share in that stock on that day. Here multiple positive predictions would just increase the number of shares I buy. 

If a negative sentiment is encountered and a dip in prices is anticipated I would short a share of that stock on that day. Here, multiple negative predictions would just increase the number of shares I short. 

hence i would be placing orders every day only if a +1 or -1 is encountered.


## MACHINE LEARNING
 
 Here, for the prediction part, I have used Decision Trees, so after training it on around 20 stocks with their daily trends mapped with their particular sentiments.

### NOTE
 here in the project, I have combined all the data of the three testing stocks into a single dataset; hence, it should not be confused with a single stock. On some days, we have both positive news and negative news about a company. here, as per the strategy, orders are placed keeping in mind the net sentiment of the day(sum of all sentiments), and the decision would be taken based on that net value. these calculations were made a bit different in the notebook, so follow this note. Anyway, the end result would be the same amount of return.


 ## PORTFOLIO METRICS


 SHARPE RATIO

 return_per_month :  0.038460095069643874
std_dev_returns :  0.01656321216763425
sharpe_ratio :  1.5895266053965686


WIN RATIO

num_positive_returns :  70
num_negative_returns :  57
win ratio: 1.2280701754385965

NET RETURNS AFTER STRATEGY

net returns in strategy:  23972.22939300537

TOTAL NUMBER OF TRADES

total number of trades :  127(here each trade is buying each stock or shorting each one)

ACCURACY OF THE MACHINE LEARNING MODEL
76%





 SHARPE RATIO

 return_per_month :  0.038460095069643874

std_dev_returns :  0.01656321216763425

sharpe_ratio :  1.5895266053965686


WIN RATIO

num_positive_returns :  70

num_negative_returns :  57

win ratio : 1.2280701754385965

NET RETURNS AFTER STRATEGY

net returns in strategy :  23972.22939300537

TOTAL NUMBER OF TRADES

total number of trades :  127(here each trade is buying each stock or shorting each one)

ACCURACY OF THE MACHINE LEARNING MODEL

76%


## DRAWBACKS

-  Vader being not that accurate using models such as roberta would result in much better sentiment scores which further makes the model more accurate.
- More accurate the sentiment scores more accurate the machine learning model would be.
- Unavailability of news/social media sentiments of higher series width for free which has restricted our dataset for training and has caused a pinch of inaccuracies in calculating the metrics.
- As sentiments are not the only reason for market movement sentiment analysis result should be combined with results of other technical indicators inorder to improve on returns and reduce risks.

