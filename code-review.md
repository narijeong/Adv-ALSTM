# Codeflow 

## ALSTM: python pred_lstm.py -l 5 -u 4 -l2 1 -f 1
- *KDD17* includes longer history ranging from Jan-01-2007
to Jan-01-2016 of 50 stocks in U.S. markets.
- parameters
* 1. p = data path(kdd data)
* 2. l = 15 lag (length of history)
* 3. u = 16  number of hidden units in lstm
* 4. l2 = 0.001 alpha for l2 regularization
* 5. f = 1 use fixed initialization