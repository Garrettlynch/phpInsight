phpInsight - Sentiment Analysis in PHP
---------

phpInsight is a sentiment classifier. It uses a dictionary of words that are 
categorised as positive, negative or neutral, and a naive bayes algorithm to
calculate sentiment. To improve accuracy, phpInsight removes 'noise' words. 

For example usage, see the `examples` folder.

License: GPLv3 or later


--- update 26-06-2018 ---

Library no longer allows a tie between positive and negative (pos/neg) sentiments, instead neutral (neu) sentiment is assumed.
