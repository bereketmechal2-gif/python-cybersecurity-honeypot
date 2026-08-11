# Python Cybersecurity Honeypot

A lightweight Python automation script designed to simulate a basic security honeypot. 

## How It Works
1. **File Detection**: Uses the `os` module to check for a decoy sensitive file (`credit_cards.txt`).
2. **Data Generation**: Automatically initializes fake high-value data if the file is missing.
3. **Intrusion Logging**: Appends a timestamped alert to a central security log if tampering/access is detected.
4. **Log Analysis**: Reads and parses the log file to generate a security alert report in the terminal.
