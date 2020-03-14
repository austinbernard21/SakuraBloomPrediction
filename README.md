# SakuraBloomPrediction
simple neural network to predict sakura bloom dates in tokyo

Bloom dates and tokyo weather data collected from Japan Meteorological Agency.

Data is 57 years divided by days with 11 different features. I decided with such a small sample size, i had to reduce the features so i used an average of each month and only fed in the first two months for each sample, after cutting out some features that are highly correlated. The first two months were used because bloom dates generally lie in March or April. Comparing to a random forest model, i was able to obtain 20% higher accuracy on the test set with a simple neural network. With only 51 training samples and 5 test samples, there was a good amount of bias in the model but i think with a higher sample size, this neural network is simple enough and predictive enough to make accurate predictions of the week of the year the cherry blossom flowers will bloom in the city of Tokyo.
