 conda create -n lang9 python==3.11 -y 

1. conda activate lang9

2. pip install -r requirements.txt

3.  run you project 

 streamlit run app.py

# 🚀 AI Recruitment Agent – Resume Analyzer

An AI-powered Streamlit application that analyzes resumes, identifies strengths and weaknesses, generates personalized interview questions, and even rewrites resumes based on job roles or descriptions.

Built with:
- 🧠 **LangChain + Groq (LLaMA3)**
- 🤗 **HuggingFace Embeddings**
- 🎯 **FAISS for semantic similarity**
- 💬 **Streamlit for the user interface**

---

## ✨ Features

### 1️⃣ Resume Analysis
- Upload PDF or TXT resume
- Choose from predefined roles or upload a custom Job Description
- AI gives a score out of 100 and evaluates skill strengths and weaknesses
- Semantic matching using vector embeddings

### 2️⃣ Resume Q&A
- Ask natural language questions about the resume
- AI answers based on semantic document understanding

### 3️⃣ Interview Questions Generator
- Select difficulty (Easy / Medium / Hard)
- Choose types: Behavioral, Technical, Scenario-based, etc.
- AI creates personalized questions relevant to the resume and role

### 4️⃣ Resume Improvement
- Choose improvement areas like formatting, clarity, ATS optimization
- Get actionable bullet-point suggestions and before/after examples

### 5️⃣ AI-Improved Resume Generator
- Automatically rewrites the resume for a selected role or JD
- Highlights missing skills and improves language, layout, and quantification
- Outputs an enhanced version in plain text format

---

## 📁 Project Structure

├── app.py # Main Streamlit application
├── agents.py # ResumeAnalysisAgent class (LLM logic)
├── ui.py # Modular UI components (sidebar, tabs, layout)
├── requirements.txt # All Python dependencies
├── README.md # Project documentation



---

## ⚙️ How to Run

### 1. Clone the repository


git clone https://github.com/yourusername/ai-recruitment-agent.git
cd ai-recruitment-agent

### 2. Install dependencies and make env.

conda create -n resume-agent python=3.10
conda activate resume-agent
pip install -r requirements.txt

### 3. Launch the app

streamlit run app.py

