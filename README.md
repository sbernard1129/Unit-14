# Unit-12

## Which model has a lower loss?

The LSTM RNN model was ran testing the Fear and Greed Index and closing prices to predict pricing. Different windows of lookback days were used.

The loss for each test is listed below:

FNG\
1 Day: 0.08495\
2 Days: 0.09071\
3 Days: 0.09196\
4 Days: 0.09378\
5 Days: 0.09126\
6 Days: 0.09536\
7 Days: 0.09710\
8 Days: 0.09313\
9 Days: 0.09609\
10 Days: 0.10029

Closing\
1 Day: 0.01171\
2 Days: 0.01687\
3 Days: 0.02240\
4 Days: 0.02462\
5 Days: 0.02565\
6 Days: 0.02597\
7 Days: 0.03042\
8 Days: 0.03111\
9 Days: 0.03086\
10 Days: 0.03241

The Closing prices predictor with 1 day of lookback had the lowest loss.

## Which model tracks the actual values better over time?

The closing prices predictor model tracked the actual values better than the fear and greed index predictor.

## Which window size works best for the model?

A window size of 1 day worked best for predicting bitcoin price.

### Contributors
```
Stephen Bernard
```