# AI Reminder Buddy

A motivational, AI-powered productivity assistant that helps you manage your to-do list, sends you regular reminders, and keeps you inspired to complete tasks on time. Built with Python, OpenAI's GPT-4, and threading for real-time interactions.

---

##  Features

- ✅ **To-Do List Manager**  
  Add, view, mark, and remove tasks with deadlines. Get AI suggestions when tasks are overdue.

- 🔔 **Smart Reminders**  
  Set interval-based reminders for any task, each running in the background with motivational messages.

- ⏰ **Overdue Task Notifier**  
  Background thread that monitors overdue tasks and provides encouraging alerts via GPT-4.

- 💬 **AI Motivation**  
  Uses OpenAI to provide short, fun, and encouraging messages throughout your productivity flow.

---

## 📦 Setup Instructions

### 1. Clone the Repositoy

```bash
mkdir my-AI-Agent
cd my-AI-Agent

### 2. Install Dependencies

```bash
pip install alith python-telegram-bot python-dotenv web3

### 3. Configure API Key

OPENAI_API_KEY=sk-...your-openai-key...

### 4. Run the Python script and interact with the main menu:

python ai_reminder_buddy.py
