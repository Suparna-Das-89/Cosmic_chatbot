# 🌌 [Cosmic Chatbot: Ask the Universe!](https://cosmicchatbot.streamlit.app/)

> 👉 **[Click here to try the live chatbot](https://cosmicchatbot.streamlit.app/)**  
> Ask space-related questions and get real-time, LLM-powered answers from the cosmos!


**Ever wanted to ask the cosmos about black holes, solar flares, or the next full moon?**  
This interactive Streamlit chatbot connects you to space knowledge from NASA, Wikipedia, arXiv, and more — all powered by state-of-the-art LLMs and embeddings.


## 🚀 Features

- **LLM-Powered Responses** using [Groq's](https://groq.com/) hosted LLaMA 3 model
- **Wikipedia & DuckDuckGo Summaries** for fast factual answers
- **NASA Astronomy Picture of the Day (APOD)** embedded
- **Latest NASA News** from RSS feeds
- **Live Solar Activity Updates** from NOAA
- **Moon Phase Predictions** via `ephem`
- **arXiv Paper Search** for space-related research
- **Semantic Topic Detection** using SBERT embeddings


## 🧑‍💻 Tech Stack

**Tools and Purposes:**

Streamlit : Web interface                           
Groq LLaMA 3 LLM : Large Language Model (via API)          
HuggingFace SBERT : Semantic similarity (topic matching)    
llama-index : Context indexing and retrieval          
NASA & NOAA APIs : Astronomy data                          
Wikipedia API : Factual summaries                       
arXiv Python : Scientific paper search                 


## ⚙️ Installation & Setup

1. **Clone this repository**  

2. **Install required packages**

   pip install -r requirements.txt

4. **API Keys**

   Create a .streamlit/secrets.toml file and add:
   GROQ_API_KEY = "your_groq_api_key"
   NASA_API_KEY = "your_nasa_api_key"

6. **Run the app**

   streamlit run app.py

## Example Questions

"When is the next full moon?"

"What is a black hole?"

"Tell me about solar flares"

"What’s the latest research on dark matter?"

## Acknowledgements

NASA Open APIs

Groq

Wikipedia REST API

arXiv API

LlamaIndex

HuggingFace Sentence Transformers
