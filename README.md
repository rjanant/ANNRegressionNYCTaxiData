# ANNRegressionNYCTaxiData

The goal is to estimate the cost of a New York City cab ride from several inputs. The inspiration behind this code along is a recent Kaggle competition.

The Kaggle competition https://www.kaggle.com/c/new-york-city-taxi-fare-prediction provides a dataset with about 55 million records. The data contains only the pickup date & time, the latitude & longitude (GPS coordinates) of the pickup and dropoff locations, and the number of passengers. It is up to the contest participant to extract any further information. For instance, does the time of day matter? The day of the week? How do we determine the distance traveled from pairs of GPS coordinates?

For this exercise we've whittled the dataset down to just 120,000 records from April 11 to April 24, 2010. The records are randomly sorted. 


We can use the model to predict the taxi fare by providing the new data records. 

For the test data - on average, predicted values are within ±$3.63 of the actual value.
