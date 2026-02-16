# Duplicate Question Pairs Detection Project

## Problem Statement

The primary objective of this project is to develop a predictive model capable of identifying pairs of questions with similar meanings. This task is pivotal for platforms like Quora, where it can help in reducing redundancy and improving user experience by offering relevant answers to new questions based on previously answered ones.

## Source

The dataset utilized in this project is sourced from Kaggle. You can access the dataset via the following link: [Quora Question Pairs](https://www.kaggle.com/competitions/quora-question-pairs/data).

## Features

The dataset comprises the following features:

- **id**: Unique identifier for each question pair.
- **qid1, qid2**: Unique identifiers for each individual question (available only in the train.csv).
- **question1, question2**: The full text of the questions.
- **is_duplicate**: Binary variable indicating whether the pair of questions share similar meanings (1 for yes, 0 for no).

## Project Overview

### Installation Steps

To replicate this project, you need to follow these installation steps:

1. Install Python (if not already installed) from [python.org](https://www.python.org/).
2. Install Jupyter Notebook using pip:
3. Install required libraries using pip:

### Methodology

The project employs the following machine learning algorithms for prediction:

1. **Logistic Regression**
2. **Decision Tree**
3. **XGBoost**
4. **RandomForestClassifier**

The goal is to determine the most effective algorithm for detecting duplicate question pairs.

## Conclusion

In this project, we developed and evaluated several machine learning models to predict duplicate question pairs. The findings shed light on the performance of different algorithms and provide insights for future improvements and enhancements.Here using these machine learning algorithm we get accuracy of 80%.



