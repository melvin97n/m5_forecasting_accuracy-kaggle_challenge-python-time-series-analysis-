# m5_forecasting_accuracy-kaggle_challenge-python-time-series-analysis-
The M5 forecasting(Accuracy) challenge, is a challenge put up by the University of Nicosia which comprises of sales data from 10 Walmart stores in 3 states with 3049 items in the stores. The notebook I have created aims to find a solution that is fairly accurate and not too computationally expensive. The link given at the bottom is a link to the kaggle page where the data can be found( it is too large in size to be uploaded to github). The three files uploaded are the Jupyter notebook itself, the guide for competitors provided by the University of Nicosia for the challenge and a copy of the Jupyter Notebook in html format. To view it in webpage form use the link:
https://htmlpreview.github.io/?https://github.com/melvin97n/m5_forecasting_accuracy-kaggle_challenge-python-time-series-analysis-/blob/master/M5_forecasting.html



M5 forecasting -Accuracy
The M5 forecasting(Accuracy) challenge, is a challenge put up by the University of Nicosia which comprises of sales data from 10 Walmart stores in 3 states with 3049 items in the stores. The objective as given by the host is as follows: The objective of the M5 forecasting competition is to advance the theory and practice of forecasting by identifying the method(s) that provide the most accurate point forecasts for each of the 42,840 time series of the competition. The value 42840 is formed as a result of the hierarchical nature of the problem with each step requiring a solution. The different hiearchies are:

1 Unit sales of all products, aggregated for all stores/states: 1

2 Unit sales of all products, aggregated for each State: 3

3 Unit sales of all products, aggregated for each store : 10

4 Unit sales of all products, aggregated for each category: 3

5 Unit sales of all products, aggregated for each department: 7

6 Unit sales of all products, aggregated for each State and category: 9

7 Unit sales of all products, aggregated for each State and department: 21

8 Unit sales of all products, aggregated for each store and category: 30

9 Unit sales of all products, aggregated for each store and department: 70

10 Unit sales of product x, aggregated for all stores/states: 3,049

11 Unit sales of product x, aggregated for each State: 9,147

12 Unit sales of product x, aggregated for each store: 30,490

Total 42,840

For further details on the competion visit: https://www.kaggle.com/c/m5-forecasting-accuracy/data

In this kernel, we will take a look at this huge dataset,doing EDA,optimizing for lower end workstations and apply computationally inexpensive models(Prophet,SARIMAX) using Colab and Kaggle Notebooks.
