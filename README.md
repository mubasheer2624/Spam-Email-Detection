# Spam-Email-Detection

This project aims in building a spam detection model using NLP techniques in Python. The process starts with data collection and cleaning. We leverage some EDA techniques to understand the structure and characteristics of the data, as demonstrated by the analysis of message lengths, histograms, and word clouds. The core of our project involves extensive data preprocessing, including text normalization, stop words removal, and lemmatization. We converted labels into binary form and partition the data into training, validation, and test sets. Initially we used Naive Bayes model technique and got an accuracy of 88.9. To address class imbalance issues affecting performance, we applied the SMOTE technique which increased our accuracy to 96.4. We then used the LSTM technique to improve further more accuracy of our model and achieved an accuracy of 98.4.
More ways such as heavy feature engineering and treating data in a different way such as try snipping large messages or creating meaningful vectors using Doc2Vec or LLMs like BERT could have been done.
