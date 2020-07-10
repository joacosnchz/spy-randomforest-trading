# Abstract
This trading strategy uses Random Forest Classifier in order to create buy or sell orders for the $SPY ETF outperforming buy &amp; hold strategy

# Description
The model is trained using previous 30 days as features and classified using the upcoming 5 days. The accuracy could be better and the confussion matrix shows some big false-positives, but as the equity curve shows it can still be profitable.

![Equity Curve](https://github.com/joacosnchz/spy-randomforest-trading/blob/master/equity_curve.png "Equity Curve")

Looking forward to improve the model performance

# Sources
https://www.quantstart.com/advanced-algorithmic-trading-ebook/
