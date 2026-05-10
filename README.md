# Simple Python SHA-256 Hasher

## Project Overview
This is a Python-based utility designed to generate **SHA-256 cryptographic hashes** from user input. In security engineering, hashing is a fundamental concept used to ensure **Data Integrity**—verifying that information has not been altered or tampered with.

## How It Works
The script utilizes Python's built-in `hashlib` library to:
1. Accept a string input from the user.
2. Encode the string into bytes (UTF-8).
3. Process the bytes through the SHA-256 algorithm.
4. Output a 64-character hexadecimal "fingerprint."

## Security Use Cases
I built this project to demonstrate the following security principles:
* **Password Hashing:** Understanding how systems store "receipts" of passwords rather than plain text to prevent data breaches.
* **The Avalanche Effect:** Demonstrating that a single character change in input results in a completely different hash output.
* **Integrity Verification:** A precursor to building File Integrity Monitoring (FIM) tools.

## 🛠️ Requirements
* Python 3.x
* No external libraries required (uses standard library `hashlib`)

## 📖 How to Run
1. Ensure you have Python installed.
2. Run the script via terminal or an IDE like Thonny:
