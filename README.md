# 📚 AI Book Recommender App  

Deep Learning • Denoising Autoencoder • Streamlit • PyTorch  

> Intelligent book recommendation system based on Deep Learning, combining Denoising Autoencoder (DAE) and collaborative filtering with a production-ready interactive web interface.

---

## 🎯 Project Overview

Recommendation systems power modern platforms like Netflix, Amazon, and Spotify.  
This project demonstrates the full pipeline of building and deploying an AI-powered recommendation system:

✔ Data preprocessing  
✔ Model design & training  
✔ Evaluation  
✔ Web deployment  

👉 **Goal:** Deliver personalized and robust book recommendations from noisy user-book interaction data.

---

## 🧠 Technical Approach

### 🔹 Model: Denoising Autoencoder (DAE)
- Paradigm: Unsupervised Learning  
- Input: User–Book rating matrix  
- Framework: PyTorch  

### 🔹 Strategy
- Inject noise into user ratings
- Learn compact latent representations
- Reconstruct ratings to predict preferences
- Generate Top-N recommendations

The denoising mechanism improves robustness and generalization.

---

## 🖥️ Web Application (Streamlit)

### Features
- 👤 Select a user ID  
- 🔢 Choose number of recommendations  
- 📚 Display recommended books  
- 🌐 Fetch metadata via Google Books API  
- 📥 Export recommendations as CSV  
- ⚡ Cached API calls for better performance  

---

## ✨ Key Features

✅ Personalized recommendations  
✅ Deep Learning model (PyTorch)  
✅ External API integration (Google Books API)  
✅ Optimized API calls (caching)  
✅ Modular & maintainable architecture  
✅ Ready-for-demo UI  

---


## 🛠️ Tech Stack

| Domain | Technologies |
|--------|--------------|
| Language | Python |
| Deep Learning | PyTorch |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Web UI | Streamlit |
| API | Google Books API |
| Version Control | Git / GitHub |



---

## 🚀 Installation

```bash
git clone https://github.com/<your-username>/Book_recommender_app.git
cd Book_recommender_app
pip install -r requirements.txt
streamlit run app.py
```
---

🔍 Business Use Cases

Online bookstores

E-commerce platforms

Educational platforms

AI Proof of Concept

Personalization engines
---

📈 Future Improvements

Hybrid recommendation (content-based + collaborative)

Embedding visualization

Online learning with user feedback

REST API version (FastAPI)

Docker & Cloud deployment

MLOps pipeline integration
---



👤 Author

Salima Qritel
Data Science / AI Engineer

---
