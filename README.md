Link to the Colab file: [here](https://colab.research.google.com/drive/1nejvhlpfRG2ShThkXJA3JUHiN3To61px?usp=sharing)

# Fake News Prediction

This project implements a fake news prediction system using logistic regression. The model classifies news articles as either real or fake based on their content.

## Getting Started

To get started, download the dataset from Kaggle. You can access it [here](https://www.kaggle.com/c/fake-news/data?select=train.csv).
Register/ take part in the competition and then download the dataset from there.

## Data Description

The dataset contains the following columns:

1. **id**: Unique identifier for each article.
2. **title**: Title of the news article.
3. **author**: Author of the news article.
4. **text**: Main content of the news article.
5. **label**: The label indicating whether the news is fake (1) or real (0).

## Model Overview

1. **Data Preprocessing**: Clean and prepare the data for training.
2. **Train-Test Split**: Split the data into training and testing sets.
3. **Logistic Regression**: Train a logistic regression model to classify the news articles.
4. **Prediction**: Use the trained model to predict whether a new article is real or fake.

For further details, please refer to the Kaggle notebook.
