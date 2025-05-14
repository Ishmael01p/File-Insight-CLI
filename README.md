# 📁 File Insight CLI Tool

A command-line tool written in Java that scans directories and provides insightful summaries about the files it finds. This project is ideal for anyone looking to explore file I/O, CLI development, and modular Java architecture.

---

## ✅ Features

- 📂 **Directory Scanning**  
  Traverse any directory and analyze all contained files and subdirectories.

- 📊 **File Summary Reports**  
  Output total number of files, grouped by extension, size, and modification date.

- 🔍 **Filtering Support**  
  Filter files by extension, size, or custom rules (e.g., `--filter=ext:.txt`).

- 🧾 **Detailed Metadata**  
  Display size, last modified date, file path, and more.

- 📤 **Optional Output to File**  
  Save results as a formatted report or JSON.

---

## 🛠 Project Structure


---

## 🚀 Sample Usage

```bash
# Show a summary of all files in the current directory
java -jar file-insight-tool.jar --path ./ --summary

# Show details of all .java files
java -jar file-insight-tool.jar --path ./ --details --filter=ext:.java
