# NLP Ngram Language Model Lab (Unassessed) 📚

This lab focuses on building and evaluating ngram language models. You will work on four exercises, each targeting different types of ngram models. Before diving into the exercises, make sure you understand the provided examples.

## Exercises Overview 🏋️‍♂️

1. **Unigram Maximum Likelihood Estimation (MLE) Model**:
   - Build a model estimating the likelihood of single words occurring.
   - Evaluate the model's perplexity on the training sentences.
   
2. **Bigram MLE Model with Add-One Smoothing**:
   - Build a model estimating the likelihood of words given the previous word.
   - Implement add-one smoothing for testing.
   - Evaluate perplexity on the test data.

3. **Bigram Model with General Additive (Lidstone) Add-k Smoothing**:
   - Implement general additive smoothing with different values of k.
   - Find the optimal k value on the heldout data.
   - Evaluate perplexity on the test data with the optimal k.

4. **Ngram Models with Kneser-Ney Smoothing**:
   - Modify the training code to handle out-of-vocabulary words.
   - Experiment with different n-gram orders and discount values.
   - Find the optimal values for perplexity on the heldout data.
   - Evaluate perplexity on the test data with the optimal parameters.

## Getting Started 🚀

Before starting the exercises, ensure you have the following files:
- `switchboard_lm_training.txt` for training data.
- `switchboard_lm_heldout.txt` for heldout/development data.
- `switchboard_lm_test.txt` for test data.

## How to Use 📝

- Each exercise requires modifications to the provided code.
- Follow the instructions within each exercise carefully.
- Evaluate the perplexity of language models on both heldout and test data.

## Note 📌

- Ensure to replace out-of-vocabulary words with `<unk/>` before processing.
- Maintain consistency in vocabulary across exercises for fair comparisons.
- Experiment with different parameters to optimize model performance.
