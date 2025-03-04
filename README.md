# 🏫 University of New Haven Chatbot

## 📌 Overview
The **University of New Haven Chatbot** is an AI-powered assistant designed to answer any queries related to the university. It extracts information from official university sources using web scraping, processes the data, and leverages machine learning to provide accurate responses. This chatbot serves as an informative tool for students, faculty, and prospective applicants.

## 🌍 Data Sources
The chatbot gathers information from the following university sources:
- [Undergraduate Catalog](https://catalog.newhaven.edu/content.php?catoid=31&navoid=2062)
- [Graduate Catalog](https://catalog.newhaven.edu/content.php?catoid=30&navoid=2025)
- [University Sitemap](https://www.newhaven.edu/sitemap.xml)
 

## 🚀 Features
✔ **Web Scraping** – Extracts relevant university information from official sources  
✔ **Natural Language Processing (NLP)** – Uses ML models for accurate query responses  
✔ **Vector Search with ChromaDB** – Efficient information retrieval for precise answers  
✔ **Interactive Chat Interface** – Simple and user-friendly web-based chatbot  
✔ **Real-time Updates** – Continuously learns from newly extracted data  
✔ **Deployment Ready** – Can be hosted on cloud platforms  

## ⚡ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/college-chatbot.git
cd college-chatbot
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Chatbot
To run in CLI mode:
python query_chatbot.py

🛠️ Technology Stack

🔹 Python – Backend processing
🔹 BeautifulSoup, Scrapy – Web scraping
🔹 ChromaDB – Vector storage for search
🔹 FastAPI – Web API for chatbot responses
🔹 LLM (Large Language Models) – Enhances response accuracy
🔹 HTML, CSS, JavaScript – Front-end interface

📊 Machine Learning Model

Uses pre-trained LLM embeddings to process and generate accurate responses.
The chatbot converts user queries into vector embeddings and searches the best-matching university-related information.
📖 Acknowledgment

This project was developed under the guidance of Professor Dr.Ardiana Sula and Dr.Muhammad Aminul Islam as part of our Capstone Project at the University of New Haven.



