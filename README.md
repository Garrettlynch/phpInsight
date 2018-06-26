phpInsight - Sentiment Analysis in PHP
---------

phpInsight is a sentiment classifier. It uses a dictionary of words that are 
categorised as positive, negative or neutral, and a naive bayes algorithm to
calculate sentiment. To improve accuracy, phpInsight removes 'noise' words. 

For example usage, see the `examples` folder.

License: GPLv3 or later



--- Update 26-06-2018 ---

Score and categorise functions have been modified.  Score now decides an overall dominant sentiment (in case of a tie in scores), which is added to the $scores array as key "dom".  Categorise retrieves this winning sentiment ("dom") rather than the first key of the $scores array as assumed winning sentiment.
