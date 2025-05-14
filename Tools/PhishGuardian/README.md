# 🔐 PhishGuardian v1.1 – AI-Based Phishing Detection Tool

**PhishGuardian** is a Flask-based AI tool designed to detect phishing emails and suspicious URLs using machine learning. It leverages Natural Language Processing (NLP) techniques and classification models to analyze and flag potentially harmful content, providing a modern, interactive web interface for real-time analysis.

---

## 👨‍💻 Authors

- **Aditya Gupta** – [adityaarav21@gmail.com](mailto:adityaarav21@gmail.com)  
- **Sagar Dalal** – [sagardalal2004@gmail.com](mailto:sagardalal2004@gmail.com)  
- **Markanday Joshi** – [Markanday03@gmail.com](mailto:Markanday03@gmail.com)  
> *SGT University, Gurugram*

---

## 🚀 Features

- Analyze **email content** for phishing indicators using TF-IDF + Logistic Regression
- Detect **suspicious URLs** using a Multinomial Naive Bayes classifier
- Modern responsive **dark-themed UI** with Bootstrap 5
- Tabbed sections for clean separation of Email and URL analysis
- Returns detailed results with classification labels and inline feedback

---

## 🧠 Tech Stack

- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript
- **Backend**: Python, Flask
- **ML Libraries**: Scikit-learn, Joblib
- **NLP Techniques**: TF-IDF Vectorization

---

## 🛠️ How It Works

### Email Detection:
- Clean and preprocess the email text
- Apply TF-IDF vectorization
- Use a trained Logistic Regression model to classify as `phishing` or `ham`

### URL Detection:
- Extract structural features from the URL (e.g., length, '@' count, domain)
- Classify using a Naive Bayes model

---

## 📂 Project Structure

PhishGuardian/
│
├── frontend.html # Web UI (HTML + JS)
├── app.py # Flask application
├── email_model.pkl # Trained email classifier
├── email_vectorizer.pkl # TF-IDF vectorizer for email
├── url_model.pkl # Trained URL classifier
├── requirements.txt # Python dependencies
└── README.md # This file

📈 Future Scope
Integrate email header and sender verification

Use deep learning models like LSTM/BERT for better NLP detection

Collect and classify real-world phishing samples dynamically

Add email attachment and metadata analysis
