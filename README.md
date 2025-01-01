# Predict
Prediction of project completion using monte-carlo and linear regression

Using "remaining" data points, forecast completion date:

<img width="1076" alt="image" src="https://github.com/user-attachments/assets/56b96c82-87e5-4b8a-bd37-a7826cf7bb5e" />

Two methods are used to forecast:

  1. Linear regression - Create a best-fit line and see when it gets to zero (full content completed)
  2. Monte Carlo - Roll the dice daily on completion for that day till all content is completed. Do this many times and generate a distribution of completion dates

# Using

Just load the html file in a modern browser.

Some sample data is provided in the page, but you can upload your own data from a csv file using the following format:

```
  yyyy-mm-dd,remaining
  yyyy-mm-dd,remaining
  ...
```

See sample file Project_X.csv

# License

Creative-Commons 1.0

Attribution to Sagi Smolarski - sagism@gmail.com
