# 📊 Simple Log Analysis Demo

This is a lightweight Python script that performs basic log parsing and detects sudden spikes in error logs. It helps identify potential issues by scanning for too many `ERROR` level entries within a short time window.

---

## 📌 Features

- Parses a raw log file using regex
- Converts logs into a structured Pandas DataFrame
- Detects error spikes within 30-second intervals
- Flags anomaly if errors exceed a threshold
- Prints full log summary for inspection

---

## 🛠️ Requirements

- Python 3.7+
- `pandas`
- `scikit-learn`

Install dependencies:
```bash
pip3 install pandas
```

# Expected Log Format 
YYYY-MM-DD HH:MM:SS LEVEL Message content
2025-06-30 14:01:00 INFO Application started
2025-06-30 14:01:10 ERROR Failed to connect to DB

# Run
python3 simple_log_analysis.py
python3 aiops_log_analysis.py

