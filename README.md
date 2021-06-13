# FX-LSTM
FX Analysis using LSTM
This project looks at GBP and AUD. We attempt to craft out some strategies and run them through a LSTM classification model to see if new insights can be gained.
The data set is from 2020 and consists of 1 minute data
As the initial model didnt work well, we ran 2 more alternative LSTM models - a regressor and a forwrad step regressor 

There are 4 scripts for this project. Capstone Project_1min data is the script for the initial LSTM classifier model which did not do well. LSTM_Regressor_GBP runs the close prices against SMA50 and RSI for GBP. LSTM_Timesteps_GBP runs the script for a simple forward step model for GBP. LSTM_Timesteps_Improved_GBPAUD runs the script for a LSTM forward step model (with more layers and epochs) for GBP and AUD, and has better results.

I hope you enjoy my little project! 
