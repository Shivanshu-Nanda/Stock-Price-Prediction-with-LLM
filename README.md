# Stock-Price-Prediction-with-LLM
## Stock Price Prediction with LLM (Using Gemini in Colab)

This project explores how large language models (LLMs) can perform complex tasks that previously required coding. Instead of manually writing code, we will interact with Google's Gemini 

- Load and analyze stock price data.
- Engineer relevant features for prediction.
- Build and evaluate models such as regression and random forest.
- Discuss potential trading strategies based on predictions.

## Project Breakdown

### Step 1: Data Exploration
- **Prompt the LLM**: Load historical stock price data for Apple Inc. (AAPL) from 2020-01-01 to 2025-01-01 using Yahoo Finance.
- **Key Considerations**: Ensure the model retains context while summarizing key statistics.

### Step 2: Feature Engineering
- **Prompt the LLM**: Generate meaningful features such as moving averages, technical indicators, and volatility measures.
- **Managing Context**: If the LLM forgets prior outputs, remind it by reintroducing key statistics.

### Step 3: Model Building
- **Prompt the LLM**: Train a model (regression for price prediction, random forest for trend classification).
- **Split Ratio Consideration**: Explain the importance of train-test split (e.g., 70/30) and verify the LLM respects it.

### Step 4: Model Evaluation & Prediction
- **Prompt the LLM**: Use the trained model to predict stock prices for 2023-2024.
- **Analyze Performance**: Interpret accuracy, R² scores, and classification reports.

### Step 5: Strategy Discussion
- **Prompt the LLM**: Based on model performance, discuss possible trading strategies.
- **Critical Thinking**: Evaluate whether the model is truly useful for financial decision-making.
