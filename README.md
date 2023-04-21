# NLP---Neural-Language-Model
This is an assignment on implementing an ngram language model for French from the course Machine Learning for NLP at the University Paris Cite'.

We will implement a language model

- at a given position i
- it takes as input the two preceding words
- and outputs log_probabilities for each word of the vocabulary

The network will use the concatenation of embeddings of the two preceding words, followed by a MLP with a single hidden layer.
