# AI_local_ollama
AI local with Ollama
# Local AI with Python + Ollama

This repository contains simple Python examples to interact with **local AI models** using the Ollama SDK.

##  Requirements

* Python 3.8+
* Ollama installed
* Models:

  ```bash
  ollama pull llama3.2
  ollama pull codellama
  ```
* Install SDK:

  ```bash
  pip install ollama
  ```

---

##  Scripts

### 1. chat.py

Basic prompt to a local model.
**Use case:** simple AI queries.

```bash
python chat.py
```

---

### 2. chat_context.py

Multi-turn conversation with context.
**Use case:** chatbots, assistants.

```bash
python chat_context.py
```

---

### 3. generate_code.py

Generates Python code using AI.
**Use case:** code generation and learning.

```bash
python generate_code.py
```

---

### 4. generate_text.py

Generates text using a local LLM.
**Use case:** content generation, summaries.

```bash
python generate_text.py
```

---

### 5. streams.py

Streams AI responses in real time.
**Use case:** live chat, streaming UIs.

```bash
python streams.py
```

---

### 6. tool_calling.py

Demonstrates tool/function calling with AI (e.g., math operations).
**Use case:** AI agents, automation, integrations.

```bash
python tool_calling.py
```

---

## Purpose

Demonstrates how to:

* Run LLMs locally (no API costs)
* Build AI-powered tools in Python
* Use chat, streaming, code generation, and tool calling

---

## Author

Antonio Godos
