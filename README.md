<img width="2140" height="735" alt="image" src="https://github.com/user-attachments/assets/cd3a2902-1e06-49e1-9df1-88174fce843e" />

from pathlib import Path
import zipfile, shutil, os, textwrap

base = Path("/mnt/data")
readme_path = base / "Krishika_GitHub_Profile_README.md"
banner_candidates = [
    base / "a_wide_minimal_elegant_banner_style_graphic_with.png",
    base / "a_wide_cinematic_cyber_tech_themed_banner_hero_i.png",
    base / "h3xiee-github-banner.png",
]
banner_src = next((p for p in banner_candidates if p.exists()), None)

readme = r'''<div align="center">

<img src="assets/github-banner.png" alt="Krishika Chellappandian — H3xiee" width="100%">

# Krishika Chellappandian

### Biomedical Engineer • AI/ML • Healthcare AI • Data Science

**Building practical AI systems at the intersection of healthcare, intelligent automation, and cybersecurity.**

<p>
  <a href="https://h3xiee.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-0B1220?style=for-the-badge&logo=googlechrome&logoColor=8ED6FF"></a>
  <a href="https://www.linkedin.com/in/krishika-c"><img src="https://img.shields.io/badge/LinkedIn-0B1220?style=for-the-badge&logo=linkedin&logoColor=8ED6FF"></a>
  <a href="https://github.com/H3xiee"><img src="https://img.shields.io/badge/GitHub-0B1220?style=for-the-badge&logo=github&logoColor=8ED6FF"></a>
  <a href="mailto:krishikachellappandiyan@gmail.com"><img src="https://img.shields.io/badge/Email-0B1220?style=for-the-badge&logo=gmail&logoColor=8ED6FF"></a>
</p>

</div>

---

## 👩‍💻 About Me

I'm a **Biomedical Engineering graduate** with hands-on experience developing AI and machine learning solutions for healthcare, including **ECG signal processing, computer vision, biomedical data analysis, and full-stack AI applications**.

My current focus is expanding into **Generative AI, LLMs, Retrieval-Augmented Generation (RAG), autonomous agents, and cybersecurity AI**.

I enjoy taking an idea from **problem → architecture → implementation → testing → working system**.

🎯 **Currently seeking:** Entry-level opportunities in **AI/ML, Data Science, Healthcare AI, and related applied AI roles**.

---

## 🧠 What I Work With

### Artificial Intelligence & Machine Learning
`Python` `TensorFlow` `Keras` `Scikit-learn` `CNN` `VGG-19` `OpenCV`

### Generative AI & Intelligent Systems
`LLMs` `RAG` `Autonomous Agents` `AI Security` `MCP`

### Healthcare & Biomedical AI
`ECG Processing` `MIT-BIH` `WFDB` `Signal Processing` `Feature Extraction` `Computer Vision`

### Data & Development
`NumPy` `Pandas` `SQL` `MATLAB` `Streamlit` `Flask` `SQLite` `Git` `GitHub` `Power BI`

---

## 🚀 Featured Projects

### 🏋️ AI-Based Exercise Posture Correction System

**Python · TensorFlow · Keras · CNN · VGG-19 · OpenCV · Streamlit · Flask · SQLite**

A full-stack deep learning application for exercise posture classification.

- Classifies exercise posture across **six classes**
- Developed **CNN and VGG-19** models
- Implemented frame extraction and whole-video prediction
- Integrated SQLite authentication
- Built an interactive Streamlit interface

🔗 **[View Project →](https://github.com/H3xiee/Fitness-Posture-Correction)**

---

### ❤️ ECG Arrhythmia Signal Processing Pipeline

**Python · WFDB · SciPy · Scikit-learn · NumPy**

An end-to-end ECG preprocessing pipeline built using the **MIT-BIH Arrhythmia Database**.

- ECG preprocessing and dataset preparation
- Butterworth filtering
- R-peak segmentation
- Feature preparation for **1D CNN** models

🔗 **[View Project →](https://github.com/H3xiee/ECG-Prediction)**

---

### 🕷️ Web Crawler — Cybersecurity Reconnaissance Pipeline

**Python · Asyncio · BeautifulSoup · JSON**

An intelligence-driven web crawler designed for structured cybersecurity reconnaissance.

- Endpoint extraction
- JavaScript analysis
- Authentication detection
- Attack-surface mapping
- Graph-based visualization
- Structured JSON outputs designed for downstream AI workflows

🔗 **[View Project →](https://github.com/H3xiee/crawler)**

---

### 🤖 Oryn — Autonomous AI Software Engineering System

**Generative AI · LLMs · RAG · Autonomous Agents**

An autonomous AI software engineering system designed to work through software tasks rather than simply generate isolated responses.

- Uses a trusted knowledge base to answer questions
- Takes a goal and develops an execution plan
- Writes and edits real code
- Runs tests
- Diagnoses failures
- Iterates on fixes
- Verifies that the result actually works before marking the task complete

🔒 **Repository: Private**

---

## 💼 Experience

**Generative AI Intern — Cyart Tech LLP**
- Worked with Generative AI, RAG, LLMs, cybersecurity AI workflows, web crawling, and Model Context Protocol (MCP).

**Bioinformatics Intern — Crescent Innovation & Incubation Council**
- Training and practical exposure in bioinformatics and biomedical data analysis.

**Power BI Intern — PwC**
- Created dashboards and data visualizations using Power BI.

**Web Development Intern — Octanet / Camplin**
- Built responsive web applications using HTML, CSS, and JavaScript.

---

## 🎓 Education

**B.Tech — Biomedical Engineering**  
PSNA College of Engineering and Technology, Dindigul  
**Graduated:** 2025 · **CGPA:** 7.6 / 10

---

## 📜 Certifications

- **PG Diploma in AI/ML in Healthcare** — Clinilaunch Research Institute
- **How to Build a Chatbot Using Python** — Great Learning

---

## 🔭 What I'm Exploring Now

```text
Generative AI
     ↓
LLMs + RAG
     ↓
Autonomous Agents
     ↓
Tool Use + Execution
     ↓
Verification + Feedback
     ↓
Reliable AI Systems
```

I'm particularly interested in how AI can move beyond **answer generation** toward systems that can **reason over relevant context, plan work, execute actions, test outcomes, recover from failures, and verify results**.

---

## 📊 My Technical Interests

| Area | Focus |
|---|---|
| 🤖 AI/ML | Deep Learning, CNNs, Computer Vision |
| 🧠 Generative AI | LLMs, RAG, AI Agents |
| 🔐 Cybersecurity AI | Reconnaissance, Security Workflows, AI-assisted Analysis |
| 🫀 Healthcare AI | ECG, Biomedical Signals, Computer Vision |
| 📈 Data Science | Python, SQL, Pandas, Power BI |
| 🧬 Bioinformatics | Biomedical Data & Computational Biology |

---

## 🌱 How I Build

**Learn → Build → Test → Break → Understand → Improve**

I prefer practical engineering over simply collecting technologies.  
Every project is an opportunity to understand **why a system works, where it fails, and how to make it better**.

---

## 📫 Let's Connect

I'm interested in connecting with **AI/ML engineers, data scientists, healthcare AI teams, researchers, startups, and teams building real-world intelligent systems**.

- 🌐 **Portfolio:** https://h3xiee.github.io/portfolio/
- 💼 **LinkedIn:** https://www.linkedin.com/in/krishika-c
- 🐙 **GitHub:** https://github.com/H3xiee
- 📧 **Email:** krishikachellappandiyan@gmail.com

<div align="center">

### *Explore. Learn. Build. Grow.*

**Thanks for visiting my profile!**

