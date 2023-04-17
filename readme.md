# Summary of Assignments

This summary covers the four given assignments. It provides a template for a GitHub Readme file that contains the results and relevant information for each assignment.

## Assignment 1: Finding Similar Text Sections using Edit Distance

Objective: In this assignment, the goal is to use the edit distance to find similar text sections between documents by implementing the Smith-Waterman Algorithm.

### Steps:

    1-  Download at least 20 standard textbooks from the Ministry of Education and convert them to text documents. Each document should be at most 400 lines. Aim to have at least 100 Turkish text documents.
    2- Insert the same line of text into random positions of random text documents to create common text between them.
    3- Using the Smith-Waterman Algorithm, find the common lines between given two text documents.

## Assignment 2: Developing a Statistical Language Model of Turkish using N-grams

Objective: Develop a statistical language model of Turkish using N-grams of Turkish syllables.

Steps:

    1- Download the Turkish Wikipedia dump.
    2- Separate each word into its syllables using a program found online or implemented.
    3- Calculate the 1-Gram, 2-Gram, and 3-Gram tables for this set using 95% of the set (using a subset if necessary). Apply GT smoothing and use efficient storage methods.
    4- Calculate perplexity of the 1-Gram to 3-Gram models using the chain rule with the Markov assumption for each sentence. Use the remaining 5% of the set for these calculations. Present findings in a table.
    5- Produce random sentences for each N-Gram model, picking one of the best 5 syllables randomly. Include these random sentences in the report and discuss the produced sentences.

## Assignment 3: Assigning Vectors to N-grams and Measuring Turkish Morphological Derivations

Objective: Assign vectors for each N-gram of Turkish syllables and measure how well it captures the Turkish morphological derivations.

Steps:

    1- Download the Turkish Wikipedia dump.
    2- Separate each word into its syllables using a program found online or implemented.
    3- Calculate the 1-Gram, 2-Gram, and 3-Gram tables for this set using 95% of the set (using a subset if necessary).
    4- Assign vectors for each of the 1-gram, 2-gram, and 3-gram syllables using the word2vect algorithm.
    5- Find word similarity tests for Turkish morphology suffixes and analyze the results.
    6- Run morphology analogy tests between the words and list examples where the system works and fails.

## Assignment 4: Developing a Simple Translator from Ottoman Turkish to Modern Day Turkish

Objective: Use the Python language and the Keras library on Google Colabs to develop a simple translator from Ottoman Turkish to modern day Turkish.

Steps:

    1- Familiarize with Google Colaboratory and deep learning examples.
    2- Develop a simple translator using LSTM methods (no transformer-based models allowed), train it with the provided dataset, and measure the final BLEU score on the system results. Use a separate test set for performance evaluation.
    3- Perform experiments to:
    4-Measure the effects of pretraining of the model with other Turkish sets.
    5-Measure the effect of data size by running experiments with different amounts of training data.
    6-Change the attention and LSTM parameters of the model and report the results.