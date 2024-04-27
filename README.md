## Twitter Sentiment Analysis using BERT

## Overview
This project aims to perform sentiment analysis on Twitter data using pre-trained BERT (Bidirectional Encoder Representations from Transformers) models. 
The goal is to classify tweets into positive, negative, or neutral sentiment categories.

## Installation
```bash
%pip install transformers
%pip install pandas
%pip install seaborn
%pip install tensorflow
%pip install matplotlib
%pip install nltk
```
##  Clone the GitHub repository:
```bash
git clone https://github.com/Rawlingsofficial/sentimental_analysis
```
## Download the pre-trained BERT model from Hugging Face:

```
# Load tokenizer and model
tokenizer = AutoTokenizer.from_pretrained("DunnBC22/bert-base-uncased-Twitter_Sentiment_Analysis_v2")
model = AutoModelForSequenceClassification.from_pretrained("DunnBC22/bert-base-uncased-Twitter_Sentiment_Analysis_v2")

```
## Usage
- Run the Jupyter Notebook Twitter_Sentiment_Analysis.ipynb.
- Follow the instructions within the notebook to perform sentiment analysis on Twitter data.
- Explore the results and visualize the sentiment distribution using provided code snippets.
- Adjust parameters or experiment with different models for further analysis.

# Dataset
The dataset used in this project consists of Twitter data with labeled sentiment.
It contains approximately 1.6 million tweets with sentiment labels (positive, negative, neutral).

# Acknowledgments
[Hugging Face](https://huggingface.co/)
[Twitter API](https://developer.twitter.com/en/docs/twitter-api)

## Author 
- [Mbah Rawling Mukhen](https://github.com/Rawlingsofficial/Rawlingsofficial)



