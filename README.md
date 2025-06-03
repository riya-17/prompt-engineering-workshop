# Prompt Engineering Workshop

Welcome to **Prompt Engineering Workshop**, a hands-on workshop where you'll learn to run and use prompts using [Ollama](https://ollama.com/).

## 🎯 Goals

By the end of this workshop, you will:

- Run and interact with language models locally using the `ollama` CLI
- Use Python (`chatbot.py`) to call Ollama’s API
- Will have good knowledge around prompt engineering which will make your interaction with LLMs easier

---

## 🧰 Prerequisites

Make sure you have the following installed **before** the workshop:

- Python 3.10+
- [Ollama](https://ollama.com/download) (with at least one model pulled locally, like `qwen3:0.6b`)
- Git
- A GitHub account

---

## 🚀 Getting Started

1. **Fork this repository** to your own GitHub account.
2. **Clone your fork** to your local machine:

   ```bash
   git clone https://github.com/YOUR_USERNAME/prompt-engineering-workshop.git
   cd prompt-engineering-workshop
   ```

3. **Install dependencies:**

   ```bash
   python3 -m venv .venv
   source ./venv/bin/activate
   pip install -r requirements.txt
   ```
---

## 🛠 Example Ollama CLI Commands

- Pull a model:

  ```bash
  ollama pull qwen3:0.6b
  ```
  or
  ```bash
  ollama pull gemma2:2b
  ```
  or
  ```bash
  ollama pull tinyllama:1.1b 
  ```

- Run a prompt:

  ```bash
  ollama run qwen3:0.6b "What is the capital of Peru?"
  ```

- Summarize a file:

  ```bash
  ollama run qwen3:0.6b "Summarize this file: $(cat README.md)"
  ```

---

## 💬 Help & Questions

If you get stuck:

- Check your local `ollama` service: [http://localhost:11434](http://localhost:11434)
- Ask your workshop host or teammates!
- Or open a GitHub Issue if it's repo-related.

---

Enjoy the chaos. Herd your llamas.  
