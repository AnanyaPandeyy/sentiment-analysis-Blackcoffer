This repository contains the project I did for BlackCoffer, where I scraped over 100 of their articles to score them based on sentiment, polarity, subjectivity, word complexity, etc.
I've used the given stop words and positive and negative words files and have not imported them from any library.

stopwords_combined.ipynb: 

This notebook contains all the methods used to clean the input data (obtained through scraping, exceptions raised for a few articles handled by converting the UTF-8 code)  

text_analyse.ipynb: 

Contains a custom class object containing all methods of processing input tokens and quantifying their results for each method.



Clean Input is generated after ridding the initial input file of stop words, punctuations, etc.
