---
title: Bag-of-Words
---
The phrase *bag-of-words* typically refers to a way of representing
text in natural language processing, although [it has been applied to computer vision][1].

A bag-of-words representation contains how many times each word appears in a document,
but disregards the order of the words.

Often, bag-of-words models will only include the $k$ most frequent words in a corpus.
This reduces the memory needed to store relatively-infrequent words, and the
underlying representation of the document is mostly the same.

See also:

 - [Bag-of-words model][2]
 - [Bag of Words Meets Bags of Popcorn - Kaggle][3]
 
[1]: https://en.wikipedia.org/wiki/Bag-of-words_model_in_computer_vision
[2]: https://en.wikipedia.org/wiki/Bag-of-words_model
[3]: https://www.kaggle.com/c/word2vec-nlp-tutorial/details/part-1-for-beginners-bag-of-words