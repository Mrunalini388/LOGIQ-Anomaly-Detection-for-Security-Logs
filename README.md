
# LOGIQ  
**AI Anomaly Detection for Security Scan Logs**

LOGIQ is a Python tool that analyzes raw Nmap and Nikto scan logs to automatically detect suspicious or unusual entries using machine learning. It helps you quickly identify potential vulnerabilities in your security logs.

---

## 🚀 Features

- Processes raw scan logs from Nmap and Nikto  
- Extracts basic features like line length and security-related keywords  
- Uses Isolation Forest (unsupervised ML) to detect anomalies  
- Labels each log entry as **Normal** or **Anomaly**  
- Saves results to a file for easy review

---

## ✅ Prerequisites

- Python 3.7 or higher  
- Required packages: `numpy`, `scikit-learn`, `pyfiglet`

---

## ⚙️ Setup & Usage

 1. Clone the repository
```
git clone https://github.com/Mrunalini388/LOGIQ-Anomaly-Detection-for-Security-Logs
cd LOGIQ-Anomaly-Detection-for-Security-Logs
```
2. Create and activate a virtual environment
    macOS/Linux:
```
python -m venv venv
source venv/bin/activate
```
3. Install dependencies
```
pip install -r requirements.txt
```
4. Add your scan logs
Place the following files in the project root:
```
example_nmap.txt
example_nikto.txt
```
5. Run anomaly detection
```
python ai_log_analyzer.py
```



