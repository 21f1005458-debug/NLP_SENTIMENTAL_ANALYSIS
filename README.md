# NLP_SENTIMENTAL_ANALYSIS
NLP Sentimental analysis using pyspark
# 🧠 NLP Sentiment Analysis Pipeline with PySpark

## 🚀 Overview
This project builds a scalable NLP sentiment analysis pipeline using PySpark. It processes large volumes of customer reviews, performs text cleaning and sentiment scoring, and outputs structured sentiment data for further analytics or model training.

## 📊 Features
- Batch processing of raw review data using PySpark
- Sentiment scoring via TextBlob using PySpark UDFs
- Output written to Parquet and SQLite
- Notebook for sentiment distribution analysis

## 🛠️ Tech Stack
- PySpark
- TextBlob
- Pandas
- SQLite
- Parquet

## 📁 Folder Structure
- `data/`: Raw and processed review files
- `scripts/`: PySpark pipeline and utility code
- `output/`: Final sentiment results
- `notebooks/`: Jupyter analysis notebooks

## ▶️ Run the Pipeline
```bash
spark-submit scripts/sentiment_pipeline.py
