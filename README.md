# nlp_datasets
Various datasets for NLP researches, kaggle competitions and other practical usage 

# Cryptocurrency texts dataset
Contains real tweets about Bitcoin and other cryptocurrencies. 

File name: crypto_tweets.csv

Size: 
843 kb

Shape:
(3940, 13)

Columns:
'user_location', 
'date', 
'text'


Based on this dataset: https://www.kaggle.com/kaushiksuresh147/bitcoin-tweets

3 columns were taken and randomly sampled. Rows with missed data were dropped 


# Students messages dataset
Contains real messages largely originate from Singaporeans and mostly from students attending the University (National University of Singapore).
These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available.

File name: students_messages.csv

Size: 
236 kb

Shape:
(3256, 1)

Columns:
'student_message'


Based on this dataset: https://www.kaggle.com/uciml/sms-spam-collection-dataset

1 column was taken and randomly sampled. Rows with spam lable were eliminated (Real messages only)
