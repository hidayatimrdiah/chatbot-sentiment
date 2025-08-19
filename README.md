# Sentiment Analysis Chatbot 🤖

A simple sentiment chatbot built with **Logistic Regression** and **Gradio UI**.  
It classifies user input as **positive** or **negative sentiment** and responds conversationally.

## Features
- Preprocessing of text (removes mentions, URLs, punctuation).
- Sentiment classification using Logistic Regression. (Compared to two other sentiment techniques : VADER and NaiveBayes)
- Interactive chatbot UI powered by Gradio.
- Confidence score displayed for predictions.

## Demo
Run locally:

```bash
git clone https://github.com/hidayatimrdiah/chatbot-sentiment.git
cd sentiment-chatbot
pip install -r requirements.txt
python app.py
