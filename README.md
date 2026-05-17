# Natural Language Processing (NLP) Lab Repository

This repository contains a collection of Python scripts and Jupyter Notebooks demonstrating various fundamental and advanced concepts in Natural Language Processing (NLP). 

## Table of Contents

* **Lab 1: Text Preprocessing**: Demonstrates basic text cleaning techniques including tokenization, filtering of non-alphabetic characters, English script validation, stop word removal, and stemming using the NLTK library.
* **Lab 2: N-Gram Language Models**: Implements unigram, bigram, and trigram language models from scratch to calculate individual word probabilities and overall sentence probabilities.
* **Lab 3: Minimum Edit Distance**: Features a dynamic programming implementation to calculate the minimum edit distance between two strings (e.g., "saturday" and "sunday").
* **Lab 4: Syntactic Parsing**: Contains implementations of both Top-Down and Bottom-Up parsing algorithms for evaluating sentences against a simple context-free grammar.
* **Lab 5: Text Classification**: Demonstrates a Naive Bayes classifier built from scratch to categorize text documents into "comedy" and "action" genres based on word likelihoods and priors.
* **Lab 6: Corpus Exploration**: Provides an overview of various NLTK corpora, including Brown, Inaugural, Reuters, and UDHR, by extracting their categories, raw text, words, and sentences.
* **Lab 7: Lexical Semantics**: Uses NLTK's WordNet to extract sets of synonyms and antonyms for a given target word.
* **Lab 8: Machine Translation**: Uses Hugging Face's `transformers` library and a pre-trained sequence-to-sequence model (`rajaykumar12959/nllb-en-kn-v1`) to perform English to Kannada translation.

## Dependencies

To run the notebooks in this repository, you will need the following Python libraries installed:
* `nltk`
* `transformers`
* `torch`

Additionally, several NLTK datasets must be downloaded to your environment before running specific labs:
* `punkt`, `stopwords`, and `wordnet`
* `brown`, `inaugural`, `reuters`, and `udhr`
