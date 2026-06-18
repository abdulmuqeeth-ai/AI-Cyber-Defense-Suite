# 🛡️ AI Cyber Defense Suite

A comprehensive cybersecurity platform that detects and analyzes common cyber threats using AI and rule-based techniques.

## 🎯 Features

### 1. 📧 Phishing Email Detector
- Analyzes email content for phishing indicators
- Detects urgent language, suspicious URLs, and brand spoofing
- Returns risk score and detailed reasons

### 2. 🌐 Suspicious URL Analyzer
- Checks URLs for security vulnerabilities
- Analyzes domain structure, HTTPS usage, and suspicious patterns
- Identifies potential phishing and malware links

### 3. 🔐 Login Attack Monitor
- Tracks login attempts in real-time
- Detects brute force attacks
- Automatically blocks suspicious IPs
- Stores data in SQLite database

### 4. 🦠 Malware Hash Checker
- Calculates MD5 and SHA256 hashes of uploaded files
- Compares against known malware database
- Identifies malicious files

### 5. 📊 SOC Dashboard
- Real-time analytics
- Threat distribution charts
- Activity monitoring

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Database**: SQLite
- **Libraries**: pandas, numpy, scikit-learn, plotly, hashlib

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/AI-Cyber-Defense-Suite.git

# Navigate to project
cd AI-Cyber-Defense-Suite

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
