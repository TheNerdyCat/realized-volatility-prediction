# Optiver Realized Volatility Prediction
Apply your data science skills to make financial markets better

## Description
Volatility is one of the most prominent terms you’ll hear on any trading floor – and for good reason. In financial markets, volatility captures the amount of fluctuation in prices. High volatility is associated to periods of market turbulence and to large price swings, while low volatility describes more calm and quiet markets. For trading firms like Optiver, accurately predicting volatility is essential for the trading of options, whose price is directly related to the volatility of the underlying product.

## Evaluation
Submissions are evaluated using the root mean square percentage error, defined as:

<img src="https://github.com/TheNerdyCat/realized-volatility-prediction/blob/main/input/img/rmspe.png" height="100">

## Submission
For each row_id in the test set, you must predict the target variable. The file should contain a header and have the following format:
```
row_id,target
0-0,0.003
0-1,0.002
0-2,0.001
```

## Background Knowledge
Optiver's data scientists have created a [tutorial notebook](https://www.kaggle.com/jiashenliu/introduction-to-financial-concepts-and-data) debriefing competition data and relevant financial concepts of this trading challenge. Also, Optiver's online course can tell you more about financial market and market making. Access the video by following the link below:

[![Introduction to financial markets and instruments - Kaggle edition](https://img.youtube.com/vi/ZDF2LDsiLBs/0.jpg)](https://www.youtube.com/watch?v=ZDF2LDsiLBs)
