# Capstone-Project- Classification- Coronavirus Tweet Sentiment Analysis


**Introduction**

Provided with Coronavirus Tweet Sentiment Analysis dataset, main objective is to do some analysis and build a classification model to predict the sentiment of COVID-19 tweets.

**Problem Statement**

Coronavirus Tweet Sentiment Analysis
This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then. The names and usernames have been given codes to avoid any privacy concerns.

**Dataset Information**

The provided Dataset is of Coronavirus Tweet which consists detail of tweets done by user. There are total 41157 rows and 6 columns in the provided dataset. In this dataset there are details for tweets such as Tweet timing which states Date for a particular tweet. Username and Screenname of the user which is coded to avoid privacy concerns. Original tweet of user, location from where tweet is done and Sentiment behind that tweet. In short, there are UserName, ScreenName, OriginalTweet, TweetAt, Location and Sentiment variables. The main objective is to predict the sentiment of COVID-19 tweet. Following are the details of all columns present:

UserName- Date of record for stocks

ScreenName – Opening price of stocks

OriginalTweet – Highest price in the day for stocks

TweetAt – Lowest price in the day for stocks

Location – Closing price of stock

Sentiment – Sentiment of the Tweet

**Data Preprocessing**

Data preprocessing involves cleaning and transformation data into suitable form for analysis. Removing null values, duplicate values and making data ready to analyse further. This steps for data cleaning is must before starting with model implementation.

**Model Implementation**

For building classification model, text normalization is performed which include expanding contractions, Tokenization, Remove punctuations, Stemming, Lemmatization and POS tagging. Data transformation is done using Normalization technique. Data is standardize using StandardScaler. Split the data into training and testing sets, and train the model on the training set. Evaluate the model's performance on the testing set and tune the hyperparameters accordingly. For this project, we have used accuracy as the evaluation metric to choose which model is performing better.

**Conclusion**

For building classification model, we have used several algorithm such as Logistic Regression, Decision Tree Classifier, Random Forest Classfier, K-Nearest Neighbors and Naive Bayes Classifier using Count Vectorizer and TF-IDF Vectorizer.

Comparing with the accuracy of other models we can clearly state that Logistic Regression is performing better than any other with 0.78 accuracy.

