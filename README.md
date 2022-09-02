# House-Price-Predictions
The goal is estimate a house’s price from a set of features describing the house (number of rooms, size, etc.). The dataset used was from kaggle competition.

The Normal equation we use in session is not working and I predict it is caused by unregulated wights as there are 74 wights in the training data with some being single values and others are huge number so I used Normal regularized equation and the mean absolute error is close to that of sklearn.
