================
Documentation
================

The main module in this package takes in two inputs: data as a Pandas DataFrame, and a column name as a str.

Example::
``Data = pd.read_csv(~/data/data.csv)``

``column = 'Text'``

----------------------
``show_char_count()``
----------------------

This method returns a histogram showing your data column in length of characters

----------------------
``show_word_count()``
----------------------

This method returns a histogram showing your data column in length of words

----------------------
``show_word_length()``
----------------------

This method shows the length of individual words in your data column

----------------------------
``show_common_stopwords()``
----------------------------

This method shows the common stopwords in your data column

--------------------------
``show_common_words()``
--------------------------

This method shows the common words in your data column that are not stopwords

---------------------
``show_sentiment()``
---------------------

This method shows the sentiment of the text in your data

-------------------------
``show_sentiment_cats()``
-------------------------

This method shows the sentiment of your data plotted on a bar chart

-------------------------
``show_neg_sentiment()``
-------------------------

This method shows the five most negative text values from your data

---------------------------
``show_pos_sentiment()``
---------------------------

This method shows the five most positive text values from your data

---------------------------
``show_flesch_kincaid()``
---------------------------

This method shows a plot of your text by Flesch-Kincaid score

---------------------------
``show_bi_grams()``
---------------------------

This method shows the most common bi-grams from your text data

-------------------------
``show_tri_grams()``
-------------------------

This method shows the most common tri-grams from your text data
