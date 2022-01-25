# NLP-Opinion_Mining
 Suggestion Mining from Online Reviews and Forums.
 
 Sentiment analysis (also known as opinion mining or emotion AI) is the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information. Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications that range from marketing to customer service to clinical medicine. With the rise of deep language models, such as RoBERTa, also more difficult data domains can be analyzed, e.g., news texts where authors typically express their opinion/sentiment less explicitly.
 
Here is what the Pre-processing does:
Remove all capital letters, punctuations, emojis, links, etc. Basically, removing all that is not words or numbers.
Tokenize the data into words, which means breaking up every comment into a group of individual words.
Remove all stopwords, which are words that don’t add value to a comment, like “the”, “a”, “and”, etc.


Lemmatization is one of the most common text pre-processing techniques used in Natural Language Processing (NLP) and machine learning in general.
 The root word is called a stem in the stemming process, and it is called a lemma in the lemmatization process.
 
 
Removing extra spaces
Most of the time the text data that you have may contain extra spaces in between the words, after or before a sentence. So to start with we will remove these extra spaces from each sentence by using regular expressions.


Removing punctuations
The punctuations present in the text do not add value to the data. The punctuation, when attached to any word, will create a problem in differentiating with other words.


Case Normalization
As python is a case sensitive language so it will treat NLP and nlp differently. One can easily convert the string to either lower or upper by using:
str.lower() or str.upper().


Tokenization: Splitting a sentence into words and creating a list, ie each sentence is a list of words. 


Removing Stopwords
Stopwords include: I, he, she, and, but, was were, being, have, etc, which do not add meaning to the data. So these words must be removed which helps to reduce the features from our data. These are removed after tokenizing the text.


Stemming: A technique that takes the word to its root form. It just removes suffixes from the words. The stemmed word might not be part of the dictionary, i.e it will not necessarily give meaning. There are two main types of stemmer- Porter Stemmer and Snow Ball Stemmer(advanced version of Porter Stemmer).


