# AI Security Scanner 🔍🤖

An AI-powered network port scanner built with Python and Groq AI.
Scans target hosts for open ports and uses AI to analyze threats,
assess risk levels, and generate remediation recommendations.

## Features
- Scans common or custom ports on any target host
- Color coded terminal output for quick analysis
- AI powered threat analysis using Groq (Llama 3.3)
- Generates detailed remediation recommendations
- Saves full report to scan_results.txt

## Setup
1. Clone this repo
2. Install dependencies:
   pip install groq python-dotenv
3. Create a .env file:
   GROQ_API_KEY=your-key-here
4. Run:
   python ai_scanner.py

## Technologies
- Python 3.11
- Groq AI (Llama 3.3 70B)
- Socket programming
- ANSI terminal colors

## Disclaimer
Only scan hosts you have permission to scan.
scanme.nmap.org is provided for legal practice scanning.
