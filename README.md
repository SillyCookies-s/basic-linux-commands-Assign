# 🐧 Linux Commands 101

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-4D4D4D?style=for-the-badge&logo=gnometerminal&logoColor=white)

This repository contains the completion of **Assignment 1 - Linux Commands Practice**.

## 🎯 Assignment Overview

This assignment demonstrates fundamental Linux command-line operations essential for **system administration** and **DevOps** roles:

| Task | Commands | Description |
|------|----------|-------------|
| 📁 **File & Directory Operations** | `mkdir`, `touch`, `mv` | Creating directories, files, and renaming |
| 👀 **File Content Viewing** | `cat`, `head`, `tail` | Displaying and viewing file contents |
| 🔍 **Pattern Searching** | `grep` | Finding text patterns in files |
| 🗃️ **File Compression** | `zip`, `unzip` | Creating and extracting archives |
| 🌐 **Downloading Files** | `wget` | Downloading files from web |
| 🔒 **File Permissions** | `chmod` | Managing file access permissions |
| 🌍 **Environment Variables** | `export`, `echo` | Setting and displaying variables |

## 📂 Repository Structure

```
linux-commands-assignment/
├── 📝 README.md                    # Project documentation
├── 📜 commands_used.txt           # Complete command reference
├── 📄 report.docx                 # Complete assignment report with screenshots
├── 📷 screenshots/                # Command execution screenshots
│   ├── 1.png                    # File & directory operations
│   ├── 2.1.png, 2.2.png         # File content viewing
│   ├── 3.png                    # Pattern searching
│   ├── 4.png                    # Compression operations
│   ├── 5.png                    # File downloading
│   ├── 6.png                    # Permission changes
│   └── 7.png                    # Environment variables
├── 📁 test_dir/                   # Original test directory
│   └── renamed_example.txt
├── 📁 unzipped_dir/               # Extracted archive contents
├── 🔒 secure.txt                  # Read-only permission file
└── 📦 test_dir.zip                # Compressed archive
```

## ⚙️ Commands Summary

```bash
# Directory and file operations
mkdir test_dir
touch test_dir/example.txt
mv test_dir/example.txt test_dir/renamed_example.txt

# File viewing
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

# Pattern searching
grep "root" /etc/passwd

# Compression
zip -r test_dir.zip test_dir/
unzip test_dir.zip -d unzipped_dir/

# Downloading files
wget https://github.com/trinib/Linux-Bash-Commands/blob/main/README.md

# Permissions
chmod 444 secure.txt

# Environment variables
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

## 📸 Screenshots

All command executions are documented with screenshots from **Kali Linux VM**:

- **1.png** - Directory creation, file creation, and renaming operations
- **2.1.png & 2.2.png** - File content viewing with cat, head, and tail commands
- **3.png** - Pattern searching using grep command
- **4.png** - File compression and extraction operations
- **5.png** - File downloading using wget
- **6.png** - File permission modifications
- **7.png** - Environment variable operations

## 🏆 Assignment Completion

<div align="center">

| Status | Task |
|:------:|------|
| ✅ | All tasks completed successfully |
| 📸 | Screenshots captured and organized |
| 📝 | Documentation prepared |
| 📁 | Repository structured and ready |

</div>  

## 🛡️ Security Note

> **Important:** For security and privacy reasons, this repository doesn't include:
> - System files or sensitive information from production systems
> - Large output files from system commands

All commands were executed successfully in a **Kali Linux virtual machine** environment as documented in the assignment.

---

<div align="center">

**🐧 Built with Linux • 📚 Educational Purpose • ✨ Open Source**

</div>