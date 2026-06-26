# Hey, I'm Dmitry 👋

I'm a second-year **Applied Data Analysis & Artificial Intelligence** student at **HSE University, Saint Petersburg**  
at the **School of Informatics, Physics and Technology**, in partnership with **VK**.

I’m focused on **Machine Learning**, **Data Science**, and **Deep Learning**:  
from tabular ML, feature engineering and gradient boosting to PyTorch models, speech enhancement, and LLM/NLP experiments.

Currently open to **ML / DS internship opportunities**.

---

## 🚀 What I'm working on

- **Machine Learning / Data Science**: EDA, preprocessing, feature engineering, validation, metrics, gradient boosting, AutoML, ensembling
- **Deep Learning**: PyTorch, training loops, custom losses, checkpoints, inference pipelines, Transformers, audio/speech models
- **Applied AI**: local AI agents, NPC behavior, LLM/NLP, dialogue context and memory management
- **Engineering**: Python, SQL/PostgreSQL, Git, Docker, Flask, REST APIs, Telegram Bot API

---

## 🧠 Main projects

> Some repositories are currently private until coursework / hackathon defense.  
> Public links and detailed READMEs will be added soon.

### 🎮 Character.AI-like local NPC Agent for games — in progress

A local AI module for game NPCs: the character should respond in role, use dialogue history and game-world context, and preserve a consistent personality.

**Architecture idea:**

```text
character profile
+ dialogue history
+ game-world state
→ response generation
→ role / tone / consistency control
```

**Focus:** LLM/NLP, local inference, prompt/data design, character profiles, dialogue context, memory management.

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

Repository / write-up: **private for now, link soon**

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

## 🛠 Tech stack

**Languages:** Python, C++, C  

**ML / DS:**  
NumPy, Pandas, Polars, SciPy, scikit-learn, Statsmodels, Matplotlib, Plotly, Jupyter

**Models / methods:**  
Linear/Logistic Regression, Ridge/Lasso, SVM/SVR, kNN, Decision Trees, Random Forest, ExtraTrees, LightGBM, CatBoost, XGBoost, PCA/SVD, clustering, anomaly detection, recommender systems basics, uplift/time series basics

**Deep Learning:**  
PyTorch, CNN, RNN/LSTM, Transformers, attention mechanisms, audio/speech models, LLM/NLP basics

**Engineering:**  
SQL, PostgreSQL, Git, Linux CLI, Docker, Flask, REST API, Telegram Bot API

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

---

## 📫 Contacts

- Telegram: [@legenda0008](https://t.me/legenda0008)
- Email: [dvsorochan@edu.hse.ru](mailto:dvsorochan@edu.hse.ru)
- GitHub: [DmitryS-01](https://github.com/DmitryS-01)

---

## 🐟 meme 4 u

![](meme.JPG)
