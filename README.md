# BT5153_Group_K.L.M.S
Rumor Detection in Popular Online Social Media Posts

To reduce the size of the submission folder, we have convert original JSON data into csv file with initial processing. 
 
There are 6 csv files for data and 4 jupyter notebook programs in this submission:

raw_train.csv: raw training data containing original tweet text and existing feature from tweet API

raw_test.csv: raw training data containing original tweet text and existing feature from tweet API

EDA_analysis.csv: preprocessed file for eda analyses 

train.csv: output file from preprocessing program 

test.csv: output file from preprocessing program

Lowercase_no_url_stopwords_special_words_lemmatized_data.csv: training data without url, stopwords and special words

preprocessing.ipyb: preprocessing program: 
      input: raw_traIn.csv, raw_test.csv, EDA_analysis.csv
      output: train.csv, test.csv

Machine Learning Models.ipyb: machine learning program:
      input: train.csv, test.csv
      output: imp.csv, covid_result.csv

Keras.ipyb: machine learning program: Neural network with embedding
      input: lowercase_no_url_stopwords_special_words_lemmatized_data.csv


Keras_Corss_Validation.ipyb: machine learning program:NN with embedding + k-fold
      input: lowercase_no_url_stopwords_special_words_lemmatized_data.csv
