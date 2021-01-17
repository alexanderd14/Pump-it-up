# Pump-it-Up


The goal here is to try helping the Tanzanian Ministry of Water to predict the operating condition of a waterpoint accross the country. We want to predict which pumps are going to continue working, which ones are going to need repairs and which ones are going to fail. We are thus dealing here with a multiclass classification problem for which we develop and Ensemble model.

The link to the competition is the following: https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/.

This work was done with the help of my colleagues Begoña Frigolet and Mohamed Khanafer. The model we developped ended up in the top 15% out of around 10000 people listed on the Leaderboard with a score of 0.8129.

The script associated with this model is found in the file 1_Pump_it_up_competition. It contains the following: a detailed Exploratory Data Analysis, Feature Engineering and Modeling, Feature Creation, a lightGBM, an ensemble VotingClassifier and a trial with H2O's Random Forrest.
