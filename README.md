# Data Analysis Agent

An AI agent that answers business questions about sales data in plain English.
It writes and runs Pandas code on its own and returns the answer.

## What it does
- Answers questions like "Which category has the highest profit?"
- Creates charts such as monthly sales trends

## Tech used
Python, Pandas, LangChain, Google Gemini API, Google Colab

## Dataset
Superstore Sales Dataset (Kaggle)

## How to run
1. Open the notebook in Google Colab
2. Add your Gemini API key in Colab Secrets as GOOGLE_API_KEY
3. Upload the Superstore CSV and run all cells

## Example questions
- Which 5 customers have the highest total sales?
- Which region has the lowest profit?
