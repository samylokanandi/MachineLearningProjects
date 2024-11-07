
---

# Homework 2 - Text Classification and NLP Preprocessing

This project focuses on disaster tweet classification using natural language processing (NLP) and machine learning techniques, primarily **Logistic Regression** and **Naive Bayes** models with various preprocessing steps.

---

## Steps:

### Data Loading and Splitting
- Loads training and test datasets from CSV files and splits the training data into training and development sets.

### Data Preprocessing
1. **Text Cleaning**:
   - Converts text to lowercase, removes punctuation, mentions, URLs, and hashtags.
   
2. **Lemmatization**:
   - Tokenizes text and applies part-of-speech (POS) tagging to ensure proper lemmatization.

3. **Stopword Removal**:
   - Removes common stopwords to reduce noise in the data.

### Feature Engineering
- **Bag of Words (BoW)**: Generates binary BoW feature vectors for the cleaned text with a minimum document frequency threshold.
- **N-grams**: Creates 2-gram features to capture word pairs in the dataset for improved context representation.

### Model Training and Evaluation
1. **Logistic Regression**:
   - Trains logistic regression models with no regularization, L1 regularization, and L2 regularization, comparing F1 scores to assess overfitting.

2. **Naive Bayes**:
   - Implements Naive Bayes from scratch, calculating class priors and conditional probabilities, and evaluates F1 scores on training and development sets.

### Submission Preparation
- Prepares test data predictions for submission to Kaggle, using a logistic regression model trained on combined cleaned data.

---

This notebook provides a complete workflow for text classification, including preprocessing, feature extraction, and model evaluation using both logistic regression and Naive Bayes.
