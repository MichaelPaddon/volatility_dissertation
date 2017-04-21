# Applying machine learning to the forecasting of stock price volatility
An MBA dissertation by Michael Paddon

## Synopsis
Volatility is an intrinsic property of risk bearing assets and accurate
forecasting of this variable is fundamental to effectively managing risk. There
exists a rich literature in this domain and many forecasting models are extant.
Machine learning techniques have been applied successfully to this problem.
In particular, neural nets have been constructed and shown to outperform
historical, implied and autoregressive conditionally heteroscedastic volatility
models. These neural nets solutions, however, have proven complex in
practice to configure optimally. The process has been characterised as “more
of an art than science” (Hamid and Iqbal, 2004).

The research hypothesis for this project is that recent advances in machine
learning and deep neural nets allow the construction of a high performance
volatility forecasting model that is easier to configure correctly and more
stable against changes in model hyperparameters or inputs. An LSTM based
recurrent neural network architecture is proposed as suitable for time series
forecasting. Data from the CRSP US Stock Database and Google Trends is
used to construct training patterns and testing patterns and the model is
subjected to fifteen different training scenarios. These scenarios vary the
model hyperparameters and inputs, and compare the consequent
performance against three common benchmark forecasting models.

The model is found to perform well in most scenarios, be easy to configure
and demonstrates good resilience to hyperparameter and input changes. In
the highest performing configurations, the model demonstrated an RMS error
rate less than 50% of the next best performing benchmark.
