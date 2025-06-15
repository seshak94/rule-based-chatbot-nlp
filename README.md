# Chatbot Development – Rule-Based with NLP

This project develops a basic chatbot using rule-based logic and NLP techniques to simulate conversation and provide automated responses to predefined intents.

## 🛠️ Technologies Used
- Python
- NLTK
- Regex
- JSON
- Google Colab / Jupyter Notebook

## 🧠 Project Highlights
- Preprocessed user input using stemming, tokenization, and lowercasing
- Mapped user input patterns to intents using a rules-based JSON structure
- Built a simple NLP engine for intent recognition and response generation
- Handled unknown queries gracefully with default fallback responses

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install nltk

2. Run chatbot_dev.ipynb in Google Colab or Jupyter Notebook.

📁 Files
chatbot_dev.ipynb – main notebook

intents.json – JSON file defining user intents, patterns, and responses

💬 Sample Interaction
vbnet
Copy
Edit
User: Hello
Bot: Hi there! How can I assist you today?

User: What services do you offer?
Bot: I can help you with account queries, billing, and technical support.
