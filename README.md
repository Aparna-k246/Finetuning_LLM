# 🔧📚 LLM Fine-tuning Projects (Gemma, Lamini)

This repository showcases practical examples of **fine-tuning Large Language Models (LLMs)** using both **Google Gemma** and **Lamini**. It covers notebook-based experiments and script-based pipelines, enabling you to adapt LLMs for domain-specific tasks like Q&A, classification, or summarization.

---

## 📁 Repository Structure

```
Finetuning_LLM/
├── Lamini_Finetuning/                    # Script-based fine-tuning using Lamini SDK
│   ├── finetune.py
│   └── requirements.txt
├── Gemma_Finetuning_notebook.ipynb      # Google Gemma finetuning via Colab/Notebook
└── README.md
```

---

## 🚀 Projects Overview

| Project | Description | Model |
|--------|-------------|--------|
| 🧠 **Gemma Fine-tuning Notebook** | End-to-end training loop with sample prompts | Google Gemma |
| 🧪 **Lamini Finetune Script** | Python-based finetuning using Lamini SDK | Lamini (Open Source) |

---

## 🧰 Tech Stack

- **Google Gemma** – Lightweight, open-source LLM
- **Lamini SDK** – Developer-friendly API for custom LLMs
- **HuggingFace Transformers**, **PEFT**, **LoRA**
- **Jupyter/Colab** for iterative workflows

---

## 🛠️ Setup Instructions

### 🔹 For Lamini
```bash
cd Lamini_Finetuning
pip install -r requirements.txt
python finetune.py
```

> 💡 Requires Lamini API key (obtain from [lamini.ai](https://lamini.ai))

### 🔹 For Gemma (Notebook)
- Open `Gemma_Finetuning_notebook.ipynb` in Jupyter or Colab
- Follow cells step-by-step to train, evaluate, and test
- GPU recommended


---

## 🔭 Future Enhancements

- Add custom dataset support via CSV/JSONL
- Add evaluation benchmarks: BLEU, ROUGE, Accuracy
- Integrate Weights & Biases for tracking

---

## 📫 Let’s Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)

---

## ⭐ If You Found This Useful

- ⭐ Star this repo  
- 🍴 Fork it and try your own fine-tuning  
- 🧠 Connect for LLM collaboration
