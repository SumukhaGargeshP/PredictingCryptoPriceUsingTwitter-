# Predicting Cryptocurrency Price using Twitter Data
## Goal
The goal of this project is to use Twitter data to analyze fluctuations in cryptocur-
rency value and develop a method to predict future changes. In the last two years,
the market capitalization of cryptocurrency has risen from $200 billion USD from
(Jan 2020) to $1500 billion USD (Apr 2022). Cryptocurrencies are very volatile
and experience price fluctuations on both daily and long-term valuations. An-
alyzing this trend will help in making better investment decisions. Twitter has
around 300 million users who use Twitter as a news source to make purchase de-
cisions.Tweets about cryptocurrency may have an impact in analyzing the price
fluctuations on a day-to-day level. Our results indicate that With this project we
are determining the best approach to predict variations and fluctuations in cryp-
tocurrencies. We were able to solve regression problem with a MAPE of 2.5%.
We have also captured the Bitcoin Price movement with an accuracy of 78% by
framing it as a classification problem. And our results indicate that the major
drivers of bitcoin price are- ‘previous day price’, ‘negative sentiment share’, and
‘volume of tweets’. <br />

## Results
A year long Bitcoin data that was analyzed, had a very high variation with respect to price. The
lowest price was at $29K and highest was at $67K, exhibiting a range of 40K. Along with this,
direction of movement was also fluctuating a lot. Prices going up nearly 50% days and going down
on the other 50%. These variations and frequent fluctuations in data makes it a hard problem to
solve.
With the regression approach, using the quantitative, qualitative aspects of tweets and last 3 days
price trends, allowed to predict the ‘Next day’ price of bitcoins with R-squared value of 0.975,
RMSE of 1440 and MAPE of 2.5%. Statistically, this makes a very robust framework. Average error
rate of 2.5% should be a reasonable estimate for the majority of cases.
But, since the application of this project is in the investment and economic sector, it was imperative
to capture the direction of movement as well. This was achieved through the classification
approach, which involved ‘Price movement up or down’ as the target variable. With the best fitting
model, both accuracy and an F1 score of 78% was achived. This has shown that the ‘previous
day price’, ‘negative sentiment share’, and ‘volume of tweets’ are the major drivers of Bitcoin price.
