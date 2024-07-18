# Research-Paper-Recommendation-System

This project uses natural language processing (NLP) and machine learning techniques to recommend research papers and predict their subject areas. The project consists of two main components:

1. Research Paper Recommendation: This component uses sentence transformers to encode paper titles and calculate cosine similarity scores to recommend papers.
2. Subject Area Prediction: This component uses a shallow multi-layer perceptron (MLP) model to predict the subject area of a paper based on its abstract.

## Data

The project uses the following datasets:

- Arxiv Data: A dataset of research papers from the Arxiv repository.
![Screenshot 2024-07-18 122440](https://github.com/user-attachments/assets/6f74cd93-c4a0-4b83-afd4-9a39b785ee7e)


## Models

The project uses the following models:

- Sentence Transformers: A pre-trained model for encoding sentence embeddings.
- Shallow MLP Model: A trained model for predicting subject areas.

## Usage

To use the project, simply run the streamlit app and enter a paper title or abstract. The app will recommend papers and predict the subject area of the input paper.

## Requirements

- Python: The project is built using Python 3.8.
- Libraries: The project uses the following libraries:
    - Sentence Transformers
    - TensorFlow
    - Keras
    - Streamlit
    - Pickle
    - NumPy

## Installation

To install the required libraries, run the following commands:

pip install sentence-transformers
pip install tensorflow
pip install keras
pip install streamlit
pip install pickle
pip install numpy

## Running the App

To run the app, navigate to the project directory and run the following command:

streamlit run app.py
