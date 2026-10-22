# Fake News Detection Using LSTM

## 1. Project Overview
This project uses Natural Language Processing (NLP) and a Long Short-Term Memory (LSTM) neural network to classify news articles as Fake or Real based on their textual content.

## 2. Problem Statement
A digital news platform wants to identify potentially fake news articles using their textual content. A labelled dataset of approximately 2,000 news articles is used to train and evaluate a deep learning model.

## 3. Objectives
- Load and preprocess the news dataset.
- Handle missing values and duplicate articles.
- Tokenize text and convert it into padded numerical sequences.
- Build and train an LSTM classification model.
- Evaluate the model using accuracy, precision, recall, and F1-score.
- Display a confusion matrix.
- Predict the category of unseen news articles.

## 4. Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- TensorFlow and Keras
- Scikit-learn
- Matplotlib and Seaborn

## 5. Dataset
The project uses the Fake and Real News Dataset from Kaggle.

Dataset: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

The dataset contains fake and real news articles. Approximately 2,000 articles are selected for this experiment.

## 6. Model Architecture
The LSTM model contains:
1. Embedding layer
2. LSTM layer with 64 units
3. Dropout layer
4. Dense layer with ReLU activation
5. Output layer with sigmoid activation

## 7. Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

Actual evaluation results should be recorded after running the notebook.

## 8. How to Run
1. Download the notebook from this repository.
2. Open https://colab.research.google.com/.
3. Upload the notebook to Google Colab.
4. Download the dataset from Kaggle and upload `Fake.csv` and `True.csv`.
5. Run the notebook cells in order.

## 9. Prediction
The trained model accepts an unseen news article and predicts whether its text resembles the Fake or Real articles in the training dataset.

**Note:** Predictions are model classifications, not independent verification of factual accuracy.

## 10. Author
GitHub: https://github.com/sheimohid1-ops
