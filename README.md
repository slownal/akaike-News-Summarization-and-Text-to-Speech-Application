# Assignment: News Summarization and Text-to-Speech Application 

This project extracts news from Google News, summarizes the content using NLP models, performs sentiment analysis, and converts summaries into Hindi audio using TTS.

## Features  
- **News Extraction:** Scrapes Google News for articles.  
- **Summarization:** Uses a transformer-based NLP model to summarize articles.  
- **Sentiment Analysis:** Classifies news as Positive, Negative, or Neutral.  
- **Text-to-Speech (TTS):** Converts summaries into Hindi audio.  
- **API Access:** FastAPI-based backend for easy integration.  
- **Frontend Interface:** Built with Streamlit for user interaction.  

## Installation  

### **1. Clone the Repository**
```bash
git clone https://github.com/slownal/akaike-News-Summarization-and-Text-to-Speech-Application.git  
cd akaike-News-Summarization-and-Text-to-Speech-Application

### **2. Set Up a Virtual Environment  

#### Windows (Command Prompt or PowerShell)
```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux (Terminal)
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 4️ Run the Streamlit Application  
```bash
streamlit run app.py
```

 **The application should now be running in your browser!** 


