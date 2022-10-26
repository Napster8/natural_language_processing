# Natural Language Processing

This repository illustrates several comparitive studies on some of the key areas of Natural Language Processing using pyton ofcourse. 

Applications such as sentiment analysis, topic modelling, machine translation, is illustrated for now. Plans to expand on other applications.

Index of Contents:

1. Regular Expressions - This is to ensure the data quality is decent. Illustrates several examples on some of the most common usage of regular expressions.

2. Sentiment classifier on yelp - Illustrates some of the basic pipeline blocks of Natural Language Processing projects.
    - Building Vocabulary of words for sentiment analysis by building custom functions that use frequency of word occurence as criteria to filter out the words.
    - Word to Vector - A naive but basic method (One Hot Encoding) was used.
    - Creating feature matrix.
    - Splitting the data into training and test data and training several basic machine learning algorithms simulataneously.
    - Comparing the metrics.
3. Text Pre-Processing
    - Tokenizing words using:
      - SpaCy
      - Lemmatization
      - Stemming (Porter and Snowball Stemmer)
      - Byte Pair Encoding
      - BertTokenizer
      - XLNetTokenizer
    - Normalizing word formats.
      - Spelling Correction using Minimum Edit Distance(MED) and english_words_set.
4. Topic Modelling
    - TFIDF - statistically measuring importance of each word in classifying a certain document in a given corpus of documents.
    - Topic Modelling using sci-kit learn's TFIDF and gensim's implementation.
    
