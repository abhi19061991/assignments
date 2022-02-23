
SPEECH TO TEXT
-----------------------
-import a random speech dataset of a personality..
-library imported (Speech recognition and pyaudio)
-using exception handling method to load and convert the speech to
text.



Twitter sentiment analysis
----------------------------
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

For training the models, we provide a labelled dataset of 31,962 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet
preprocessing
---------------
-convert the tags(twitter sentiment) type as string.
-using regrex experession remove aal the unwanted pattern(@,!)
-create a column(clean tweet) which consists of clean data
-splitting the string with minimum words=3.
-stemmimg and lemmatization.
-join all word in a single sentence in a list.
EDA
------------
-visualize the frequent sentences by using WordCloud library.
-extract -ve and +ve tweets by defing the label as 1 and 0.
-displat +ve and -ve tweets in frequency distribution with help of nltk.
-vectorize and extract feature throgh bag of words technique.
and convert in to list of array.
-split the model into train,test,split.
model training
---------------------
using logistigic regression model to train the model.
finding f1 and accuracy score,getting 95%accuracy.
 


LDA(TOPIC MODELLING)
--------------------------------
-load a json extension file dataset using load file() command
preproceesing steps
---------------------
-apply stopwords..and lemmitization in the given corpus.
this is elimainate all the infected words and reduce to roots words.
-create a spacy object
nlp=spacy.load("en_core_web_em") used for large dataset.
this libraray is very usefull for  handling the POS tags words,
entity recognition ,finding quotes in sentences,puntuation etc..
-usage of gensim library (corpora.dictionary) to find the list of 
unique words in the corpus
training 
-----------
-training done using technique using tf-idf,which calculate the frequency
of the vocabulary in a sentence.
optimization
---------------
optimization of model done throgh N-grams ,in ihis case usage of 
bigram and trigram which uses words in a cluster format in corpus..
visualization
---------------
library using pyLDAvis to visualize the clustering on a 2d graph.




NAMED ENTITY RECOGNITION
-----------------------------------------
-import a random datset with sentence consisting of noun,pronoun
ex.organisation,place..
-import spacy library.which will automatically clean the infected text.
# Load SpaCy model
nlp = spacy.load("en_core_web_sm"
VISUALIZATION
---------------------
Create dataset using dictionary and displaying the respective entity. 

 



