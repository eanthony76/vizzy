===============
Documentation
================


The vizzy_sentence module in this package take in two inputs: data as a Pandas DataFrame, and a column name as a str.

Example::
``Data = pd.read_csv(~/data/data.csv)``
``column = 'Text'``

----------------------
``show_char_count()``
----------------------
This method returns a histogram showing your data column in length of characters

---------------------
``show_word_count()``
---------------------
This method returns a histogram showing your data column in length of words

----------------------
``show_word_length()``
----------------------
This method shows the length of individual words in your data column

----------------------------
``show_common_stopwords()``
----------------------------
This method shows the common stopwords in your data column
