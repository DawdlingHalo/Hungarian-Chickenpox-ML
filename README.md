# Dataset Source
Hungarian Chickenpox is a spatio temporal dataset created by Benedek Rozemberczki. I have obtained this dataset from UCI Machine Learning repository and will be implementing variety of forecasting including ML. 

---

# Dataset Analysis
The shape of dataset is **521 x 21**. Attributes are weekly counts of chickenpox cases in Hungarian counties. Since it has more than one column , so we have a multivariate dataset. We have 20 counties and one column for the date.

--- 

# What the repository contains ?
I will be starting from scratch , i.e , starting from basic models to more complex models and increase the complexity as we progress forwards. 

Hungarian Chickenpox dataset is a  spatio-temporal dataset of weekly chickenpox cases from Hungary. It contains county-level adjacency matrix and time series of the county-level reported cases between 2005 and 2015. 

---

# Task
Our task is to forecast the future values by splitting dataset into two parts. Data is split into training and testing set .

Agenda of project is to create two kinds of models:
1.  Nation level case count prediction
2.  County level case count prediction


First we will apply our model for nation level case count prediction. The model created will be unvariate forecasting model. 

<!-- (Models to implement:
1.   Naive Forecasting
2.   Moving Average
3.   Basic Dense layer model
4.   RNN
5.   CNN) -->
