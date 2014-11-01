SRK-Searcher
============

This an application of text processing techniques using NLTK library. The user types in what he wants to find out about Indian actor Shahrukh Khan, and gets the most appropriate result. 

Firstly we delete all punctuations and few other special symbols.
Then the text is tokenized and vectorized.
Then the post which doesnt contain the key word is deleted
Then we apply TF-IDF 
The post having minimum TF-IDF value is displayed as the result
