# NLP-related-to-complaints
**Sentiment Analysis with NLP related to complaints**

I worked at sikayetvar.com to get the titles, complaints and links of the complaints about TEB. I tried to create a dictionary, import that dictionary into a dataframe with the help of pandas and save it to CSV file by date.

**Installing / Getting started**

import requests

import urllib.parse

import random

from bs4 import BeautifulSoup

import re

import pandas as pd

from datetime import date


**You can find the code and csv file of my project on data extraction here.**

TEB_Sunum_veriçekme.ipynb
aaTEB_sikayetvar-2020-08-19.csv

**NLP & Sentiment Analyze Part**

I worked on downloading the libraries required for visualization, reading positive and negative texts, converting complaints to lowercase. 

**Source Codes of positive and negative words**

negative_words_tr.txt

positive_words_tr.txt

# SENTİMENT ANALYSİS

**Installing **

import plotly.express as px #visualization

import pandas as pd

from nltk import word_tokenize

from nltk.corpus import stopwords

import numpy as np

import re

import nltk

import string

from snowballstemmer import TurkishStemmer

pd.set_option('display.max_colwidth', -1)


I worked with these processes to break down sentences and make them countable. He then worked on removing punctuation, removing stop words, and refreshing the dataset. In order to see the transformation of the word with the suffixes on the root, the commonly used unnecessary words and punctuation marks should be taught to the computer. Rooting yield after cleaning was important for training and testing. Then I did sentiment analysis from my dataset, which I separated from its roots. I made a score for positive and negative words, assigning values ​​1 to positive words and 0 to negative words. After that, I did vectorizer, modeling testing and training. I realized that since it is an unbalanced data set, I will apply the undersampling method with the help of the count vectorizer. I use testing and logistic regression to analyze a dataset with one or more independent variables that determine an outcome.

**code**

Teb_Sunum_Modelleme.ipynb

# Related projects

https://github.com/pyjamapants/Python-NLP-Chat-Bot.git

