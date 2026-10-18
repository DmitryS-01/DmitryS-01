# Hey, I'm Dmitry 👋

I'm an **Applied Data Analysis & Artificial Intelligence** student at  
**HSE University, Saint Petersburg**, School of Informatics, Physics and Technology, in partnership with **VK**.

I work on applied Machine Learning projects: from EDA and model experiments to reproducible training pipelines, evaluation, Docker environments, and working demos.

**Yandex Kinopoisk RecSys.**

[![Telegram](https://img.shields.io/badge/Telegram-@legenda0008-26A5E4?logo=telegram&logoColor=white)](https://t.me/legenda0008)
[![Email](https://img.shields.io/badge/Email-dvsorochan@edu.hse.ru-D14836?logo=gmail&logoColor=white)](mailto:dvsorochan@edu.hse.ru)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-DmitryS--01-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/DmitryS-01)

---

## 🧠 Main projects

### 🎧 Speech Enhancement on VoiceBank+DEMAND

**Single-channel speech enhancement:**

```text
noisy wav → STFT → neural network → ISTFT → enhanced wav
```

Built a complete Deep Learning pipeline for removing background noise from speech while preserving its intelligibility and natural sound.

**What I implemented:**

- STFT / ISTFT audio preprocessing and reconstruction
- time-frequency encoder-decoder architecture
- separate magnitude and phase denoising branches
- axial self-attention over time-frequency representations
- bidirectional magnitude/phase cross-attention
- training, checkpoint selection, full-test evaluation, and batch inference
- Docker environment and web application for model inference

**Experiments:**

- trained models on **VoiceBank+DEMAND** and **MS-SNSD**
- compared multiple model sizes, architectures, and training configurations
- evaluated the models using PESQ, STOI, SI-SDR, CSIG, CBAK, COVL, and SSNR

**Best result:**

- **PESQ: 3.426**
- compact model: **~3.46M parameters**
- result comparable with strong published speech enhancement models on the same benchmark

The project is still being developed with the goal of preparing a research paper.

**Stack:** Python, PyTorch, NumPy, STFT/ISTFT, attention mechanisms, Docker, Flask.

Repository: [SpeechDenoising-DL](https://github.com/DmitryS-01/SpeechDenoising-DL)  
Demo: [Hugging Face Space](https://huggingface.co/spaces/DmitryS-01/dlproject)

---

### 🧩 VK Predict CMC Hackathon

**High-dimensional tabular binary classification:**

```text
data audit → EDA → feature engineering → validation
→ model experiments → blending → submission
```

The dataset contained:

- **247,972** training objects
- **106,274** test objects
- **1,367** anonymized and noisy features
- only **1.35%** positive examples
- almost no direct linear correlation between individual features and the target

**What I worked on:**

- data audit and exploratory data analysis
- missing values, noise, leakage, and train/test drift checks
- feature engineering and feature selection
- validation strategy and experiment tracking
- model training and hyperparameter tuning
- stacking, blending, and ensemble analysis
- final refit and submission generation

**Models tested:**

- LightGBM
- CatBoost
- XGBoost
- Random Forest
- Logistic Regression
- FLAML
- TabM

**Results:**

| Approach | ROC-AUC |
|---|---:|
| Best single model | **0.69428** |
| Best team blend | **0.71513** |

**Stack:** Python, Pandas, Polars, NumPy, scikit-learn, LightGBM, CatBoost, XGBoost, FLAML, PyTorch.

Repository: [VK_CMC_hackathon](https://github.com/DmitryS-01/VK_CMC_hackathon)  
Competition: [VK Predict CMC Hackathon](https://www.kaggle.com/competitions/vk-predict-cmc-hackathon)

---

### 📦 Ozon Tech RoboZon

**Simulation-first Computer Vision and robotics prototype for item sorting.**

```text
LiDAR / laser profiler → object dimensions
three RGB views → cross-section classification
measurements + CV output → sorting route
```

I proposed using **two independent measurement channels**:

- LiDAR or a laser profiler for reliable physical dimensions
- three RGB cameras for detecting whether an object has a circular cross-section

A rule engine combines both outputs and selects the appropriate sorting route.

**What I implemented:**

- procedural synthetic data generator
- object-disjoint train/validation/test splits
- multi-view image classification pipeline
- comparison of five Computer Vision architectures
- simulated LiDAR measurement channel
- routing rules and structured model output
- tests, Docker, JSON Schema, ONNX checks, and experiment configs

**Synthetic demonstration dataset:**

- **400 unique objects**
- **2,000 three-view samples**
- generated to demonstrate the system before real equipment and operational data became available

**Best synthetic test result:**

- **F1: 0.8916**
- **ROC-AUC: 0.9743**
- selected model: **EfficientNet-B0**

**Stack:** Python, PyTorch, OpenCV, NumPy, scikit-learn, ONNX, Docker.

Repository: [robozon](https://github.com/DmitryS-01/robozon)

---

### 📚 AI Study Assistant

**RAG system for university lectures, course materials, and personal notes.**

```text
PDF files and notes
→ cleaning and chunking
→ embeddings
→ vector index
→ relevant fragments
→ structured answer / LaTeX notes
```

The core retrieval pipeline is implemented; final integration and interface work are currently in progress.

**What the system does:**

- processes PDF lectures and course materials
- cleans and splits documents into searchable fragments
- builds embeddings and a vector index
- retrieves up to ten relevant fragments for a user query
- handles typos, conversational wording, and paraphrased questions
- combines information from several relevant sources
- generates structured LaTeX lecture notes using my own template

**Evaluation:**

- prepared a local set of queries and relevant documents
- retrieval quality is evaluated using **MAP@10**
- experiments are checked on both direct and paraphrased queries

**Stack:** Python, embeddings, vector search, PDF processing, LaTeX.

Repository: **private for now**

---

### 🤖 Generalized MNK Game Research Platform

A course research project for studying learning algorithms in generalized **M×N×K games with D-properties**.

```text
game configuration
→ AI strategy
→ automatic match series
→ statistics and state analysis
```

**What we implemented:**

- configurable game environment
- human-vs-AI and AI-vs-AI modes
- DQN agent
- classical MCTS
- AlphaZero-style approach
- automated tournament series
- experiment statistics and visualization
- analysis and counting of unique game states

The project won the course nomination for **“Most Scientific Project.”**

**Stack:** Python, PyTorch, Reinforcement Learning, DQN, MCTS.

Repository: [tic-tac-toe-RL-HSE-ADA-AI](https://github.com/DmitryS-01/tic-tac-toe-RL-HSE-ADA-AI)

---

## 🛠 Tech stack

**Languages:**  
Python, C++, C, SQL

**Machine Learning:**  
scikit-learn, LightGBM, CatBoost, XGBoost, classification, regression, clustering, dimensionality reduction, recommender systems basics, time series basics

**Deep Learning:**  
PyTorch, CNN, RNN/LSTM, Transformers, attention mechanisms, Computer Vision, speech and audio models

**Data:**  
NumPy, Pandas, Polars, SciPy, PostgreSQL, Jupyter

**Engineering:**  
Git, Linux, Docker, Flask, LaTeX

**Systems:**  
computer architecture, operating systems, processes, virtual memory, system calls, basic assembly

---

## 🎓 Education

**HSE University, Saint Petersburg**  
**Applied Data Analysis & Artificial Intelligence**, 2024–2028  
School of Informatics, Physics and Technology, in partnership with **VK**

Relevant coursework:

- Machine Learning
- Deep Learning
- Mathematical Analysis
- Probability Theory and Mathematical Statistics
- Information Theory
- Linear Algebra
- Optimization
- Numerical Methods
- Algorithms and Data Structures
- Databases
- Computer Architecture and Operating Systems

Additional education:

- **ML Start**
- Stepik **Generation Python** courses
- selected modules from the Yandex backend development course

---

## 🌱 A bit more about me

- English: **B2**
- Duolingo streak: **495 days**
- Interested in **chess**, mathematical problems, low-level systems, and understanding how software works under the hood

---

## 📫 Contacts

- Telegram: [@legenda0008](https://t.me/legenda0008)
- Email: [dvsorochan@edu.hse.ru](mailto:dvsorochan@edu.hse.ru)
- Hugging Face: [DmitryS-01](https://huggingface.co/DmitryS-01)

---

## 🐟 meme 4 u

![](meme.JPG)
