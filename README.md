# Study-Planner-AI-chatbot

# 📚 Study Bot – AI Study Planner & Assistant

Study Bot is an AI-powered study planner designed to help college students manage their study time effectively, plan subjects smartly, and clear academic doubts using a single assistant.

Unlike basic planners, Study Bot understands user intent and responds accordingly — whether it’s creating a study plan, solving calculations, or answering subject-related questions.

---

## 🚀 Features

- 🧠 **AI Study Planner**
  - Generates structured study schedules based on available time
  - Splits time across subjects like DBMS, OS, CN, etc.
  - Helps manage daily and weekly study routines

- ⏱️ **Time Management Assistant**
  - Handles prompts related to time splitting, scheduling, and workload balancing
  - Compares available time with required study hours

- 🧮 **Calculator Agent**
  - Performs mathematical calculations instantly
  - Useful during problem-solving and quick checks

- 💬 **Q&A Chatbot**
  - Answers academic and personal study-related doubts
  - Acts as a virtual study companion

- 🤖 **Agent-Based Architecture**
  - Different agents handle different tasks (planner, calculator, Q&A)
  - Improves clarity, performance, and scalability

---

## 🛠️ Tech Stack

- **Python**
- **Transformers (Hugging Face)**
- **FLAN-T5 / LLM-based text generation**
- **Regex & Intent Detection**
- **CLI-based interaction (can be extended to web UI)**

---

## 📂 Project Structure

study-bot/
│
├── agents/
│ ├── study_planner.py
│ ├── calculator_agent.py
│ └── qa_agent.py
│
├── main.py
├── requirements.txt
└── README.md


---

## ▶️ How to Run

1. Open in Google Colab and run the code


## Modules Used: 

1. Torch Transformer by Hugging Face 🤗

## 🧪 Example Prompts

Create a 4 hour study plan for DBMS and OS

Split my study time effectively

What is normalization in DBMS?

Calculate 45 * 12
