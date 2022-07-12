# Sentiment Analysis for Arabic Tweets Related to Riyadh Season using LSTM Network

This is a school project on Articial neural network course,My team did a Sentiment analysis on Arabic tweets about Riyadh season to classify the tweets as positive, negative or neutral tweets using Long Short Term Memory networks (LSTM) 

##Dataset 
To use data from Twitter, first, we registered an application in order to gain the access to the APIs which allows us to retrieve, engage with, or create a variety of different resources including the following: tweets, users, spaces.
After getting the data, we filters the tweets  about Riyadh season using specific keywords. then we stored the unlabeled data in a csv file.

We labeled the data manually into three categories: 
Positive tweet: 1
Natural tweet: 0
Negative tweet: -1 


###Cleaning and preprocessing
The cleaning_text method basically involves removing punctuation, Arabic diacritics (short vowels and other harakat), elongation, emoji, and URL.

###Tokenization
We did the Tokenization to break the raw text into words, The tokenization helps in interpreting the meaning of the text by analyzing the sequence of the words.

###LSTM model
Then, we built the LSTM network, we used RELU as an activation function

