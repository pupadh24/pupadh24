# Hi, I'm Pratham

I'm a CS student at the University of Cincinnati (Honors Program) who enjoys building practical systems that solve problems I actually face in daily life.

Most of my projects start from personal frustration: something that feels inefficient or broken, and I want to understand it deeply enough to build a proper solution. I’m really interested in backend engineering, security, and applied AI

Currently looking for **Software/CS/IT Co-op roles for Fall 2026.**

---

## What I'm Working On

### 🧠 AwareYourself
This is a local-first anti-doomscrolling system designed to break mindless social media habits.

I'm working on this because I was tired of losing hours of my day to social media without realizing it. Deleting apps never worked, and screen time limits were easy to bypass. The real issue wasn’t access, it was the *habit* itself.

AwareYourself intercepts app launches, forces a short pause to break the dopamine loop, and asks me to state my intent before continuing. Instead of blocking usage, it builds awareness. Over time, it logs this data so I can correlate digital habits with physical health signals (taken straight from my Apple Watch) like sleep, heart rate, and energy levels to better understand how scrolling affects my body and focus. This is 100% local and no data ever leaves my device or iCloud.

Focus: behavioral design, local-first architecture, privacy, system-level data pipelines.
Repo: https://github.com/pupadh24/AwareYourself

---

### 🔐 VaultGuard Finance AI
This is a privacy-first financial analysis assistant using local LLMs and RAG.

For me, this started as a reaction to how people casually send their sensitive financial data uploaded into cloud AI tools. I wanted to explore whether it was possible to build a system that delivers useful insights *without* compromising privacy.

VaultGuard uses a dual-mode architecture: a fully local mode for private inference and a high-performance API-based demo mode. I built a PII-redaction pipeline to sanitize transaction data before embedding generation, and working on a RAG pipeline using vector search for fast, secure querying.

Tech: Python, Llama 3, Pandas, ChromaDB  
Repo: https://github.com/pupadh24/VaultGuard-Finance-AI  
Live Demo: https://vaultguard-finance-ai-pupadh24.streamlit.app  

---

### ☁️ CloudSecret
This is an end-to-end encrypted, self-destructing secret sharing service.

This project came from seeing people casually send passwords over insecure channels (plain text messages). I wanted to design a system where sensitive data simply *cannot exist* longer than necessary.

CloudSecret encrypts data using AES-256, allows only one-time secure access, and permanently deletes records immediately after viewing using database triggers. The focus is on encryption workflows, backend security, and data lifecycle control.

Tech: C#, ASP.NET Core, PostgreSQL  
Repo: https://github.com/pupadh24/CloudSecret  

## Finished Projects

### 🏥 Hospital Management System
This is a full-stack medical records and appointment management platform.

This was my first large-scale full-stack project. I wanted to understand how real systems handle authentication, data integrity, and production deployment. I had a local only version before but now I've migrated this into a cloud setup. I update this repo every now and then trying to migrate features from my local version to the live cloud demo.


Tech: Flask, MySQL, TiDB Cloud  
Repo: https://github.com/pupadh24/Hospital-Management-Syetem  
Live: https://hospital-management-system-0r2y.onrender.com/login  

---

## Tech Stack

Languages: Python, C/C++, C#, SQL, JavaScript, HTML, CSS  
Frameworks & Tools: Flask, Git, Docker, VS Code, Visual Studio  
Databases: PostgreSQL, MySQL, TiDB Cloud, ChromaDB  
Systems: Linux, macOS, Windows  

---

## Experience

**Intern: ePROMIS ERP Solutions**

Working on a high-scale SaaS ERP platform serving 150+ enterprise clients

---

## I'd Love to Connect

Email: pupadh24@gmail.com  
LinkedIn: https://linkedin.com/in/pupadh24  

