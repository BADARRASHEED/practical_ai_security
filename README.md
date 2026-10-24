# Practical AI Security | Hands-On Implementations

**Exploring AI vulnerabilities, adversarial machine learning, defensive techniques, and security evaluation through practical Python implementations.**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter)
![AI Security](https://img.shields.io/badge/Focus-AI%20Security-darkgreen)
![Status](https://img.shields.io/badge/Project-Hands--On%20Learning-blueviolet)

## Overview

This repository documents my hands-on exploration of **Artificial Intelligence Security**, based on the practical coding exercises presented in *Practical AI Security: A Hands-On Guide to Attacking, Defending, and Securing Modern AI Systems* by **Harriet Farlow**, published by No Starch Press in 2026.

The project brings together Python implementations and Jupyter notebooks to explore how modern AI systems can be attacked, evaluated, and protected.

My objective is to move beyond theoretical knowledge by studying security vulnerabilities at the implementation level, experimenting with adversarial techniques, understanding their underlying mechanisms, and examining practical defensive approaches.

The repository serves as a technical learning resource covering the intersection of:

- Artificial Intelligence and Machine Learning
- Adversarial Machine Learning
- Large Language Model (LLM) Security
- AI Red Teaming and Threat Evaluation
- Defensive AI and Model Robustness
- Agentic AI and Retrieval-Augmented Generation (RAG) Security

## Technical Areas Covered

### 1. Adversarial Machine Learning

Exploring how carefully designed or manipulated inputs can influence machine learning predictions and compromise model reliability.

**Implementations include:**

- Projected Gradient Descent (PGD)
- Carlini & Wagner attacks
- Adversarial patches
- Model extraction
- Membership inference
- Data poisoning
- Backdoor attacks
- Side-channel attacks

These exercises provide practical insight into attack surfaces across the machine learning lifecycle.

### 2. Defensive AI and Model Robustness

Investigating techniques intended to improve model resilience and reduce exposure to adversarial manipulation.

**Implementations include:**

- Adversarial training
- Defensive distillation
- Randomized smoothing
- Certified defenses
- Ensemble methods
- Gradient obfuscation analysis
- Statistical detection

The focus is on understanding how different defenses operate, their assumptions, and their limitations.

### 3. LLM and Generative AI Security

Studying security weaknesses in language-model applications and exploring defensive controls for safer AI interactions.

**Topics include:**

- Prompt injection attacks
- Instruction-layer filtering
- Input validation
- Model behavior evaluation
- Security testing of LLM applications
- Retrieval-Augmented Generation (RAG)

This area emphasizes the importance of treating external data, retrieved content, and model-generated responses as potential security boundaries.

### 4. Agentic AI Security

Examining security challenges introduced by AI systems that can interact with tools, environments, and other agents.

**Practical areas include:**

- Agent security experiments
- Agent communication
- Reinforcement learning environments
- Agent behavior evaluation
- Tool interaction risks

These exercises support a deeper understanding of the security implications of increasingly autonomous AI systems.

### 5. AI Red Teaming, Safety, and Evaluation

Exploring approaches for systematically identifying weaknesses and evaluating the behavior of AI systems.

**Topics include:**

- AI red teaming
- Security evaluations
- Toxicity evaluation
- Model behavior analysis
- Supply-chain security
- Mechanistic interpretability

The objective is to connect vulnerability discovery with evaluation, mitigation, and continuous security improvement.

## Repository Contents

The repository contains Jupyter notebooks (`.ipynb`) and Python files (`.py`) covering practical AI security experiments.

| Category | Selected Implementations |
|---|---|
| Adversarial Attacks | `PGD.ipynb`, `CarliniWagner.ipynb`, `adversarial-patch.ipynb` |
| Model Security | `model-extraction.ipynb`, `membership-inference.ipynb`, `backdoor.ipynb` |
| Data Security | `data-poisoning.ipynb`, `supply-chain.ipynb` |
| Defensive Techniques | `adversarial-training.ipynb`, `defensive-distillation.ipynb`, `randomized-smoothing.ipynb` |
| LLM Security | `prompt-injection.ipynb`, `input-validation.ipynb`, `instruction-layer-filtering.ipynb` |
| Agent Security | `agent-hack.ipynb`, `agentcomms.ipynb`, `GridWorld.ipynb` |
| AI Evaluation | `security-eval.ipynb`, `toxicity-eval.ipynb`, `Red_team.ipynb` |
| AI Applications | `mini_rag.py`, `multi_modal_model.py`, `language_translation_model.py` |

Additional experiments cover statistical detection, ensemble methods, interpretability, embedding-space visualization, and model comparison.

## Technology Stack

The practical exercises use tools and concepts from the Python AI ecosystem.

**Core technologies:**

- Python
- Jupyter Notebook / Google Colab
- Machine Learning and Deep Learning
- Natural Language Processing
- Adversarial Machine Learning
- AI Security Evaluation

Individual experiments may require libraries such as NumPy, pandas, scikit-learn, PyTorch, TensorFlow, or Hugging Face Transformers, depending on their implementation.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/BADARRASHEED/practical_ai_security.git
cd practical_ai_security
```

### 2. Create a Python Virtual Environment

```bash
python -m venv .venv
```

Activate the environment.

**Windows:**

```bash
.venv\Scripts\activate
```

**Linux / macOS:**

```bash
source .venv/bin/activate
```

### 3. Install Jupyter

```bash
python -m pip install --upgrade pip
python -m pip install jupyterlab
```

Install additional dependencies according to the imports and requirements of the individual experiment.

### 4. Launch JupyterLab

```bash
jupyter lab
```

Select a notebook and execute its cells in the intended order.

Alternatively, open notebooks in Google Colab using their GitHub URLs.

**Note:** Dependencies, hardware requirements, and API credentials vary across experiments. Some Python files may require format conversion or adjustments before direct execution. The examples have not been presented as a fully automated or independently validated test suite.

## Learning Objectives

Through this repository, I aim to strengthen my practical understanding of:

1. How AI and machine learning models become vulnerable to adversarial manipulation.
2. How attacks such as data poisoning, prompt injection, and model extraction operate.
3. How defensive techniques can improve AI robustness and reliability.
4. How to evaluate AI systems for security weaknesses and unsafe behavior.
5. How security considerations extend to LLMs, RAG applications, and autonomous agents.
6. How to connect AI security research with real-world engineering and deployment practices.

## Responsible Security Research

All experiments in this repository are intended for **education, authorized security research, and defensive learning**.

Security testing should be conducted only on systems, environments, and models for which explicit authorization has been granted.

The code is not intended for unauthorized access, disruption, exploitation of third-party systems, or malicious activities.

Understanding attacks is an essential part of developing stronger and more resilient AI systems.

## Acknowledgments and Attribution

This project is inspired by and based on the practical exercises accompanying:

**Practical AI Security: A Hands-On Guide to Attacking, Defending, and Securing Modern AI Systems**

**Book Author:** Harriet Farlow  
**Publisher:** No Starch Press  
**Publication Year:** 2026

**Resources:**

- [Official Book Page](https://nostarch.com/practical-ai-security)
- [Original Companion Code Repository](https://github.com/harriethacks/aisecurityhandbook)

Full credit for the original educational examples and their underlying material belongs to Harriet Farlow and the respective rights holders.

This repository represents my personal hands-on learning, execution, organization, and exploration of those examples. It is an independent learning project and is not an official companion repository or an endorsement by the book's author or publisher.

Reuse and redistribution of original material remain subject to the applicable permissions and licensing terms.

## Author

**Badar Rasheed Butt**  
AI Engineer
