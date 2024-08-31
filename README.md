# Sentiment Analysis App

![LLM](https://img.shields.io/badge/Transformers-green)
![Python](https://img.shields.io/badge/python-3.7%2B-blue)
![Deployment](https://img.shields.io/badge/Streamlit.-orenge)

A user-friendly web application for sentiment analysis built with Streamlit and Hugging Face Transformers. This app allows users to input text, analyze its sentiment, and receive a star rating based on the sentiment.

## Features

- **Real-time Sentiment Analysis:** Analyze the sentiment of any text and receive instant feedback.
- **Intuitive Interface:** Simple buttons for submitting text and refreshing the page.
- **Open Source:** Free to use and modify for your needs.

## Working Principle

1. **Text Input:** Users enter a piece of text into the provided input area.
2. **Model Loading:** The app uses the `nlptown/bert-base-multilingual-uncased-sentiment` model from Hugging Face's Transformers library. This model is designed for sentiment analysis and can handle multiple languages.
3. **Sentiment Analysis:** When the "Submit" button is clicked, the app sends the input text to the model for analysis. The model processes the text and predicts its sentiment.
4. **Result Display:** The sentiment analysis model provides an output label (e.g., `5 stars`) and a confidence score. The app displays these results to the user.
5. **Refresh Functionality:** The "Refresh" button allows users to clear the input area and start a new analysis.

## Use Cases

1. **Customer Feedback Analysis:**
   - Businesses can use this app to analyze customer feedback or reviews to gauge overall sentiment. This helps in understanding customer satisfaction and areas needing improvement.

2. **Social Media Monitoring:**
   - Users can analyze sentiment from social media posts or comments to monitor public opinion about brands, products, or events.

3. **Content Moderation:**
   - The app can be used to detect and flag negative or harmful content in user-generated content, ensuring a positive online environment.

4. **Market Research:**
   - Researchers can analyze sentiment from survey responses or focus group feedback to gain insights into consumer attitudes and preferences.

5. **Personal Use:**
   - Individuals can use the app to analyze the sentiment of their own written content, such as blog posts, personal messages, or creative writing.
