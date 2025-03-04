# 🏫 University of New Haven Chatbot

## 📌 Overview
The **University of New Haven Chatbot** is an AI-powered assistant designed to answer any queries related to the university. It extracts information from official university sources using web scraping, processes the data, and leverages machine learning to provide accurate responses. This chatbot serves as an informative tool for students, faculty, and prospective applicants.

## 🌍 Data Sources
The chatbot gathers information from the following university sources:
- [Undergraduate Catalog](https://catalog.newhaven.edu/content.php?catoid=31&navoid=2062)
- [Graduate Catalog](https://catalog.newhaven.edu/content.php?catoid=30&navoid=2025)
- [University Sitemap](https://www.newhaven.edu/sitemap.xml)

## 📁 Project Structure

college-chatbot/ │── data/ # Raw and cleaned extracted data │ ├── extracted_links.csv # Links extracted via web scraping │ ├── cleaned_texts/ # Processed text files │── models/ # Machine learning models │ ├── chatbot_model.pkl # Trained chatbot model │ ├── vector_store/ # Vector embeddings │── notebooks/ # Jupyter notebooks │ ├── siri_cap.ipynb # LLM model notebook │ ├── php_extract.ipynb # Web scraping notebook │── scripts/ # Python scripts for automation │ ├── scrape_data.py # Scrapes and processes university data │ ├── train_model.py # Trains the chatbot model │ ├── query_chatbot.py # Queries chatbot responses │── webapp/ # Chatbot UI components │ ├── index.html # Front-end interface │ ├── app.js # JavaScript functionality │ ├── styles.css # CSS styles │── requirements.txt # List of dependencies │── README.md # Project documentation │── .gitignore # Excludes unnecessary files │


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

