# Predict-Spotify-track-popularity-score

# Objective

This project is the last project undertaken at IronHack. It aims at 

•	understanding the song patterns of French artists’ music 

•	digesting the drivers of a song popularity on spotify to build machine learning algorithm and predict song popularity

# Steps

The main steps to predict song popularities are listed below: 

•	creation of my own database: starting from a sample of 12 000 french artists and retrieving their associated 10 most popular songs on spotify and the dominant genre of each artist

•	Retrieve the audio features of each song, their release date, and their presence or not in a Spotify France own playlist, the artists spotify users’ followers

•	Build regressions models to predict track popularity (Linear regression, K-Nearest-Neighbors, Random Forest)

•	Compare accuracy/score of each model and go with the most precise one


Three algorithms were compared in this project, whose results were compared. 
Random Forest is the best performing algorithm for this dataset. It would then be the one going into production.

# Libraries:

pandas, seaborn, numpy

# Future works:

As future works, the below points could be used to increase score of the model in order to use it in production:

•	Find other features that could help predicting track popularity such as lexical field of each song, fan engagement (festivals, social media…), affiliation to a label/major

•	Diversify sources of information (not only Spotify)

•	Integrate a sub-model to best predict non established artists. As of now, the algorithm will easily predict song popularity for artists having many spotify users’ followers

•	Make the model universal and not solely applicable to the French market
