# Behavioural Fraud Detection System

A machine learning system that detects fraudulent banking transactions by
comparing each transaction against a customer's own historical spending
behaviour (amount, time, location) rather than generic rules.

## Setup
1. Install dependencies: `pip install -r requirements.txt`
2. Download the Sparkov dataset from Kaggle (kartik2112/fraud-detection)
   and place `fraudTrain.csv` and `fraudTest.csv` in this folder.
3. Open `fraud_detection.ipynb` and run all cells from top to bottom.

## Project structure
- `fraud_detection.ipynb` — full pipeline: preprocessing, model training,
  evaluation, and the scoring function used for testing individual
  transactions.