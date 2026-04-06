#  LogSentrix – Windows Log Analyzer

LogSentrix is a Python-based tool designed to analyze Windows Event Logs in real-time and detect suspicious activities such as failed logins, unusual behavior, and potential security threats.

## Features
- Read live Windows Event Logs
- Detect login attempts (success & failure)
- Convert logs into structured JSON
- Risk analysis engine (planned)
- Modular architecture for scalability

## System components 
- Python
- pywin32 (win32evtlog)
- JSON

## Project Status
🚧 Work in Progress – Core log reading implemented, advanced analysis coming soon.

## 📂 Planned Modules
- `log_reader.py` → Reads Windows logs
- `translator.py` → Converts raw logs to structured format
- `risk_engine.py` → Detects suspicious patterns

## 📊 Future Goals
- Real-time monitoring dashboard
- AI-based anomaly detection
- Export reports (PDF/CSV)

## ⚠️ Note
This tool is for educational and ethical cybersecurity purposes only.

---

## 👨‍💻 Author
Yogesh Mondal
