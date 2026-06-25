# 🎓 AI Lecture Assistant

An AI-powered lecture management and learning assistant built with LangChain, Gemini AI, and Streamlit. It helps students access lecture materials, generate notes, ask questions, summarize topics, and receive personalized study guidance.

## 🚀 Features

* 📚 Lecture Management — Store and organize lecture content
* 📝 Automatic Notes Generator — Create concise notes from lecture materials
* 🔍 Topic Search — Quickly find concepts from uploaded lectures
* 📄 Lecture Summarizer — Generate easy-to-understand summaries
* ❓ AI Question Answering — Ask questions about lecture topics
* 🎯 Personalized Learning Assistant — Get explanations and study recommendations
* 📊 Progress Tracking — Monitor learning progress and completed topics
* 💬 AI Tutor Chatbot — Interact naturally with Gemini AI for doubt clarification

## 🛠️ Tech Stack

| Technology       | Purpose                              |
| ---------------- | ------------------------------------ |
| Python           | Core language                        |
| Streamlit        | Web UI                               |
| LangChain        | AI Agent framework                   |
| Google Gemini AI | Language model                       |
| SQLite           | Database                             |
| FAISS / ChromaDB | Vector storage for lecture retrieval |

## 📁 Project Structure

ai_lecture_assistant/

├── ai_lecture.py ← Backend + AI Agent

├── app.py ← Streamlit UI

├── lectures.db ← Database

├── requirements.txt ← Dependencies

└── README.md ← Project documentation

## ⚙️ Installation

### Step 1 — Clone the Repository

```bash
git clone https://github.com/YourUsername/ai_lecture_assistant.git
cd ai_lecture_assistant
```

### Step 2 — Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3 — Run the Application

```bash
streamlit run app.py
```

### Step 4 — Add Gemini API Key

Enter your Gemini API key in the sidebar of the application.

Get your API key from:

https://aistudio.google.com

## 🌐 Live Demo

👉 Click here to open the app

## 📸 Screenshots

### Dashboard

* View available lectures
* Track learning progress
* See recent activity

### Lecture Assistant

* Upload lecture notes
* Generate summaries
* Ask questions from lecture content

### AI Tutor

* Interactive Q&A
* Topic explanations
* Study recommendations

## 🤖 AI Agent Tools

| Tool               | Description                            |
| ------------------ | -------------------------------------- |
| UploadLecture      | Upload lecture notes and documents     |
| ViewLectures       | Display available lecture materials    |
| SummarizeLecture   | Generate concise summaries             |
| SearchTopic        | Search concepts across lectures        |
| AskLectureAI       | Answer questions using lecture content |
| GenerateNotes      | Create structured notes                |
| RecommendStudyPlan | Suggest personalized study plans       |

## 💬 Example Queries

* "Summarize today's AI lecture"
* "Explain neural networks in simple terms"
* "Generate notes for Machine Learning Unit 2"
* "What topics are covered in Data Structures?"
* "Create a study plan for next week's exam"
* "Search all lectures for sorting algorithms"

## 📝 License

This project is for educational purposes.

## 👨‍💻 Author

Made with ❤️ using LangChain + Gemini AI + Streamlit
