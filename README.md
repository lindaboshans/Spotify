# Harmonizing Preferences: Machine Learning for Spotify Song Predictions

This repository contains a project I did to learn how to:
1) scrape spotify API for my own data
2) perform exploratory data analysis on the types of songs I like and dislike 
3) test several machine learning algorithms to determine which can most accurately predict my song preferences.

The measure I used for determining the best model is the F1 score and accuracy, since it is important to have a good balance between precision and recall in song recommendations as well as accurate predictions. Having false positives or false negatives are not costly to the problem at hand (whether I like or dislike a song). 

The [code](https://github.com/lindaboshans/Spotify-Recommendation-System/blob/070da1a6bc3a5bf2424c0e7d82ca443eda61f427/Spotify.ipynb) is broken down into three main parts:
1) Data scraping and processing: Using spotify's API to download all my liked songs (over 1,000 songs) and a playlist of my dislikes (over 900 songs). I organized and cleaned the data for analysis, and also one-hot encoded the genres into 25 broad categories to make it easier to use as features.
2) Exploratory analysis: looking at trends, characteristics, and correlation of song features.
3) Predictive Modeling: The second part explores different machine learning algorithms, including linear regression, random forest classfier, AdaBoost and GradientBoosting, and SVM.

The winning model was the GradientBoosting model with an F1 score of 86.73% using audio features for variables. 

