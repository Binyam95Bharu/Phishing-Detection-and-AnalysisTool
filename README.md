# Phishing-Detection-and-AnalysisTool


An advanced phishing detection system that analyzes email content and URLs to identify potential phishing attempts. This tool uses heuristic and signature-based methods to help prevent social engineering attacks.

---

## Features

- Analyzes email text for common phishing keywords and suspicious language.
- Scans URLs for suspicious patterns and verifies domains against a trusted whitelist.
- Provides a detailed, easy-to-understand report indicating phishing likelihood.
- Modern, responsive web interface for submitting emails and URLs and viewing results.
- Built with Python Flask backend and clean HTML/CSS/JavaScript frontend.

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- `pip` package manager

### Installation

1. Clone this repository or download the source files.

2. Create and activate a Python virtual environment:

   **Windows (PowerShell):**
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate.ps1
macOS/Linux:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
Install required Python packages:

bash
Copy
Edit
pip install flask tldextract
Running the Application
bash
Copy
Edit
python app.py
The Flask server will start on http://localhost:5000.

Usage
Open a browser and navigate to http://localhost:5000.

Paste email content or input a suspicious URL.

Click Analyze to see a detailed phishing analysis report.

The tool highlights suspicious keywords, URL patterns, and overall phishing risk.

Project Structure
php
Copy
Edit
phishing-detection-tool/
│
├── app.py            # Python Flask backend with phishing detection logic
├── static/
│   └── index.html    # Frontend interface for user input and results display
└── README.md         # This file
Limitations & Future Improvements
Current heuristics are basic; expanding to machine learning models can improve detection accuracy.

No user authentication or logging yet — suitable for local or internal use.

Domain whitelist is minimal — should be expanded or replaced with dynamic threat intelligence.

Can integrate with real email servers and APIs for real-time phishing detection.

License
MIT License

Author
BINYAM BAHRU
---

Would you like me to also prepare GitHub Actions workflows
