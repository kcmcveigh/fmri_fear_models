# fmri_fear_models

This is the code from Yiyu Wang's and I conference presentation at SANS this year. This code implements a set of analyses comparing how dynamic models (LSTMs) compare in terms of predictive performance to static classical ML models (SVR). Our findings show that dynamic and static models perform similiarly suggesting that at least in this somewhat limited context (the input data was 20 seconds of fMRI data, and the fear ratings were provided just once at the end of the video) it doesn't seem like dynamic information, as modeled by the LSTM improves prediction of fear experiences. 

Unfortunately all the data is not yet publically available until the first set of papers on the data is published. 
