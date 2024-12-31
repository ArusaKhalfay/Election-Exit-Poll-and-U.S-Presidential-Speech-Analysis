# Election Exit Poll Prediction and U.S. Presidential Speech Analysis 

## Overview

This project applies machine learning and natural language processing (NLP) techniques to address two distinct problems:
1. **Voter Party Classification**: Predicting voter party affiliation based on survey data.
2. **Text Analysis**: Analyzing and visualizing themes in U.S. presidential inaugural speeches.

---

## Features

### 1. Voter Party Classification
- **Objective**: Develop a model to predict which political party a voter is likely to support based on their demographic and opinion data.
- **Steps**:
  - Data exploration and preprocessing:
    - Checked for missing and duplicate values.
    - Encoded categorical variables and scaled features.
  - Model development:
    - Built and compared Logistic Regression, LDA, KNN, and Naive Bayes classifiers.
    - Evaluated models using accuracy, confusion matrices, and ROC-AUC scores.
  - Insights:
    - Key predictors include leader perception and economic conditions.
    - Logistic Regression and LDA emerged as the best-performing models.

### 2. Text Analysis of Presidential Speeches
- **Objective**: Perform an NLP analysis of inaugural speeches to uncover linguistic patterns and key themes.
- **Steps**:
  - Basic text statistics:
    - Calculated counts of characters, words, and sentences.
  - Text preprocessing:
    - Removed stopwords, punctuation, and numerical characters.
    - Converted text to lowercase for uniformity.
  - Word frequency analysis:
    - Identified the most frequently occurring words for each president.
  - Visualization:
    - Created word clouds to visualize prominent topics in each speech.
  - Insights:
    - Themes reflected historical challenges and priorities:
      - Roosevelt: Freedom and war.
      - Kennedy: Civic responsibility and global cooperation.
      - Nixon: Peace and reconciliation.

---

## Technologies
- **Languages**: Python
- **Libraries**:
  - **Data Analysis**: pandas, numpy
  - **Machine Learning**: sklearn
  - **NLP**: nltk, wordcloud
  - **Visualization**: matplotlib, seaborn

---
