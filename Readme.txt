Twitter Sentiment Analysis Project

Overview:

This project involves the analysis of tweets to determine the sentiment expressed in each tweet. The project includes data collection, preprocessing, exploratory data analysis, feature extraction, sentiment labeling, and model training and testing. The main goal is to classify tweets into positive, negative, or neutral categories.

Work Flow:

Data Collection
The dataset Tweets.csv contains tweets that are loaded into a pandas DataFrame for analysis.

Preprocessing
Tweets are cleaned and preprocessed by removing URLs, special characters, and converting them to lowercase. NLTK's tokenization, stop word removal, and lemmatization are applied.

Exploratory Data Analysis
Top words in tweets are identified.
Word clouds are generated to visualize the data.
Feature Extraction
TF-IDF vectorization is used to convert textual data into a numeric form suitable for machine learning models.

Sentiment Labeling
NLTK's SentimentIntensityAnalyzer is used to calculate polarity scores for each tweet, and labels are assigned based on these scores.

Model Training and Testing
The dataset is split into training and test sets.
A Multinomial Naive Bayes classifier is trained.
Model performance is evaluated using classification reports and accuracy scores.
A confusion matrix is plotted to visualize the performance.
Additional Analysis
An additional function keyword_sentiment_analysis is provided to perform sentiment analysis on tweets containing a specific keyword.

Usage
Load the dataset and follow the steps in the script to preprocess data, train the model, and evaluate its performance. To analyze sentiment for a specific keyword, use the keyword_sentiment_analysis function.

python code: To Test the Model 
Change the keyword required in the place of "Football" and execute the code

keyword_sentiment_analysis('football', data, classifier, tfidf_vectorizer)

License

This project is licensed under the MIT License - see the LICENSE.md file for details