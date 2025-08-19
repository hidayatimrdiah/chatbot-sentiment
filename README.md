# Sentiment Analysis Chatbot 

A simple sentiment chatbot built with **Logistic Regression** and **Gradio UI**.  
It classifies user input as **positive** or **negative sentiment** and responds conversationally.

## Features
- Preprocessing of text (removes mentions, URLs, punctuation).
- Represented the preprocessed text using the Word2Vec technique. (Compared to Bag of Words technique)
- Sentiment classification using Logistic Regression. (Compared to two other sentiment techniques : VADER and NaiveBayes)
- A plotted bar graph to visualize which method has the highest accuracy for the chatbot.
- Interactive chatbot UI powered by Gradio.
- Confidence score displayed for predictions.
  
## Dataset
This project uses the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140).  

1. Download the dataset from the link above.  
2. Extract the ZIP file.  
3. Place the extracted file in the same folder as the project.

## Prerequisites

- Python 3.x installed
- Jupyter Notebook installed

## Demo
Clone the repository and install dependencies:

```bash
git clone https://github.com/hidayatimrdiah/chatbot-sentiment.git
cd sentiment-chatbot
pip install -r requirements.txt
launch jupyter notebook
run the notebook cells to see features
