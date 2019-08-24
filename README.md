# Time Series Analysis on the Power-LCL dataset
#### What will I look into?
- Skewness and Kurtosis of the distribution of power consumed
- Quarterly, Yearly, Monthly consumption patterns
- If there is a difference in the consumption based on DayOfWeek

# Data Preprocessing
- Clearing of redundant columns
- As mentioned in the problem statement that we have to perform an analysis on the hourly data hence we have to resample it.
- The processed file is ultimately stored in a different csv file

# LSTM for Time Series Analysis


---


The task is to predict the electricity usage of the households using the data provided. 
- LSTM or a Long Short Term Memory units is a type of Recurrent Neural Network that is capeable to remember past values inputted to the network.
- I will be going to use a multi-layered LSTM RNN to predict an unknown value that is preceeded by a sequence of lookback values that are inputs to the LSTM.
