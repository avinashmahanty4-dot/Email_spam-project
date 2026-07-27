# 📧 Email Spam & Phishing Detector

A high-performance, real-time Email Spam and Phishing Detection Web Application built with JavaScript, HTML5, and modern CSS glassmorphism. AegisSpam AI utilizes a client-side **Naive Bayes + TF-IDF Machine Learning Classifier** to analyze email text, calculate threat risk scores, highlight suspicious signals, and verify security headers.

![App Screenshot](https://img.shields.io/badge/Status-Active-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JavaScript-orange)

---

## ✨ Features

- 🔍 **Live Email Analyzer**: Real-time spam & phishing classification with an animated SVG risk dial gauge.
- ⚡ **Explainable AI (XAI)**:
  - In-line text scanner highlighting threat keywords and rule triggers.
  - TF-IDF feature weight breakdown for top positive (Spam) and negative (Ham) word signals.
- 📊 **Risk Vector Diagnostics**: Visual metrics for Urgency Cues, Link & Domain Suspicion (detects IP URLs & untrusted TLDs), Financial Triggers, and Formatting Anomalies.
- ⚙️ **Custom Rule & Filter Engine**: Add, edit, or toggle custom keyword blacklists, whitelists, and weight settings. Adjust sensitivity between *Permissive*, *Balanced*, and *Strict*.
- 📈 **Model Benchmark Suite**: Test the classifier against benchmark email sets with a real-time **Confusion Matrix**, **Accuracy**, **Precision**, **Recall**, and **F1-Score** analytics.
- 🌐 **Security Header Inspector**: Inspect raw email headers for **SPF**, **DKIM**, and **DMARC** authentication compliance.

---

## 📁 Repository Structure

```
email_spam/
├── index.html         # Main Web Application layout & components
├── styles.css         # Modern glassmorphism CSS design system
├── README.md          # Project documentation
├── .gitignore         # Git ignore file
└── js/
    ├── dataset.js     # Benchmark email corpus & training data
    ├── classifier.js  # Naive Bayes ML & TF-IDF risk engine
    └── app.js         # UI controller, event listeners, & gauge rendering
```

---

## 🚀 How to Run Locally

### Option 1: Simple Local HTTP Server (Python)
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/email-spam-detector.git
cd email-spam-detector

# Run local HTTP server
python -m http.server 8080
```
Open **`http://localhost:8080`** in your web browser.

### Option 2: Node.js / npx
```bash
npx serve .
```

---

## 🛠️ Step-by-Step Instructions to Push to GitHub

If Git is installed on your computer, run the following commands in your terminal:

```bash
# 1. Initialize Git repository
git init

# 2. Add all project files
git add .

# 3. Commit files
git commit -m "Initial commit: Email Spam Detector Web Application"

# 4. Rename main branch
git branch -M main

# 5. Create a new repository on GitHub (e.g. email-spam-detector) and link remote:
git remote add origin https://github.com/YOUR_USERNAME/email-spam-detector.git

# 6. Push code to GitHub
git push -u origin main
```

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
