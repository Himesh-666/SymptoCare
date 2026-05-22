# SymptoCare

AI-powered medical symptom analysis system that predicts possible diseases based on user symptoms and provides precautions and preventive suggestions.

---

# Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript

## Backend

* Python
* Flask

## Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Joblib

## Database

* SQLite

## Version Control

* Git & GitHub

---

# Project Structure

```bash
SymptoCare/
│
├── backend/
│   └── app/
│       ├── api/
│       ├── schemas/
│       ├── services/
│       └── main.py
│
├── frontend/
│
├── ml_service/
│   ├── dataset/
│   ├── inference/
│   ├── training/
│   └── saved_models/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Setup Instructions

## 1. Clone the Repository

```bash
git clone https://github.com/Himesh-666/SymptoCare.git
```

---

## 2. Move Into Project Folder

```bash
cd SymptoCare
```

---

## 3. Create Virtual Environment

### Mac/Linux

```bash
python3 -m venv venv
```

### Windows

```bash
python -m venv venv
```

---

## 4. Activate Virtual Environment

### Mac/Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

---

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Backend

Run the Flask server:

```bash
python backend/app/main.py
```

Backend will start at:

```bash
http://127.0.0.1:5000
```

---

# GitHub Collaboration Workflow

## Before Starting Work

Always pull latest changes first:

```bash
git pull origin main
```

---

## After Completing Work

### Add changes

```bash
git add .
```

### Commit changes

```bash
git commit -m "your message"
```

### Push changes

```bash
git push origin main
```

---

# Important Team Rule

Always follow:

```bash
PULL → WORK → COMMIT → PUSH
```

This prevents conflicts and keeps everyone's project updated.

---

# Notes

* Do NOT upload `venv/`
* Do NOT upload `.env`
* Do NOT push unnecessary large files
* Always pull latest code before starting work

---

# Future Features

* NLP symptom understanding
* AI chatbot assistant
* Voice symptom input
* Nearby hospital recommendations
* Disease severity detection
* Medical dashboard
