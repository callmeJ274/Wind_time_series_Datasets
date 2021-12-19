# Wind_time_series_Datasets
Toy Dataset is from  https://aml.engr.tamu.edu/book-dswe/dswe-datasets/ <br />
We only tested data and build the veriest basic model with BigDL library for distributed system and the original colab code can be get from: https://bigdl.readthedocs.io/en/latest/doc/UserGuide/notebooks.html <br />
My hand just get dirty a little, there are many paradigms for predict time series data, try it on the previous website I've listed. That's all you need to kick off your interest in Time series data or other tasks applied in BigDL library.
 
Files begin with tcn_ and LTSM_ we ran to test predict WindSpeed, Power by time 
We set gen_dt_feature(features = 'all') to make use of all time features both in 2 Problems: 1- Predicting WindSpeed and 2- Predicting Power by time+ WindSpeed
