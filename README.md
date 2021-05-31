# Abnormal-Volume-Detector

After the crazy KODK surge back in July, I decided to code up a python script that iterates through all tickers at a time, retrieves statistics about them over the past x days and times (numbers can easily be tuned) and gives an alert if the stock's volume has surged x std. deviations from the average over this time period. Useful to get into a stock early.
