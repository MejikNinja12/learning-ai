# Learning AI – From Fundamentals to Agentic Systems

> My journey learning AI — from core fundamentals to building agentic systems.  
Hands-on projects, clear milestones, and real outputs you can run.

---

### 🏷️ Tech Badges
![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-ready-orange)
![Hugging%20Face](https://img.shields.io/badge/Hugging%20Face-datasets%20%7C%20transformers-yellow)
![OpenAI%20API](https://img.shields.io/badge/OpenAI-API-green)

---

## 📚 Roadmap
learning-ai/
│
├── step-01_basics/
│ ├── project-1_hello-world-ml/
│ ├── project-2_data-cleaning/
│ └── project-3_linear_or_logistic_regression/
│
├── step-02_neural-networks/
│ ├── project-1_perceptron_gates/
│ ├── project-2_mnist-classifier/
│ └── project-3_cifar10_feedforward_or_cnn/
│
├── step-03_llms-and-rag/
│ ├── project-1_prompt-basics/
│ ├── project-2_vector-search_faiss_or_chroma/
│ └── project-3_rag-chatbot/
│
└── step-04_agentic-ai/
├── project-1_task-runner-agent/
├── project-2_multi-tool-agent/
└── project-3_bug-bounty-agent_poc/

### Step 1 — Foundations (NumPy, Pandas, scikit-learn)
- **P1:** Hello World ML – predict a simple numeric target (e.g., housing prices).
- **P2:** Data cleaning & EDA – nulls, outliers, feature scaling, visuals.
- **P3:** Regression/classification (Titanic or spam filter).

### Step 2 — Neural Networks (PyTorch/TensorFlow)
- **P1:** Perceptron on AND/OR (+ visualize decision boundary).
- **P2:** MNIST digit classifier (training loop, accuracy, confusion matrix).
- **P3:** CIFAR-10 FFN or small CNN (regularization & augmentation).

### Step 3 — LLMs & RAG (Hugging Face + vector DB)
- **P1:** Prompt basics (few-shot, thinking styles, eval examples).
- **P2:** Vector search with FAISS/Chroma (embed → index → retrieve).
- **P3:** RAG chatbot (retrieval + response; add citations & eval).

### Step 4 — Agentic AI (tool use + orchestration)
- **P1:** Task-runner agent (read docs → summarize → save notes).
- **P2:** Multi-tool agent (search → summarize → store → notify).
- **P3:** Bug bounty POC agent (permissioned scanning + report template).

---

## ✅ Progress Checklist

### Step 1 — Foundations
- [ ] **P1:** Hello World ML  
- [ ] **P2:** Data cleaning & EDA  
- [ ] **P3:** Regression/Classification  

### Step 2 — Neural Networks
- [ ] **P1:** Perceptron gates  
- [ ] **P2:** MNIST classifier  
- [ ] **P3:** CIFAR-10 model  

### Step 3 — LLMs & RAG
- [ ] **P1:** Prompt basics  
- [ ] **P2:** Vector search (FAISS/Chroma)  
- [ ] **P3:** RAG chatbot  

### Step 4 — Agentic AI
- [ ] **P1:** Task-runner agent  
- [ ] **P2:** Multi-tool agent  
- [ ] **P3:** Bug bounty POC agent  

> I’ll check items off as I complete them and link each project’s folder and write-up.

---

## 🧭 How to Navigate
Each project folder includes:
- `README.md` with **goal → dataset → steps → evaluation → what I learned**
- `notebooks/` or `src/` code
- `requirements.txt` (or `pyproject.toml`)
- `results/` (metrics, charts).  
  > Note: Large datasets and trained weights are ignored with `.gitignore`.

---

## 🛠️ Quickstart

```bash
# Clone
git clone https://github.com/<your-username>/learning-ai.git
cd learning-ai

# Create env (example)
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# Install per project
pip install -r step-01_basics/project-1_hello-world-ml/requirements.txt
