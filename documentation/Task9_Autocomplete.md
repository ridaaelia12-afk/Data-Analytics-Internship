# Task 9 — English Autocomplete and Autocorrect

## Overview

This task focuses on Natural Language Processing techniques for
building a basic English text autocomplete and autocorrection
system.

The English portion of the English-Hindi corpus is used for
language modeling.

## Dataset

**Dataset:** English-Hindi Truncated Corpus

**File:** `Hindi_English_Truncated_Corpus.csv`

### Dataset Size

- Rows: 127,607
- Columns: 3

### Columns

- `source`
- `english_sentence`
- `hindi_sentence`

## Objectives

The objectives were:

1. Load and inspect the text corpus.
2. Clean English sentences.
3. Tokenize text.
4. Analyze word frequencies.
5. Build n-gram language models.
6. Generate autocomplete suggestions.
7. Implement basic autocorrection.

## Text Preprocessing

The English sentences were processed by:

- Converting text to lowercase.
- Removing unnecessary characters.
- Tokenizing sentences.
- Cleaning whitespace.
- Preparing words for frequency and n-gram analysis.

## Word Frequency Analysis

Word frequencies were calculated to identify commonly occurring
English words in the corpus.

This provides the foundation for generating likely next words.

## N-Gram Models

N-grams were used to model relationships between words.

### Bigram Model

A bigram consists of two consecutive words.

For example:

`machine learning`

### Trigram Model

A trigram consists of three consecutive words.

For example:

`machine learning model`

These relationships are used to predict possible next words.

## Autocomplete

The autocomplete component uses previously observed word
sequences to generate possible next-word suggestions.

For a given input phrase, the model searches for likely continuations
based on the learned n-gram frequencies.

## Autocorrection

Basic autocorrection can be implemented using edit distance.

The system compares an unknown or misspelled word with words from
the vocabulary and selects likely corrections based on similarity
and word frequency.

## Evaluation

The generated autocomplete and autocorrection results can be
examined using sample inputs.

The implementation focuses on demonstrating the underlying NLP
techniques rather than building a production-level language model.

## Tools

- Python
- Pandas
- NumPy
- Regular Expressions
- Collections
- NLP techniques

## Conclusion

This task demonstrates fundamental Natural Language Processing
concepts for language modeling, autocomplete, and autocorrection.
N-gram models and edit-distance techniques provide a simple
foundation for intelligent text input systems.
