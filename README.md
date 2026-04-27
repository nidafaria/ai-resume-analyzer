# 🚀 AI Resume Analyzer & Skill Gap Finder

A **full-stack AI-powered web application** that analyzes resumes, calculates an ATS-style match score, identifies skill gaps, and provides actionable career recommendations — all through a **modern, premium UI**.

Built with **Python (FastAPI/Flask)** backend and a **dynamic frontend**, this project focuses on **real-world hiring logic**, not black-box AI hype.

---

## 🧠 What This Project Does

* 📄 Upload a resume (PDF)
* 🎯 Select a target job role
* 🧩 Extract skills from resume
* 📊 Calculate match score (ATS-style)
* ❌ Identify missing skills
* 📈 Generate improvement suggestions
* 🛣 Provide a structured learning roadmap

---

## 🏗️ Project Structure

```
ai-resume-analyzer/
│
├── ai-resume-analyzer-backend/     # Backend (Python API)
├── ai_resume_analyzer_frontend/    # Frontend (UI + logic)
└── README.md                      # Main project documentation
```

---

## ⚙️ Tech Stack

### 🔙 Backend

* Python 3
* FastAPI / Flask
* pdfplumber (PDF parsing)
* Regex-based NLP
* Weighted scoring logic

### 🎨 Frontend

* HTML5
* CSS (Glassmorphism + animations)
* Tailwind CSS (CDN)
* Vanilla JavaScript
* Lucide Icons
* Google Fonts

---

## 🚀 Key Features

### 📄 Resume Analysis

* Extracts text from PDF resumes
* Handles noisy formatting
* Accurate skill detection using regex

---

### 🎯 Role-Based Matching

Supports:

* Frontend Developer
* Backend Developer
* Full Stack Developer
* Data Science
* DevOps

Each role has predefined required skills.

---

### 📊 Weighted ATS Scoring

* Critical skills → weight 3
* High priority → weight 2
* Medium → weight 1
* Produces realistic match percentages

---

### 🧩 Skill Gap Detection

* ✅ Matched skills
* ❌ Missing skills
* ➕ Extra skills

Grouped by importance level.

---

### 🧭 Smart Recommendations

* Immediate skills to learn
* Profile improvement suggestions
* Career guidance

---

### 🛣 Learning Roadmap

* Fundamentals
* Intermediate
* Advanced

---

### 🎨 Premium UI Experience

* Glassmorphism design
* Animated gradient background
* Drag-and-drop resume upload
* Smooth transitions & micro-interactions
* Fully responsive layout

---

## 🧠 How It Works (Pipeline)

1. Upload resume (PDF)
2. Extract text using `pdfplumber`
3. Detect skills using regex
4. Match against role requirements
5. Apply weighted scoring
6. Identify skill gaps
7. Generate recommendations + roadmap
8. Display results in UI

---

## 🔮 Future Improvements

* 📊 Skill radar charts
* 🤖 AI-based feedback (Gemini/OpenAI)
* 📄 Resume section weighting
* 🔐 User authentication
* 📱 PWA support

---

## 🧠 Why This Project Stands Out

* ✅ Real hiring logic (not fake AI buzzwords)
* ✅ Transparent & explainable scoring
* ✅ Clean modular architecture
* ✅ Full-stack implementation
* ✅ Ready for ML extension

---

## 📊 System Workflow

See detailed workflow: [WORKFLOW_VISUALIZATION.md](./WORKFLOW_VISUALIZATION.md)

---

## 👨‍💻 Authors

**Nida Faria**
**Shabuir Shahin**
**Mirudula S**
**Monisha U**


---

## ⭐ Show Your Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---