# Local Password Manager & File Storage Utility

## 📁 Project Overview
A lightweight, secure command-line interface (CLI) application built in Python that manages, generates, and persists user credential data. This project showcases file handling, local data storage pipelines, and dictionary-based lookups.

## 🛠️ Core Programming Concepts Demonstrated
* **File Handling & Persistence:** Implemented local file I/O streams using Python's context managers (`with open`) to append and retrieve structured string data dynamically from flat text files (`passwords.txt`).
* **Robust Exception Handling:** Utilized `try-except` blocks to handle system runtime anomalies gracefully, ensuring structural integrity even if the source data file is missing.
* **Efficient Memory Mapping:** Leveraged Python dictionary structures for O(1) time-complexity lookups when retrieving credentials by user query.
* **Algorithmic Logic:** Integrated the `random` and `string` libraries to programmatically build randomized strings containing cryptographic characters for password generation.

## 🚀 How to Run the Script
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Run the main application file:
   ```bash
  password_manager.py
   ```
# Password-Manager
A lightweight Python application demonstrating flat-file data persistence, exception handling, and dictionary-based lookups for secure credential storage.
