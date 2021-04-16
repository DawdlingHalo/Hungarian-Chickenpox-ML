# Nation level case count prediction
Since we are doing nation level, so we only require one series. This means we total the cases from all counties into a single column. Upon observing the graph , we can conclude that we have a trend statinoary dataset . This means that time series does not exhibit a trend. 

All the cases of a particular date have been summed to generate a single value.

---

# Simple_methods

Simple_methods file includes the hardcode methods earlier used to forecast values . This will create a baseline of the score we have to attempt to beat. 

Since we are using MeanAbsoluteError(MAE) as our metric, so the model with least amount of MAE is the best model.

In the file above , we conclude that **170.4** is the best score we can get with the amount of data we presently have.

# Basic_ML_methods

In this file , we have implemented basic Dense layer Sequential Machine Learning models to build a model that can outperform simple_methods and can predict the future values. 

After implementing 2 models , we find that the best score that has been achieved with these models is **174.74289**. Next , we will be seeing how the RNN and LSTM models perform on a small dataset of Hungarian chickenpox.

# Simple_RNN_LSTM

We have applied dataset on RNN and LSTM models. Their score however is not much promising and was not able beat or come close to the baseline of Naive Forecasting. One of the reasons why it did not provide good results is because of size of data. Due to its short size , the model finds difficulty in finding patterns.
