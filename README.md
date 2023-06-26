# NFL_Gambling_Model

This project will be using multiple machine learning methods to predict money line bet winners in NFL games.  The dataset was taken from https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data which is a collection of game, weather, and gambling data from pro-football-reference, espn, nfl weather, and a few other databases.

After the data has been cleaned, custom features which help predict the home team's win chances will be created from the cleaned data.  The best four features will be selected using the RFE base model.  Once the features have been selected for training the model, the data will be ran through multiple popular machine learning methods to determine which ones perform the best by average accuracy.
    
Money line predictions will be using classification models to predict straight-up winner.  Once the model has been trained, games will be tested and won bets will produce a return based on the spread of the game and the average money line for that spread.  The average moneyline for each spread is given in favMoneyLineDict and undMoneyLineDict.  All of the bets in this model are theoretical.
