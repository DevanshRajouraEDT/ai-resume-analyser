# 🤖 AI Resume Analyser

A beginner-friendly Python project that uses **Google Gemini AI** to analyse a resume PDF and give detailed feedback.

---

## 📁 Project Structure

```
ai_resume_analyser/
│
├── resume_analyser.py     ← Main Python script (the brain)
├── requirements.txt       ← List of libraries to install
└── README.md              ← This file
```

---

## ⚙️ Setup Instructions

### 1. Make sure Python is installed
```bash
python --version
# Should show Python 3.8 or higher
```

### 2. Install the required libraries
```bash
pip install -r requirements.txt
```

### 3. Get a FREE Google Gemini API Key
- Go to: https://aistudio.google.com/app/apikey
- Sign in with your Google account
- Click "Create API Key"
- Copy the key

### 4. Run the program
```bash
python resume_analyser.py
```

---

## 🚀 How to Use

1. Run the script
2. Enter the full path to your resume PDF
3. Paste your Gemini API key (or set it as an environment variable)
4. Wait a few seconds for the AI to analyse
5. Read the feedback and optionally save it to a file

---

## 🧠 What the AI Analyses

- Overall score out of 10
- Strengths of the resume
- Weaknesses and areas to improve
- Missing sections (skills, summary, projects, etc.)
- Formatting and readability
- Keyword analysis
- Top 3 action tips

---

## 🔐 Pro Tip: Set API Key as Environment Variable

Instead of pasting the key every time, you can set it once:

**Windows:**
```cmd
set GEMINI_API_KEY=your_key_here
```

**Mac/Linux:**
```bash
export GEMINI_API_KEY=your_key_here
```

---

## 📚 Libraries Used

| Library | Purpose |
|---------|---------|
| `pypdf` | Read and extract text from PDF files |
| `google-generativeai` | Connect to Google Gemini AI |
| `os` | Work with files and environment variables (built-in) |
| `sys` | Exit the program cleanly on errors (built-in) |

---

## 💡 Ideas to Extend This Project

- Add a web interface using Flask
- Support multiple resume formats (DOCX, TXT)
- Compare resume to a job description
- Score resume against ATS (Applicant Tracking Systems)

---

*Built with Python for Scaler School of Technology Portfolio*
