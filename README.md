# Product Review Sentiment Analysis

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20App-2ea44f?style=for-the-badge&logo=streamlit&logoColor=white)](https://appuct-review-sentiment-analysis-33cy7w2d6fpsns77fugqba.streamlit.app/)
[![Built With Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)


## Overview

Product Review Sentiment Analysis is a Streamlit web application that extracts customer reviews from PDF files and analyzes the sentiment of each review using TextBlob. The app turns raw review text into clear, interactive insights so you can quickly understand customer feedback trends.

## Key Features

- Upload a PDF file containing product reviews.
- Automatically extract and split reviews from the document.
- Classify each review as Positive, Negative, or Neutral.
- Display sentiment metrics and interactive charts.
- Review individual entries and download the full analysis as CSV.

## Live Deployment

Open the deployed app here:

[![Open Deployed App](https://img.shields.io/badge/Open%20Deployed%20App-Launch%20Now-00C853?style=for-the-badge&logo=streamlit&logoColor=white)](https://appuct-review-sentiment-analysis-33cy7w2d6fpsns77fugqba.streamlit.app/)

## Tech Stack

- Streamlit
- Python
- Pandas
- PyPDF2
- TextBlob
- Plotly

## How It Works

1. Upload a PDF with product reviews.
2. The app extracts text from each page.
3. Reviews are split into individual entries.
4. Sentiment polarity is calculated for every review.
5. Results are displayed with charts, metrics, and downloadable output.

## Local Setup

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Notes

The app is best suited for PDFs where customer reviews are separated by blank lines or similar spacing patterns.
