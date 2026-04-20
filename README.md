# Infotact_internship_project1
# NYC 311 Service Requests Analysis

## 📌 Overview
This project develops an **AI-powered NLP pipeline** to analyze NYC 311 Service Requests.  
The goal is to automate complaint routing, detect sentiment, and assign urgency scores.  
It follows a structured **4-week roadmap**:

- **Week 1:** Text Cleaning & Exploratory Data Analysis (EDA)  
- **Week 2:** Department Categorization (TF‑IDF + Logistic Regression)  
- **Week 3:** Sentiment Analysis & Urgency Scoring (Naive Bayes)  
- **Week 4:** API Deployment (FastAPI + Uvicorn)


## 📂 Structure
project/    
│── notebooks/ (Week1–3 Jupyter notebooks)      
│── app/main.py (FastAPI app)    
│── models/ (saved .pkl models)    
│── data/311-service-requests-subset.csv    
│── README.md    


---

## ⚙️ Tech Stack
- **Languages/Libraries:** Python, Pandas, NumPy, scikit‑learn, NLTK, TextBlob, WordCloud, Matplotlib  
- **Models:** Logistic Regression, Naive Bayes, TF‑IDF  
- **Deployment:** FastAPI, Uvicorn  

---

## 🚀 How to Run
1. **Install dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn nltk textblob wordcloud fastapi uvicorn joblib
