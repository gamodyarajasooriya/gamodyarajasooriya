# Gamodya Rajasooriya

Final-year Computer Science undergraduate at NSBM Green University (Plymouth University, Sri Lanka)  
Graduating November 2026 · Based in Sri Lanka

I build applied AI and ML systems end-to-end — from messy real-world data through to deployed products.  
My focus: making AI actually useful, not just accurate.

---

## 🚀 Projects

### 🔵 RupiSaver — USD/LKR Forecasting & Remittance Decision Platform
> Final Year Project · 2025–2026 · Submitted to IEEE ICTAR 2026

Two-stage ML pipeline forecasting USD/LKR exchange rates 5 days ahead to help Sri Lankan migrant workers time their remittances optimally.

- **Stage 1:** XGBoost on 33 macroeconomic features predicts US Dollar Index (DXY)
- **Stage 2:** Gradient Boosting with Huber loss forecasts USD/LKR · MAE 0.31–0.52 LKR across three unseen market conditions
- **RupiGuide:** RAG chatbot with pgvector semantic search · Ollama/Llama 2 + Gemini API fallback
- **Data Engineering:** Resolved Yahoo Finance–CBSL rate divergence via Volatility Guard and 70/30 blended gap method
- **Result:** 86.4% adoption intent over Google/bank apps across 22 pilot users

`XGBoost` `Gradient Boosting` `FastAPI` `Next.js 14` `PostgreSQL` `pgvector` `Docker` `RAG` `Ollama`

---

### 🟣 PathFinder — Multi-Agent AI Study Abroad Advisor
> Ongoing · Deployed on Hugging Face Spaces

5-agent CrewAI pipeline advising Sri Lankan students on overseas university options with real-time grounded data.

- Profile Analyst → University Finder → Scholarship Expert → Visa Advisor → Strategic Advisor
- Tavily real-time web search grounds agent outputs in live tuition, scholarship, and visa data
- Silent LLM failover: Groq Llama 3.3 70B → Llama 3.1 8B Instant
- Sri Lanka-specific inputs: O/L, A/L, Z-score, LKR budget

`CrewAI` `Groq` `Tavily` `Docker` `Hugging Face Spaces` `Pydantic` `Multi-Agent`

---

### ⚙️ Vehicle Repair Management System (VRMS)
> 2024 · Full Stack Development · Team Project

Web-based platform digitizing the entire vehicle repair workflow — replacing paper records, phone calls, and manual tracking.

- OTP-based customer authentication and appointment booking
- Real-time repair status tracking via Socket.IO — customers track progress without calling
- Automated invoice generation, warranty and inventory management
- Staff attendance and administrative management
- CI/CD via GitHub Actions · Dockerized builds · AWS EC2 deployment-ready

`Angular` `Node.js` `Express.js` `MongoDB` `Socket.IO` `Docker` `GitHub Actions` `AWS EC2`

### 🟠 Gait-Based Biometric Authentication
> 2025 · Deep Learning

Passive continuous authentication from smartphone walking patterns — no user interaction needed.

- 133 statistical and frequency-domain features from accelerometer and gyroscope signals
- FFMLP with Gaussian noise augmentation for cross-day robustness
- **96.9% cross-day accuracy · 1.14% Equal Error Rate (EER)**

`TensorFlow` `Keras` `Signal Processing` `Feature Engineering`

---

### 🟡 E-Commerce Delivery Delay Prediction
> 2025 · Big Data

Predicted delivery delays on 100K+ orders to enable proactive logistics intervention.

- Processed 6 joined tables on Databricks with Apache Spark
- Engineered seller delay-rate feature — boosted AUC from 0.738 to 0.807
- Resolved 92:8 class imbalance
- **88.6% accuracy · 0.807 AUC-ROC · Projected $1.7M–$4.3M recoverable value**

`Databricks` `Apache Spark` `XGBoost` `Feature Engineering` `Imbalanced ML`

---

### 🟢 Flight Delay Prediction — Imbalanced ML System
> 2025

Demonstrated that threshold tuning is a business decision, not a technical one.

- KNN imputation, target encoding, time-of-day feature bins
- Lowering XGBoost threshold from 0.5 → 0.4 significantly improved recall on real delays
- **F1 (delay class): 0.34 → 0.46 · ROC-AUC: 0.75**

`XGBoost` `scikit-learn` `Imbalanced ML` `Threshold Tuning`

---

### 🔴 Financial News Sentiment Analysis
> 2025 · NLP / Deep Learning

Systematic DNN → RNN → LSTM comparison on 3-class financial sentiment classification.

- TF-IDF preprocessing on financial news corpus
- Handled class imbalance via dropout, layer tuning, early stopping
- **Best LSTM: 64% accuracy · Weighted F1 ≈ 0.64**

`TensorFlow` `Keras` `LSTM` `TF-IDF` `NLTK` `NLP`

---

### 🏆 SkillHub — Accessibility-Focused Learning Platform
> 2025

- IDEATHON Winner
- AIESEC UoM Idealize Semi-Finalist  
- NSBM GreenExe Top 8 Finalist
- NBQSA National Best Quality Software Awards Participant

---

## 🛠️ Tech Stack

**ML & DL:** Python · scikit-learn · XGBoost · Gradient Boosting · TensorFlow · Keras · LSTM · Random Forest  
**Gen AI & RAG:** CrewAI · pgvector · Ollama · Llama 2 · Gemini API · Groq · Tavily · Prompt Engineering · LLM Failover  
**Data:** Pandas · NumPy · Apache Spark · Databricks · SQLAlchemy  
**Backend:** FastAPI · Node.js · Django · REST APIs · JWT · WebSockets  
**Frontend:** Next.js · React · Angular · Tailwind CSS · Flutter  
**DevOps:** Docker · GitHub Actions · Pytest · Hugging Face Spaces · Gunicorn  
**Databases:** PostgreSQL · MongoDB Atlas · MySQL  

---

## 🌱 Currently Exploring
- **Agentic AI:** LangGraph · AutoGen (building on CrewAI experience)
- **MLOps:** MLflow for experiment tracking, model versioning, drift detection
- **Computer Vision:** CNNs and vision transformers with OpenCV and PyTorch
- **Cloud ML:** AWS SageMaker · Google Vertex AI

---

## 🏅 Achievements
- NSBM IDEATHON 2025 — **Winner**
- NSBM GreenExe 3.0 — **Top 8 Finalist**
- AIESEC UoM Idealize — **Semi-Finalist**
- NBQSA National Best Quality Software Awards — Participant
- IEEE ICTAR 2026 — Paper submitted

---

## 📫 Connect
- **LinkedIn:** [Gamodya Rajasooriya](https://linkedin.com/in/gamodya-rajasooriya)
- **Email:** gamodyarajasooriya@gmail.com

---

⚡ *The hardest part of my final year project wasn't the ML model — it was discovering that two financial data sources were silently reporting different numbers for the same exchange rate, and engineering three solutions to fix it.*
