# Hey, I'm Dmitry 👋

I'm a second-year **Applied Data Analysis & Artificial Intelligence** student at **HSE University, Saint Petersburg**  
at the **School of Informatics, Physics and Technology**, in partnership with **VK**.

I’m focused on **Machine Learning**, **Data Science**, and **Applied AI**:  
from tabular ML, feature engineering and gradient boosting to PyTorch models, speech enhancement, RAG systems, OCR pipelines, and LLM-powered tools.

Currently open to **ML / DS internship opportunities**.

---

## 🚀 What I'm working on

- **Machine Learning / Data Science**: EDA, preprocessing, feature engineering, validation, metrics, gradient boosting, AutoML, ensembling
- **Deep Learning**: PyTorch, training loops, checkpoints, inference pipelines, Transformers, audio/speech models
- **LLM / RAG systems**: document parsing, OCR, chunking, embeddings, vector search, retrieval, answer generation with citations
- **Applied AI tools**: AI assistants over private knowledge bases, handwritten notes processing, LaTeX lecture notes generation
- **Engineering**: Python, SQL/PostgreSQL, Git, Docker, Flask, Streamlit, REST APIs, Telegram Bot API

---

## 🧠 Main projects

> Some repositories are currently private until coursework / hackathon defense.  
> Public links and detailed READMEs will be added soon.

### 📚 AI Study Assistant: RAG + handwritten notes to LaTeX lecture notes — in progress

An AI assistant for working with my university materials: PDF lectures, handwritten notes, course files, and personal study notes.

The system is designed to:

- search through a private knowledge base
- retrieve relevant fragments from lectures and notes
- answer questions with citations
- process handwritten materials
- generate structured **LaTeX lecture notes** using my own template

**Pipeline:**

```text
PDFs / handwritten notes / course files
→ document parsing + OCR
→ chunking
→ embeddings
→ vector search
→ retrieval
→ LLM answer generation with citations
→ LaTeX lecture notes generation
```

**Focus:** RAG, semantic search, embeddings, vector databases, OCR/document preprocessing, LLM-based question answering, LaTeX generation.

**Stack:** Python, LangChain, FAISS/Chroma, Streamlit, pypdf, OCR/preprocessing, LLM API, LaTeX.

Repository: **private for now, link soon**

---

### 🎧 Speech Enhancement on VoiceBank+DEMAND

Single-channel speech enhancement pipeline:

```text
noisy wav → enhanced wav
```

Implemented a Transformer-style model for magnitude/phase denoising with:

- STFT / ISTFT
- encoder-decoder architecture
- magnitude and phase branches
- bidirectional magnitude/phase cross-attention
- training and evaluation pipeline

**Best results:**

- PESQ: **3.3563**
- STOI: **0.9592**
- SI-SDR: **19.85**
- compact ~4M params model: **PESQ 3.3329**

Also built a **Flask inference app** for uploading audio files/archives and downloading enhanced versions.

Repository: **private for now, link soon**

---

### 🧩 VK Predict Hackathon — Top-1 private score

Tabular ML competition with high-dimensional anonymized data:

- **1360+ features**
- class imbalance
- noisy and masked values
- binary classification task

Built an end-to-end ML pipeline:

- EDA and leakage checks
- feature engineering and feature selection
- validation strategy
- LightGBM / CatBoost / XGBoost / Random Forest / ExtraTrees
- FLAML AutoML and Optuna tuning
- stacking, blending, and ensemble weight search

Best holdout validation: **ROC-AUC 0.715**

Repository: [ml-project-adaai_VK_predict_hackathon](https://github.com/medlopi/ml-project-adaai_VK_predict_hackathon)

---

### 🤖 DQN for generalized MNK game with D-properties

Reinforcement learning project for a generalized tic-tac-toe-like environment.

Implemented:

- game environment
- state/action space
- reward signal
- Deep Q-Network agent
- training and strategy evaluation

Repository: [tic-tac-toe-RL-HSE-ADA-AI](https://github.com/DmitryS-01/tic-tac-toe-RL-HSE-ADA-AI)

---

### 📦 Ozon Tech “Robozon” — Computer Vision / Robotics Hackathon

Team project for a CV-based solution aimed at automating sorting-center workflows and intelligent item sorting.

My focus:

- data and annotation pipeline
- baseline approaches
- metrics
- experimental pipeline

Repository / write-up: **private for now, link soon**

---

## 🛠 Tech stack

**Languages:** Python, C++, C  

**ML / DS:**  
NumPy, Pandas, Polars, SciPy, scikit-learn, Statsmodels, Matplotlib, Plotly, Jupyter

**Models / methods:**  
Linear/Logistic Regression, Ridge/Lasso, SVM/SVR, kNN, Decision Trees, Random Forest, ExtraTrees, LightGBM, CatBoost, XGBoost, PCA/SVD, clustering, anomaly detection, recommender systems basics, uplift/time series basics

**Deep Learning:**  
PyTorch, CNN, RNN/LSTM, Transformers, attention mechanisms, audio/speech models, LLM/NLP basics

**LLM / RAG:**  
RAG, embeddings, vector search, chunking, reranking basics, OCR/document parsing, answer generation with citations, LaTeX generation

**Engineering:**  
SQL, PostgreSQL, Git, Linux CLI, Docker, Flask, Streamlit, REST API, Telegram Bot API, LaTeX

---

## 🎓 Education

**HSE University, Saint Petersburg**  
**Applied Data Analysis & Artificial Intelligence**, 2024–2028

Relevant coursework:

- Machine Learning
- Deep Learning
- Probability Theory
- Mathematical Statistics
- Numerical Methods
- Linear Algebra
- Optimization
- Algorithms and Data Structures
- Databases
- Python / C++ programming

---

## 🌱 A bit more about me

- English: **B2**
- Duolingo streak: **464 days**
- Interested in **chess**, ML systems, applied AI tools, and building projects that are actually useful
- Also built Telegram bots for catalogs, orders, notifications, and API integrations

---

## 📫 Contacts

- Telegram: [@legenda0008](https://t.me/legenda0008)
- Email: [dvsorochan@edu.hse.ru](mailto:dvsorochan@edu.hse.ru)
- GitHub: [DmitryS-01](https://github.com/DmitryS-01)

---

## 🐟 meme 4 u

![](meme.JPG)
