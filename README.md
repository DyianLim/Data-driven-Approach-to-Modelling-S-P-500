# Data driven Approach to Modelling S&P500

## Link: https://dyianlim.github.io/Data-driven-Approach-to-Modelling-S-P-500/Data-driven%20Approach%20to%20Modelling%20S&P%20500.html

_Executive Summary_

The S&P 500 is an American stock market index based on the market capitalizations of 500 large companies having common stock listed on the NYSE, NASDAQ, or the Cboe BZX Exchange. It is one of the most commonly followed equity indices, and one of the best representations of the U.S. stock market. Many people consider it to be a bellwether and leading indicator for the economy in addition to the default vehicle for passive investors who want exposure to the U.S. economy via index funds. Since 1957, the S&P 500 has performed remarkably, outpacing other major asset classes such as bonds or commodities.

In this project, we would like to examine the possible models that help predict the performance of S&P 500 index. This would allow investors (portfolio managers as well as individual investors) to predict the general economic condition and investment climate given the current market conditions. 

We will include both quantitative and qualitative inputs in the model. Quantitative inputs include Fama-French three-factor variables (SML, HML, risk premium), macroeconomic indicators (e.g. US GDP, unemployment rate, inflation index), technical analysis indicators (e.g. relative strength indicator, Z-score, accumulation) and indices for other financial assets or sectors (bond prices, index for emerging markets). Apart from these, market sentiment would also be used as a qualitative input, which can be obtained through tweets.

The first model we have developed is to nowcast the current US GDP. The Real GDP is universally recognized as the best economic indicator in measuring the state of the economy, and thus it has a huge impact on the S&P 500. However, GDP figures for the current quarter are only release 3 months after the end of the quarter, limiting the decision making of investors. Therefore, it would be of great value to nowcast the current GDP and use it in our subsequent regression analysis.

The second model is a text analytics model, where we conduct sentiment analysis on tweets from 300 influential Finance Twitter accounts. With the sentiment values, we can use the market sentiment information to predict S&P 500 performance.

Then, we use regression to determine the best model that gives the highest accuracy in predicting S&P 500.

Lastly, the team will simulate the possible economic condition in 2019 and make use of our final model to determine the possibility of a market crash or boom in 2019.
