# Harmonizing Preferences: Machine Learning for Spotify Song Predictions

This is a repository where I use data science to predict my music tastes using Spotify's rich datasets. This project is a journey through the realms of data scraping, exploratory analysis, and machine learning, all aimed at understanding the intricacies of personal music preferences and developing a model that can accurately forecast whether I'll like a new song.

Project Overview:

1. **Data Scraping and Processing**: Leveraging Spotify's API, I've gathered a comprehensive dataset encompassing over 1,000 songs I enjoy and more than 900 songs I dislike. The data was organized, cleaned, and prepared for analysis. To facilitate the use of genres as features in machine learning models, I employed one-hot encoding, categorizing the genres into 25 broad groups.

2. **Exploratory Data Analysis**: This phase involved a deep dive into the data to uncover trends, song feature characteristics, and their correlations. By examining the essence of what makes a song appealing or unappealing to me, I gained insights that guided the subsequent predictive modeling.

3. **Predictive Modeling**: Here, I tested various machine learning algorithms, including Linear Regression, Random Forest Classifier, AdaBoost, Gradient Boosting, and Support Vector Machine (SVM), to identify the one that excels at predicting my song preferences. The evaluation of these models was based on their F1 scores and accuracy, emphasizing the importance of balancing precision and recall alongside making accurate predictions.

The star of the show was the Gradient Boosting model, which achieved an impressive F1 score of 86.73% by leveraging audio features as variables. This outcome underscores the power of machine learning in personalizing music recommendations, where both false positives and false negatives bear minimal cost but significant potential for enhancing user experience.

Why This Project Matters:

"Harmonizing Preferences" is more than just a personal quest to predict song preferences; it's an exploration of how machine learning can be applied to personalize and enhance our daily experiences. Through this project, I've not only honed my skills in data science—from scraping to predictive modeling—but also created a framework that others can adapt to understand and predict their own preferences across various domains.

Dive into the code, explore the findings, and see how data science can tune into our personal tastes, one song at a time.
