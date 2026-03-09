# 🤖 Sidekick: Personal AI Co-Worker

Sidekick is an autonomous AI agent built with **LangGraph** and **Gradio**. Unlike standard chatbots, Sidekick uses a "Worker-Evaluator" architecture to browse the web, run Python code, manage files, and self-correct its work until it meets your specific success criteria.

## ✨ Key Features

* **Self-Evaluating Loops:** Uses an Evaluator node to check if the task meets your "Success Criteria" before finishing.
* **Web Browsing:** Integrated with Playwright for real-time web navigation and data retrieval.
* **Code Execution:** Built-in Python REPL for performing calculations or data processing.
* **Push Notifications:** Can send alerts to your phone via Pushover when tasks are complete.
* **Persistent Memory:** Uses `MemorySaver` to remember context across a single session.

## 🛠️ Tech Stack

* **Orchestration:** [LangGraph](https://github.com/langchain-ai/langgraph)
* **LLM:** OpenAI GPT-4o-mini
* **Interface:** Gradio
* **Tools:** Playwright, Wikipedia API, Serper (Google Search), Python REPL.

## 🚀 Getting Started

### 1. Prerequisites
* Python 3.10+
* An OpenAI API Key
* A [Serper.dev](https://serper.dev/) API Key (for web search)

### 2. Installation
Clone the repository and install dependencies:
```bash
git clone [https://github.com/YOUR_USERNAME/sidekick.git](https://github.com/YOUR_USERNAME/sidekick.git)
cd sidekick
pip install -r requirements.txt
playwright install chromium
