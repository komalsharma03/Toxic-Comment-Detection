# Toxic-Comment-Detection
“Developed a machine learning-based NLP application to classify user comments as toxic or non-toxic, deployed using Streamlit with real-time predictions and text preprocessing.”
## Requirements
Dependencies are listed in requirements.txt:
> streamlit
> pandas
> numpy
> torch
> nltk
> scikit-learn
## Features
Pretrained toxicity detection model using PyTorch.
Streamlit app for interactive testing and visualization.
Text preprocessing with NLTK (tokenization, stopword removal, stemming/lemmatization).
Evaluation metrics (accuracy, precision, recall, F1-score) via scikit-learn.
Data handling with pandas/numpy for efficient processing.
##Project Structure
├── app.py              # Streamlit app entry point
├── model/              # Saved trained model files
├── data/               # Sample datasets (e.g., comments.csv)
├── preprocessing/      # Scripts for text cleaning and tokenization
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
##Model Details
Architecture: PyTorch-based neural network (can be CNN, LSTM, or Transformer depending on training script).

Training Data: Labeled comment dataset (toxic vs. non-toxic).
Preprocessing:
Lowercasing text
Removing punctuation & stopwords
Tokenization with NLTK
Converting tokens to numerical vectors (TF-IDF or embeddings)
Evaluation:
Accuracy, Precision, Recall, F1-score
Confusion matrix for error analysis
Run the Streamlit app locally:
streamlit run app.py
##Goal
The goal of this project is to provide a lightweight, interactive tool for detecting toxic language in comments. It can be extended for:
Social media moderation
Online community management
Research in NLP and ethics

##future Improvements
Multi-class classification (toxic, severe toxic, obscene, threat, insult, identity hate).
Integration with transformer models (BERT, RoBERTa).
Deployment as a REST API for production use.
Visualization dashboards for dataset insights.
