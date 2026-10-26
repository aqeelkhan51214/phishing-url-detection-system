# Email Spoof Detector

## Semester Project
This project was developed as a semester project by **M Aqeel Khan** for cybersecurity and network security learning.

The goal of this tool is to detect potential email spoofing attempts by analyzing email headers and identifying suspicious mismatches between sender information and domain details.

## Project Overview
This Python-based application analyzes email headers to detect spoofing attempts based on inconsistencies in the `From`, `Reply-To`, and `Return-Path` fields.

## Features
- Extracts and compares sender domains from email headers
- Flags suspicious domain mismatches and spoofing signs
- Reads raw email headers from a `.txt` file
- Works as a practical cybersecurity project for learning email security analysis
- Can be extended with DKIM, SPF, and DMARC validation in future updates

---

## How It Works
- Parses email headers using Python's built-in `email.parser`
- Extracts sender domains from `From`, `Reply-To`, and `Return-Path`
- Compares the domains to detect inconsistencies
- Displays alerts when email header information looks suspicious

---

## Project Files
- `email_spoof_detector.py` → Main logic for spoof detection
- `sample_email_header.txt` → Example email header used for testing
- `README.md` → Project documentation

---

## Run the Script

```bash
python email_spoof_detector.py
```

## Author
**M Aqeel Khan**

## Note
This project is designed as a learning and academic cybersecurity assignment to demonstrate email spoof detection using Python.
