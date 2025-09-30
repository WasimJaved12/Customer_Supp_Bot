# Customer Support Bot

This project is an AI-powered Customer Support Bot built in Python.  
It can train on a PDF document, answer customer queries using NLP,  
and refine its responses based on simulated feedback.  

---

# Features
-  Load and process PDF documents with PyPDF2  
-  Semantic search using SentenceTransformers (`all-MiniLM-L6-v2`)  
-  Answer queries using DistilBERT (question-answering model)  
-  Generate/refine responses with GPT-2 (text generation)
-  Simulated feedback loop (`good`, `too vague`, `not helpful`)  
-  Logging of queries, responses, and feedback (`support_bot_log.txt`)  
-  Graceful fallback for out-of-scope queries  

---

Github link - https://github.com/WasimJaved12/C_S_BOT

pip install torch transformers sentence-transformers PyPDF2

# Usage
To Run the Bot

Open the notebook in Jupyter and run main.ipynb by clicking the play button


When prompted, select a PDF document 
Ask your queries interactively in the console.
Responses will improve based on feedback simulation.

customer-support-bot/
│── main.ipynb              # Main Jupyter Notebook
│── README.md               # Project documentation
│── support_bot_log.txt     # Log file of bot decisions
│── Serri Doc.pdf (example)       # Sample input document (not included)
