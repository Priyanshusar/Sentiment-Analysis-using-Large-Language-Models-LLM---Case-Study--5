# Sentiment-Analysis-using-Large-Language-Models-LLM---Case-Study--5
A Large Language Model (LLM) based sentiment analysis project that classifies restaurant reviews as positive, negative, or neutral using NLP and deep learning.

# Overview

This project focuses on building an AI-powered Sentiment Analysis system that automatically classifies customer reviews of restaurants as positive, negative, or neutral.
Using Large Language Models (LLMs) and Natural Language Processing (NLP), the system helps organizations quickly analyze thousands of customer reviews to uncover insights and improve decision-making.

# Problem Statement
In the digital era, customers frequently share their opinions and feedback online, generating a vast amount of valuable data in the form of reviews. However, manually analyzing this massive and unstructured textual data is time-consuming, inefficient, and non-scalable.

Organizations, particularly those managing multiple restaurants, face significant challenges in extracting actionable insights from these reviews to enhance customer satisfaction and brand reputation.

Key Challenges

Unstructured Data: Customer reviews are expressed in natural language, making it difficult to extract meaningful patterns efficiently.

Data Scale: With hundreds or thousands of reviews generated daily, manual processing is not feasible.

Sentiment Understanding: Accurately identifying whether a review reflects a positive, negative, or neutral sentiment is crucial for understanding customer experiences and improving services.

# Objective
The objective of this project is to develop a robust Sentiment Analysis model using a Large Language Model (LLM) to automatically analyze customer reviews and determine their sentiment.
This system aims to:

Enable data-driven decision-making by providing real-time sentiment insights.

Help businesses understand customer satisfaction trends at scale.

Improve marketing strategies and service quality through automated feedback analysis.

# Dataset
File: restaurant_reviews.csv

Description: Contains textual reviews and their associated sentiment labels (positive/negative/neutral).
Review -     The text of the customer’s review

Sentiment -   	The sentiment category (Positive / Negative / Neutral)

# How It Works
1- Data Loading: Import and preprocess restaurant reviews.

2- Text Processing: Clean and vectorize textual data using NLP techniques.

3- Model Application: Use a Large Language Model (Gemini 2.5 / Google Generative AI) for classification.

4- Sentiment Prediction: Generate predictions and analyze results through a simple UI.

# Technologies Used

Python

Streamlit

LangChain

Google Generative AI (Gemini 2.5)

Scikit-learn

Pandas & NumPy

Matplotlib / Seaborn

dotenv

# 🚀 Future Enhancements

Integration with live restaurant review APIs (Zomato, Yelp)

Deploy as a web dashboard for real-time monitoring

Add emotion and aspect-based sentiment analysis

# How to Run the Project
## Step 1 — Clone the Repository
git clone https://github.com/yourusername/Restaurant-Sentiment-Analyzer.git

## Step 2 — Navigate to the Folder
cd Restaurant-Sentiment-Analyzer

## Step 3 — Install the Required Libraries
pip install -r requirement.txt

## Step 4 — Run the Application
### Launch the Streamlit Web App
streamlit run app.py

# License

This project is licensed under the MIT License.


















