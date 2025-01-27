# Movie Genre Prediction

This project predicts movie genres based on titles using machine learning. It handles multi-label classification for movies with multiple genres.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Workflow](#workflow)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

## Overview
The goal is to classify movies into one or more genres using text data, transforming it into features and training a machine learning model.

## Dataset
- Format: `title:::genre1|genre2|...`
- Example: `Avatar:::Action|Adventure|Fantasy`
- Movies can belong to multiple genres.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd movie-genre-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Workflow
1. **Load Data:** Import dataset and parse titles and genres.
2. **Preprocess Data:** Clean text and encode genres.
3. **Feature Engineering:** Vectorize titles with TF-IDF.
4. **Train Model:** Use Logistic Regression with One-vs-Rest.
5. **Evaluate:** Assess performance with metrics like accuracy and F1-score.

## Usage
1. Place the dataset in the project directory.
2. Run the notebook:
   ```bash
   jupyter notebook movie_genre_prediction.ipynb
   ```
3. Follow the steps to train and evaluate the model.

## Results
The model predicts genres with reasonable accuracy. Detailed metrics are in the classification report.

## Future Work
- Improve preprocessing (e.g., stop word removal, stemming).
- Try advanced models (e.g., SVM, neural networks, BERT).
- Add features like movie descriptions or scripts.


For questions or feedback, open an issue in the repository.

