# 📚 Bhasha – Early Literacy Monitoring System

### ✨ Early Literacy Monitoring Through Handwriting Analysis and Reading–Writing Skill Enhancement in Sinhala and Tamil Languages

Bhasha is a web-based educational platform designed to support early literacy development among children learning **Sinhala and Tamil**. The system combines handwriting analysis, handwritten text recognition, spelling and grammar checking, and reading fluency profiling to help monitor children's literacy skills and provide meaningful learning feedback.

🎯 **Target Group:** Children in Grades 3–5  
🌍 **Language Support:** Sinhala and Tamil  
🎓 **Project:** Final-Year Research Project – R26-DS-009  
🏛️ **Institution:** Sri Lanka Institute of Information Technology (SLIIT)

---

## 🌟 Key Features

### ✍️ 1. Handwriting Quality Analysis
Evaluates children's handwriting samples to assess handwriting quality and support the development of writing skills.

- 📝 Analyzes handwritten Sinhala and Tamil text.
- 🖼️ Processes handwriting images to improve analysis.
- 📊 Identifies handwriting quality characteristics.
- 💡 Provides feedback to support handwriting improvement.
- 👩‍🏫 Supports teachers in monitoring children's writing development.

### 🔤 2. Handwritten Text Recognition and Language Correction
Recognizes handwritten Sinhala and Tamil text and helps identify language-related errors.

- 📷 Processes images of children's exercise-book pages.
- 🧹 Applies image preprocessing techniques to improve text recognition.
- 🔍 Uses TrOCR-based handwriting recognition.
- ✅ Identifies potential spelling errors.
- 📝 Performs grammar checking.
- 💬 Provides child-friendly explanations and corrective feedback.

### 🎙️ 3. Reading Fluency Profiling
Analyzes children's oral reading recordings to assess reading performance and identify areas requiring improvement.

- 🎧 Processes oral reading recordings using Whisper-based speech recognition.
- 📖 Evaluates reading accuracy and fluency.
- ⏱️ Analyzes hesitation and sentence-length differences.
- 🤖 Uses K-means clustering to identify reading-behavior patterns.
- 🌳 Uses a Random Forest classifier to predict reading proficiency profiles.
- 📈 Categorizes learners into three proficiency levels:
  - 🟢 Fluent
  - 🟡 Moderate
  - 🔴 Struggling

### 📖 4. Reading Error Detection
Supports the identification of errors in children's oral reading to help teachers understand reading difficulties and provide appropriate guidance.

- 🎤 Analyzes recorded reading samples.
- 🔎 Supports the identification of reading errors.
- 📊 Helps monitor reading performance.
- 💡 Provides information that can support targeted reading practice.

---

## 🛠️ Technology Stack

### 💻 Frontend
- ⚛️ React
- 🟨 JavaScript
- ⚡ Vite
- 🎨 CSS
- 🧭 React Router

### ⚙️ Backend
- 🐍 Python
- 🚀 FastAPI
- 🔗 REST APIs

### 🧠 Artificial Intelligence and Machine Learning
- 🤗 Hugging Face Transformers
- ✍️ TrOCR
- 🎙️ Whisper
- 🤖 Scikit-learn
- 🌳 Random Forest
- 📊 K-means Clustering
- 🧠 PyTorch

### 🖼️ Image and Audio Processing
- 👁️ OpenCV
- 🔢 NumPy
- 🖼️ Pillow
- 🎵 Librosa
- 🔊 SoundFile
- 🎧 Pydub

### 🔐 Authentication and Data Services
- 🔑 Google Authentication
- 🔥 Firebase
- ☁️ Google Cloud Firestore

---

## 🏗️ System Architecture

The platform integrates multiple literacy assessment components through a web-based interface and a Python backend.

```text
                 📚 Bhasha Web Application
                           │
             ┌─────────────┴─────────────┐
             │                           │
      ✍️ Writing Assessment       🎙️ Reading Assessment
             │                           │
      ┌──────┴──────┐             ┌──────┴──────┐
      │             │             │             │
  🖼️ Handwriting  🔤 Text       📖 Reading    🔎 Reading
     Quality     Recognition     Fluency       Errors
      │             │             │             │
      └──────┬──────┘             └──────┬──────┘
             │                           │
             └─────────────┬─────────────┘
                           │
                 📊 Results and Feedback
```

---

## 🎯 Project Objectives

- ✍️ Support the assessment and improvement of children's handwriting skills.
- 🔤 Recognize handwritten Sinhala and Tamil text and identify potential spelling and grammar errors.
- 🎙️ Assess children's oral reading performance using speech recognition and machine learning.
- 📖 Identify reading errors and areas requiring additional practice.
- 📊 Support literacy progress monitoring through meaningful assessment results and feedback.
- 🌱 Encourage the development of early reading and writing skills through technology-assisted learning.

---

## 👥 Intended Users

- 🧒 **Students:** Receive feedback to help improve reading and writing skills.
- 👩‍🏫 **Teachers:** Monitor literacy performance and identify areas requiring additional support.
- 🏫 **Educational Institutions:** Explore technology-assisted approaches to early literacy assessment.

---

## 🌱 Project Impact

Bhasha aims to support early literacy development by combining handwriting analysis, language processing, speech recognition, and machine learning in a single educational platform.

By focusing on **Sinhala and Tamil**, the project addresses the need for technology-assisted literacy assessment in local-language learning environments. The platform is designed to help teachers identify learning difficulties and provide more focused support for children's reading and writing development.

---

## 🎓 Academic Project

**Project Group:** R26-DS-009  
**Institution:** Sri Lanka Institute of Information Technology (SLIIT)  
**Research Area:** Early Literacy Assessment, Handwriting Recognition, Natural Language Processing, Speech Recognition, and Machine Learning

---

### 💙 Building better literacy support through technology.

*Bhasha — Supporting every child's reading and writing journey.* 📚✨
