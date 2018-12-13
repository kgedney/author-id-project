### author-id-project
Author Identification using Deep Learning Project

This project is a single-label multi-classification task for 100 authors, for which we trained a baseline support vector machine (SVM) and four deep learning models.

Since the dataset is cross-topic, we also tested the impact of removing named-entities.

**This repo contains:**
 - code to collect and prepare a dataset from the Reddit API using PRAW -> `reddit_collect_data.ipynb`
 - code to fit a baseline SVM, and four deep learning models: LSTM, CNN, CNN+LSTM, and a Simple Pooling Model -> `text_preprocessing_and_modeling.ipynb`
 - code to remove named-entities from dataset using Stanford's NER software `Cross_Topic_Processing.ipynb`
 - code to run experiment 2: fit the same models but compare results with the named-entities removed and intacted -> `exp2_text_preprocessing_and_modeling.ipynb` and `exp2_modeling.ipynb`
 - folder `data` contains csv files -> filtered_data.csv, filtered_data_sub.csv, raw_data-2.csv.zip, and author_tokens_df.csv 
 - folder `Word Clouds` with files with text and the python notebook -> words_68.txt and WordClouds.ipynb
 
 

 
 
 
