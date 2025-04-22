# 🛡️ Cowrie Honeypot Lab (Beginner Friendly)

This is a personal cybersecurity project using the [Cowrie SSH honeypot](https://github.com/cowrie/cowrie). It includes a custom Python log parser that analyzes login attempts to identify attacker behavior.

## 🔍 Features

- Logs failed and successful SSH login attempts
- Shows most common usernames and attacker IPs
- Beginner-friendly script, well-commented
- Great for learning incident analysis and attacker fingerprinting

## 📂 Files

- `parse_logs.py`: Python script that parses `cowrie.json` logs
- Cowrie logs are expected in `var/log/cowrie/cowrie.json`

## 🚀 Usage

```bash
python3 parse_logs.py

Make sure Cowrie is running and logging before using the script.
This project is part of my learning journey into cybersecurity, Python, and threat analysis. Follow for updates!

💡 Future Ideas
Integrate with ELK for live dashboards

Add color output to parser

Auto-block attackers using fail2ban
