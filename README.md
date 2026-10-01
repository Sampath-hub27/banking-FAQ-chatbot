# banking-FAQ-chatbot
AI-powered Banking FAQ Chatbot using semantic search and sentence embeddings.
# 🏦 Banking FAQ Chatbot

An AI-powered Banking FAQ Chatbot that uses semantic search
to understand user questions and retrieve relevant answers.

## Features

- 💬 Text-based conversation
- 🧠 Semantic question matching
- 🔎 FAQ search
- 📚 1,764 banking Question-Answer pairs
- 📊 Cosine similarity
- 🎨 Gradio interface
- 💾 Conversation history

## Technologies

- Python
- Gradio
- Sentence Transformers
- Scikit-learn
- NumPy
- Google Colab

## AI Model

The chatbot uses:

all-MiniLM-L6-v2

for generating sentence embeddings.

## How It Works

User Question
      ↓
Text Embedding
      ↓
Semantic Search
      ↓
Cosine Similarity
      ↓
Best Matching FAQ
      ↓
Answer
      ↓
Chat History

## Dataset

The project contains banking-related FAQ
Question and Answer pairs.

## Run

Install the dependencies:

pip install -r requirements.txt

Then open:

banking_faq_chatbot.ipynb

and run the notebook.
