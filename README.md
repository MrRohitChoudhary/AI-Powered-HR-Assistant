<p align="center">
  <img src="https://img.shields.io/badge/Project-AI%20Powered%20HR%20Assistant-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Language-Python-green?style=flat-square">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square">
  <img src="https://img.shields.io/github/last-commit/<your-username>/AI-Powered-HR-Assistant?style=flat-square">
  <img src="https://img.shields.io/github/stars/<your-username>/AI-Powered-HR-Assistant?style=flat-square">
</p>

🚀 AI-Powered HR Assistant
Automating Workforce Management with AI Agents

📌 Overview

AI-Powered HR Assistant is a multi-agent HR automation system designed to streamline workforce operations for contracting and field-based companies like Shiv Rudra Electrotech.

It enables HR staff to interact using simple natural-language commands such as:

“Mark Rajesh present today”
“What is Suresh’s pending salary?”
“Add worker 5 Anil 140”
“Remove worker Suresh”

The agent reads and updates worker records automatically using a connected database (Google Sheets) and provides instant feedback.

This project was developed as part of the
📍 Google x Kaggle — AI Agents Intensive Capstone Project (2025)
🏅 Eligible for Certificate & Kaggle Badge

🔗 Kaggle Submission:
https://www.kaggle.com/competitions/agents-intensive-capstone-project/writeups/new-writeup-1763401566806

🧠 Key Features
Feature	Description
Multi-Agent System	HR Manager Agent + Spreadsheet Agent
Natural Language Processing	HR operations through conversational queries
Attendance Management	Mark IN/OUT and record absence
Salary Calculation	Handles pending wages + overtime
Dynamic Worker Records	Add or remove workers anytime
Observability + Logging	Full trace history of agent actions
Cloud API Ready	Google Sheets API authentication implemented
🏗 Architecture

✔ Custom agent architecture inspired by LangChain agent design patterns
✔ A2A (Agent-to-Agent) communication
✔ Memory storage for context retention
✔ Tool routing for HR operations

📌 Architecture Diagram
→ assets/architecture.png

## 🧩 How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/AI-Powered-HR-Assistant.git
cd AI-Powered-HR-Assistant
### Install Requirements
pip install -r requirements.txt
###3️⃣ Run Jupyter Notebook
jupyter notebook notebook/ai_hr_agent_notebook.ipynb

🛠️ Tech Stack
Category	Tools
Language	Python
AI Agent Design	Custom NLU + rule-based NLP
Data Storage	Google Sheets API
Observability	Custom trace logger
Deployment Target	Vertex AI Agent Engine (future)
Notebook Platform	Kaggle
📸 Results (Screenshots)

Add your screenshots inside this folder:
assets/screenshots/

Example placeholders:

Feature	Screenshot
Attendance Marking	✓ attendance.png
Salary Query	✓ salary.png
A2A Logs	✓ logs.png
📦 Project Structure
AI-Powered-HR-Assistant/
│
├── notebook/
│   └── ai_hr_agent_notebook.ipynb
│
├── src/
│   ├── hr_manager_agent.py
│   ├── spreadsheet_agent.py
│   └── utils.py
│
├── assets/
│   ├── architecture.png
│   └── screenshots/
│
├── .gitignore
└── README.md


🚀 Future Deployment Plan
Phase	Feature	Target
1	Full Google Sheets live updates	Cloud API connected
2	UI Chatbot for Manager	Streamlit / Gradio
3	Worker Self-Entry Attendance	Mobile Hybrid App
4	Secure Secrets Management	GCP Secret Manager
5	Full Cloud Deployment	Vertex AI Agent Engine
6	Smart Payroll Generation	PDF & WhatsApp delivery
🧪 Sample Commands
Mark Rajesh present today
Add 2 overtime for Vijay
What is Suresh pending salary?
Add worker 4 Mukesh 120
Remove worker Vijay

📍 Author

👤 Rohit Choudhary
B.Tech — IT Engineering
AI | Automation | Full-Stack Learner
📍 Pune, India
💼 Open to collaborations and internships
📫 Connect: linkedin.com/in/your-profile-here

⚖ License

MIT License — feel free to use & contribute!

🎖 Status

✔ Google x Kaggle Agents Intensive Capstone Project Submitted
✔ Awaiting Badge + Official Certificate (Dec 2025)

🌟 Show Your Support

If you find this project useful:

⭐ Star this repository
🍴 Fork it
💬 Share feedback or ideas



