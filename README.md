# Text Analysis
The main data structure used for text analysis is the $\textbf{Bag of word}$.\\
To create a bag of words a vocabulary is needed. The vocabulary contains the set of all possible words that our model should recognize. The words are sorted according to a certain ordering.\\
A bag of words is the analytical representation of a corpus (or document). Typically the bag of words has the same length of the vocabulary.\\

If the first 3 words of the vocabulary are:

- back
- green
- tree
  
The sentence "the tree is green" has a bag of words like this: [0 1 1].\\

If the vocabulary is:

- back
- grass
- green
- tree

and the sentence is "the tree is green, but also the grass is green", the Bag Of Words is: [0 1 2 1]\\

With this representation, two or more corupuses are comparable $\rightarrow$ a machine learning model can be trained.\\

For text analysis both logistic regression and Naive Bayes classifier can be used.\\
Logistic regression is expensive in training, but can lead to a small improve respect to Naive Bayes.\\

# Stopwords
All the words that occur a lot in a sentence are called stopwords.\\
An exaple of the most frequent stopwords is: ["a", "an", "and", "or", "he", "she", "it",...]
