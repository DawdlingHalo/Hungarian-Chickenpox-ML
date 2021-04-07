# Nation level case count prediction
Since we are doing nation level, so we only require one series. This means we total the cases from all counties into a single column. 

All the cases of a particular date have been summed to generate a single value.

---

# Simple_methods

Simple_methods file includes the hardcode methods earlier used to forecast values . This will create a baseline of the score we have to attempt to beat. 

Since we are using MeanAbsoluteError(MAE) as our metric, so the model with least amount of MAE is the best model.

In the file above , we conclude that **170.4** is the best score we can get with the amount of data we presently have.