# Sentiment Analysis with VADER and RoBERTa

## Overview

This repository contains a comprehensive sentiment analysis project that combines both traditional and deep learning approaches. The project focuses on analyzing a dataset of reviews to classify sentiment using the following methods:

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner):** A rule-based tool for sentiment scoring.
2. **RoBERTa (Robustly Optimized BERT Pretraining Approach):** A pre-trained deep learning model for sentiment classification.

## Key Features

- **Data Preprocessing:** 
  - Cleaned and tokenized text for model input.
  - Performed lemmatization to standardize the text.

- **VADER Sentiment Analysis:**
  - Applied the VADER model to score sentiments and classify reviews.

- **RoBERTa Sentiment Analysis:**
  - Leveraged the pre-trained RoBERTa model to perform sentiment classification.

- **Results Visualization:**
  - Compared sentiment scores and classifications from VADER and RoBERTa.
  - Visualized distributions and insights using graphs.

## Installation

### Prerequisites

Ensure you have Python 3.8 or later installed. Then, clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/sentiment-analysis-with-roberta-and-vader.git
cd sentiment-analysis-with-roberta-and-vader
pip install -r requirements.txt
