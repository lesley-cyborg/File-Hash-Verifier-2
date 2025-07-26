# 🧪 File Hash Verifier 2

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![GUI](https://img.shields.io/badge/GUI-Tkinter-informational)
![Security](https://img.shields.io/badge/Feature-Hash%20Validation-green)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🧰 About

**File Hash Verifier 2** is a Python GUI tool for computing and verifying cryptographic file hashes (SHA-256, SHA-1, MD5).  
It also includes file metadata lookup, VirusTotal hash checking, batch file processing, and exportable reports in TXT/CSV.

Whether you’re into cybersecurity, digital forensics, or general file integrity checks — this tool is for you.

---

## 🔍 Features

- ✅ Multi-hash support: `SHA-256`, `SHA-1`, `MD5`  
- ✅ VirusTotal integration: Check against known malware hashes  
- ✅ File metadata: Displays filename, size, and type  
- ✅ Batch mode: Select and verify multiple files at once  
- ✅ Clipboard support: Copy hash or full report to clipboard  
- ✅ Theme toggle: Switch between light and dark modes  
- ✅ Progress indicator: Visual feedback while verifying  
- ✅ Clear all fields: Reset inputs and outputs easily  
- ✅ Export reports: Save results to `.txt` and `.csv`  
- ✅ Session history panel: View previously verified files  

---

## 🚀 Installation

### 🐍 Prerequisites

- Python 3.9 or higher  
- `pip` package manager  

### 📦 Install Dependencies

```bash
pip install requests
```

✅ **No drag-and-drop dependencies needed!**  
The app uses a pure Tkinter approach for maximum compatibility.

---

## 💡 How to Use

1. Launch the app:

```bash
python File_Hash_Verifier_2.py
```

2. Click the **Browse** button to select one or more files  
3. Choose a hash type (SHA256, SHA1, or MD5)  
4. Optionally paste a known hash for verification  
5. Click **Verify** to begin the hashing and VirusTotal checks  
6. Copy results to clipboard or export to `.txt` / `.csv`  
7. Use the **History Panel** to view previous file results  

---

## 📁 Project Structure

```
📁 File_Hash_Verifier_2/
├── File_Hash_Verifier_2.py
├── README.md
├── screenshots/
│   └── demo.png
└── reports/
    ├── report.txt
    └── report.csv
```

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this software with attribution.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🛠️ TODO / Feature Ideas

- ⬜ Optional drag-and-drop support  
- ⬜ Upload files to VirusTotal directly  
- ⬜ Persistent history between sessions  
- ⬜ Generate QR codes for each hash  

---

## 🙌 Acknowledgments

- [VirusTotal API](https://developers.virustotal.com)  
- [Python Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)  
- `hashlib`, `mimetypes`, and `os` for core functionality  
