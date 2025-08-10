# 🛡️ File Integrity Checker (SHA-256)

A simple **Python-based File Integrity Checker** that helps you detect whether important files have been modified, deleted, or tampered with.  
It uses **SHA-256 cryptographic hashing** to generate and compare file hashes.

---

## 📌 Features
- Generate SHA-256 hashes for files and save them in a baseline JSON file.
- Compare current file hashes with the saved baseline to detect:
  - File changes
  - Missing files
- Works on **Windows, Linux, and macOS**.
- Easy command-line interface.

---

## 🛠️ Requirements
- Python **3.x** installed on your system.

No additional libraries are needed since it only uses Python's **built-in modules**:
- `hashlib`
- `json`
- `os`

---

## 🚀 How to Use

### 1️⃣ Clone or Download the Script
```bash
git clone https://github.com/yourusername/file-integrity-checker.git
cd file-integrity-checker
