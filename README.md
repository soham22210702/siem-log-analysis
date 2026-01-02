# SIEM Log Analysis – Brute Force Detection

## Project Overview
This project demonstrates basic SIEM concepts by analyzing Linux authentication logs to detect suspicious login attempts and potential brute-force attacks.

## Objectives
- Analyze authentication logs
- Identify failed login attempts
- Detect suspicious IP addresses
- Simulate SOC-level incident detection

## Tools & Technologies
- Linux
- Python
- SIEM concepts
- Log analysis

## How It Works
The Python script scans authentication logs and counts failed login attempts per IP address. IPs exceeding a defined threshold are flagged as suspicious.

## Outcome
- Detected multiple failed login attempts
- Identified possible brute-force activity
- Gained hands-on experience in SOC workflows

## Future Enhancements
- Add alert thresholds
- Integrate visualization
- Support real-time logs
