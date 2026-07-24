# ThreatLens AI

ThreatLens AI is a browser-based security alert triage demo. Paste a raw alert and it returns a structured verdict, severity score, MITRE ATT&CK mapping, indicators of compromise, containment steps, and analyst reasoning.

## Demo

https://khushiatcode.github.io/threatlens-ai/

## Features

- Raw alert analysis
- Verdict: escalate, monitor, or dismiss
- Severity, priority, and time-to-act estimates
- MITRE ATT&CK tactic and technique mapping
- IOC extraction
- Suggested containment steps
- Preloaded attack scenarios

## Stack

- HTML, CSS, JavaScript
- Gemini 2.5 Flash
- MITRE ATT&CK
- GitHub Pages

## Run Locally

```bash
git clone https://github.com/khushiatcode/threatlens-ai.git
cd threatlens-ai
python3 -m http.server 8000
```

Open `http://localhost:8000`.

A Gemini API key is required. It is kept in browser memory for the active session and is not stored by the app.


## Author

Khushi Savaliya  
[LinkedIn](https://linkedin.com/in/khushi-savaliya) · [GitHub](https://github.com/khushiatcode)
