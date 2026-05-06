#  TruthLens – Fake News Detection & Verification System

##  Overview

This project presents TruthLens, a hybrid fake news detection framework that integrates fine-tuned BERT with Retrieval-Augmented Generation through Tavily-powered live web search and FAISS-based semantic retrieval. The proposed system addresses the fundamental limitation of purely text-driven classifiers by grounding classification decisions in externally
retrieved, verified factual evidence.

---

##  Features

*  Fake news classification using ML/NLP models
*  Context-aware analysis using transformer-based models
*  Semantic similarity search using FAISS
*  Real-time verification using external APIs
*  FastAPI-based backend for efficient processing

---

##  Tech Stack

* Python
* FastAPI
* Transformers (BERT)
* FAISS (Facebook AI Similarity Search)
* Scikit-learn
* Pandas & NumPy

---

##  Live Demo

⚠️ This project is currently deployed using a temporary tunneling service (ngrok), so the link may not always be active.

👉 **Live Link:**
https://plentiful-slush-antidote.ngrok-free.dev/

---

##  Demo Screenshots

![Home](assets/home.png)
![Prediction](assets/prediction.png)

---

##  Demo Video

👉 [Watch Demo](PASTE_YOUR_VIDEO_LINK_HERE)

---

##  How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set environment variables

Create a `.env` file and add:

```env
NEWS_API_KEY=your_key_here
GROQ_API_KEY=your_key_here
TAVILY_API_KEY=your_key_here
```

### 4. Run the server

```bash
uvicorn app.main:app --reload
```

### 5. (Optional) Expose using ngrok

```bash
ngrok http 8000
```

---

##  How It Works

1. User inputs news text
2. Text is preprocessed and embedded
3. Model predicts whether it is fake or real
4. FAISS retrieves similar content
5. External APIs provide supporting evidence

---

##  Future Improvements

* Permanent cloud deployment (e.g., Render)
* UI/UX enhancements
* Model optimization for faster inference
* Expanded dataset for better accuracy

---

##  Author

Apoorv Raizada @apoorvvraizadaa@gmail.com 
Mehul Sangwan @mehulsangwan108@gmail.com

---

##  Note

This project is developed as part of a minor academic project and demonstrates the application of NLP and machine learning in misinformation detection.

