# Predicting Earthquake Magnitude
#sgc76, vsm29

Our project is a data analysis project which predicted earthquake magnitude using historical seismic data provided by the National Earthquake Information Center (NEIC) and International Seismological Centre (ISC).
We used a dataset with roughly 20,000 entries, each with 22 variables detailing factors like location, with the earthquakes being magnitude 0.5 and greater in California from June 15, 2022 to December 31, 2022.
We used three main approaches in forming our predictions: an initial ordinary least squares regression model, a polynomial transformation upon it, and a ridge regression regularized model.
We found the polynomial model to likely overfit the data, while the ridge regression model was our best model by a slight margin.
Our models overall provide a good ballpark estimation for earthquakes. In the event that systems are fast enough to record this data in real-time, our models could be used for fairly accurate warning systems.
The biggest issues holding back our models were overfitting due to colinearity, and a lack of data for high-magnitude earthquakes which led to errant predictions at the high end in multiple models.
