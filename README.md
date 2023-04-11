# BremenBigDataChallenge

My code for the Bremen Big Data Challenge 2023. The task was to forecast values of the AWI Helgoland Roads TimeSeries. 
The code is very disorganised at the moment, as I regarded this as an opportunity to play with some time series forecasting tools. 

I used Tensorflow and Keras as well as the Darts library to obtain forecasts. The Neural Network architectures on their own weren't able to achieve promising results. The best performing model was a combination of a simple mean and neural network models. The mean was computed for every individual day from a period of five to four years prior to the prediction year. The neural network consisted of a one to two layer LSTM network. I didn't optimise the neural network as much as would have been possible in the end. So further work on this approach would've probably allowed for even better results.
