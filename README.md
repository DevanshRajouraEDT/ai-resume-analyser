# AI Resume Analyser

###THIS IS A VIBECODED PROJECT, WITH HELP OF GPT AND CLAUDE
A Python tool that reads your resume as a PDF and uses AI to give you detailed, honest feedback on it — what's good, what's missing, and exactly how to improve it.

---

## What it does

You give it your resume PDF, it reads the text, sends it to an AI, and prints back a full breakdown covering:

- Overall score out of 10
- Strengths
- Things to improve
- Missing sections
- Formatting and readability
- Keywords (including ATS keywords)
- Top 3 things to fix right now

---

## Tech used

| Tool | Purpose |
|------|---------|
| Python | Core language |
| pypdf | Reading and extracting text from PDF files |
| Groq API | Running the LLaMA 3 AI model (free) |

---

## Setup

**1. Clone the repo**
```bash
git clone https://github.com/DevanshRajouraEDT/ai-resume-analyser.git
cd ai-resume-analyser
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Get a free Groq API key**
- Go to https://console.groq.com
- Sign up and create an API key (free, no billing needed)

**4. Run it**
```bash
python resume_analyser.py
```

The program will ask for your resume path and API key, then print the full analysis.

---

## Example output

```
[*] Found your resume: my_resume.pdf
[*] Pages found: 1
[*] Successfully read 3788 characters of text.

[*] Sending your resume to the AI...

============================================================
           HERE'S YOUR RESUME FEEDBACK
============================================================

1. OVERALL SCORE: 7/10
   ...

2. STRENGTHS
   ...
```

---

## Project structure

```
ai-resume-analyser/
├── resume_analyser.py    # main script
├── requirements.txt      # dependencies
└── README.md
```

---

## Author

Devansh Rajoura
