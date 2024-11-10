# Disaster Tweet Classification

This repository contains code and resources for the Kaggle competition **Natural Language Processing with Disaster Tweets**. The goal is to classify tweets as disaster-related or not.

## Project Overview
This project uses a Dense Neural Network with TF-IDF text embeddings to classify tweets. The model is evaluated using the F1 score, optimized for precision and recall.

## Files
- `Disaster Tweet Classification with DistilBERT_n`: Main notebook with code for data preprocessing, EDA, model training, and evaluation.
- `submission_W4.csv`: Final submission file.
- `best_disaster_tweet_model.keras`: Saved model file of the best-performing model.
- `README.md`: Project overview and instructions.

## How to Run
1. Clone this repository.
2. Open `Disaster-Tweet-Classification.ipynb` and follow the steps to preprocess, train, and evaluate the model.
3. Download the dataset from the [Kaggle competition page](https://www.kaggle.com/c/nlp-getting-started) and place it in the notebook's directory.

## Results
The model achieved an F1 score of 0.79987 on the Kaggle public leaderboard. 

## License
[MIT License](LICENSE)
