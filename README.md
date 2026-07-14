# create_chatbot_using_python
This code is an implementation of a simple chatbot using TensorFlow, which is a machine learning framework developed by Google. The chatbot is trained using a neural network to classify user inputs into predefined intents and provide appropriate responses based on the detected intent.
The intents.json file is the data that we will provide to our chatbot 

# Custom AI Chatbot using Python 🤖

A lightweight, intelligent conversational agent built from scratch using Python. This project demonstrates core concepts of natural language processing (NLP), text preprocessing, and intent recognition to simulate human-like interactions.

---

### 🛠️ Tech Stack & Architecture

* **Language:** Python 3.x
* **Libraries & Frameworks:** `nltk` (Natural Language Toolkit), `numpy`, `json` (Intent handling)
* **Concepts Applied:** Tokenization, Stemming, Bag-of-Words Model, and Neural Network Classification.

---

### ✨ Features

* **Intent Recognition:** Uses a structured JSON intents file to recognize user greetings, goodbyes, and specific queries.
* **Text Preprocessing Pipeline:** Implements custom tokenization and stemming algorithms to clean user inputs efficiently.
* **Contextual Response Generation:** Matches user inputs with the highest probability patterns to return accurate, contextual answers.

---

### 🚀 Installation & Local Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Simrannegi26/create_chatbot_using_python.git](https://github.com/Simrannegi26/create_chatbot_using_python.git)
   cd create_chatbot_using_python

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

pip install -r requirements.txt

python chatbot.py
