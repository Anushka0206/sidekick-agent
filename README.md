# 🤖 Sidekick: Personal AI Co-Worker

## 📝 What is Sidekick?
Sidekick is not just a chatbot; it is an **autonomous agent** designed to handle complex tasks from start to finish. You give it a **Goal** and **Success Criteria**, and it works independently—browsing the web, writing files, and running code—until the job is done right.

### How it works:
1. **The Worker:** Searches the internet, reads Wikipedia, runs Python scripts, and manages local files.
2. **The Evaluator:** A "manager" AI that reviews the Worker's output. If the result doesn't meet your specific criteria, the Evaluator sends it back with feedback to try again.
3. **The Loop:** This cycle continues automatically until the task is perfect or it needs to ask you a question.

## ✨ Key Features
* **Web Research:** Uses Playwright and Google Serper to find real-time info.
* **Code Execution:** Can write and run Python code to solve math or data problems.
* **File Management:** Automatically creates and edits files in a local sandbox.
* **Phone Alerts:** Sends you a push notification via Pushover when the task is done.

## 🛠️ Tech Stack
* **Framework:** LangGraph (for the logic loops).
* **UI:** Gradio (for the web interface).
* **Model:** OpenAI GPT-4o-mini.

## 🚀 Installation & Setup
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Anushka0206/sidekick-agent.git](https://github.com/Anushka0206/sidekick-agent.git)
   cd sidekick-agent

2. **Install dependencies:**
   pip install -r requirements.txt
   playwright install chromium

3. **Setup**
   Add your OPENAI_API_KEY and SERPER_API_KEY.

4. **Run**
   python app.py
   
