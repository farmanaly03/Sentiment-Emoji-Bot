# 🤖 Sentiment Emoji Bot

A simple and fun NLP project using Hugging Face Transformers that analyzes the sentiment of a given text and responds with expressive emojis. It combines sentiment detection with keyword-based emoji enhancement to make text interaction more engaging.

---

## 📌 Features

- **Sentiment Analysis**: Classifies text as `POSITIVE`, `NEGATIVE`, or `NEUTRAL`.
- **Emoji Mapping**: Associates each sentiment with a set of emojis.
- **Keyword-Based Emoji Enhancement**: Adds more emojis based on keywords like `happy`, `love`, `angry`, etc.
- **Built using Hugging Face's Transformers Pipeline**

---

## 🚀 How It Works

1. User enters a text string.
2. The model detects the sentiment using `distilbert-base-uncased-finetuned-sst-2-english`.
3. Based on sentiment and keywords, it returns relevant emojis.

Sentiment Emoji Bot is a simple Python tool built using Hugging Face’s transformers library that detects the sentiment of a given text (positive, negative, or neutral) and responds with relevant emojis. It enhances user interaction by converting text-based emotions into expressive visual feedback using emojis.

🔍 Features:
Sentiment Detection: Uses a pre-trained DistilBERT model (distilbert-base-uncased-finetuned-sst-2-english) for analyzing sentiment.

Emoji Mapping: Automatically maps the detected sentiment to a set of fun and expressive emojis.

Keyword-Based Emoji Support: Optionally enhances emoji response based on keywords like happy, love, sad, etc.
