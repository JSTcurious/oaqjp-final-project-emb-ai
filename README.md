# Emotion Detection Web App (v0.0)

A lightweight Flask-based web application that uses **IBM Watson's NLP EmotionPredict API** to detect and classify emotions in text input. The app identifies five core emotions — **anger, disgust, fear, joy, and sadness** — and highlights the **dominant emotion**.

> ✅ Version 0 — Built as part of the IBM Generative AI Engineering Professional Certificate program.

---

## 🧠 What This App Does

- Accepts text input via a simple web interface
- Sends the input to IBM Watson's `EmotionPredict` NLP API
- Parses and displays emotion scores for:
  - Anger
  - Disgust
  - Fear
  - Joy
  - Sadness
- Identifies and highlights the **dominant emotion**
- Includes **input validation** and **error handling** for blank text
- Achieves **10/10 PyLint score** for clean, compliant Python code

---

## 🚀 Live Demo (Local)

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai

