# Earthquake Prediction using Long Short Term Memory Networks

Our project utilises machine learning to predict Earthquakes from Seismograph data. 

We can access the data from the source:- ds.iris.edu/data/sources.htm, which is a time series based dataset which is based on historical seismograph readings. Using predictive machine learning models, using the previous data, we hope to predict the probability an Earthquake can occur in the near future and predict it's magintude. This can help weather organizations to have prior knowledge of the occurrence of Earthquake can help in measures against the same and an earlier warning to the peopl can save several lives.


Since the data from seismograph is time series based, it is not possible to use normal neural network which can help in classification as well as the regression part. Classification can be used to identify weather an earthquake is likely to occur or not. And regression is used to predict the magnitude of the earthquake.
Since this is a time series based dataset, we can't use a vanilla neural network as the prediction using it is based solely on the current sample and not the previous and/or the next samples. Hence, in order to tackle this probelm - we use a recurrent neural network which allows likelihood to be based on the previous samples. Hence, the output is based on the complete signal.
However, recurrent neural networks face the problem of vanishing gradient's which doesn't allow proper optimization. So, we use a LSTM network to tackle the problem.

This project can provide a prior knowledge and help in preperation to tackle the problems that occur during an earthquake. We plan to work further on this problem by having various other aspects involved to predict the posibility of an earthquake.
