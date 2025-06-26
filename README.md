# CODTECH-Task1
**Name:** SANJANA PUROHIT
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08DL1470
**Domain:** Cyber Security & Ethical Hacking
**Duration:** 30th May to 30th July 2025
**Mentor:** Neela Kumar

# Task 1 – File Integrity Checker

### 🔐 Objective
Build a tool to monitor changes in files by calculating and comparing their hash values.

---

### ⚙️ Technologies Used
- Python
- `hashlib`
- `os`, `json`, `argparse`

---

### 🛠️ Features
- Scans all files in a given directory
- Calculates and saves SHA-256 hash values
- Compares hash values to detect:
  - Modified files
  - Deleted files
  - New files

---

### 📦 How to Run

1. Open terminal in the script folder  
2. To **scan and save hash values**:
   ```bash
   python file_integrity_checker.py scan your_folder --ref ref.json
