# Tweet-Classification
Detect hate speech in tweets
# Description
In this project, I have implemented a text classification model (consisting of two Bidirectional LSTM Layers, two Dense Layers and the output layer) to classify hate tweets.The datset is highly imbalanced consisting of 29720 normal and 2242 hate tweets. I have used three pretrained word embeddings namely 1-GloVe (trained on Twitter data), 2-GloVe (trained on Wiki data) and 3-fastText (trained on Common Crawl data). The final model is an ensemble of the models trained using the above mentioned word embeddings where 50% weightage is given to 1 and 25% weightage is given to 2 and 3 each. The ensemble model gives the best performance compared to the individual models. 
This dataset is available for download at https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/.
