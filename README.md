# Offline-Learning-Platform- 
An **AI-powered offline chatbot** designed to assist users in rural or low-connectivity areas.  
The system provides intelligent, context-aware responses without needing an internet connection, ensuring accessibility, privacy, and reliability.

---

## 🚀 Features
- Works **completely offline**
- Understands user queries using **intent detection**
- Uses **TensorFlow Lite** for on-device inference
- Stores and retrieves responses from **SQLite database**
- Lightweight and optimized for low-end devices
- Optional cloud sync for model updates

---

## 🧩 Tech Stack
- **Frontend:** Flutter / Kotlin  
- **Backend (optional):** FastAPI / Firebase  
- **AI Model:** TensorFlow Lite (TFLite)  
- **Database:** SQLite  
- **NLP Tools:** NLTK, spaCy  

---

## ⚙️ How It Works
1. **User inputs a query** (text or voice)  
2. **Text is preprocessed** — cleaned, tokenized, and normalized  
3. **TFLite model** classifies the intent  
4. **Response is fetched** from the local SQLite database  
5. **Reply is displayed** instantly without internet  

---
