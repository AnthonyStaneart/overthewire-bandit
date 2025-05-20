# 🎯 OverTheWire Bandit CTF Walkthrough (Levels 0–20)

Welcome to the OverTheWire Bandit CTF Guide! This project contains step-by-step solutions to the Bandit wargame levels 0 through 20. These exercises are designed to build foundational Linux command-line and security skills, such as file navigation, permission handling, data extraction, and remote communication.

---

## 📌 Overview

**Project Goal:** Solve Bandit CTF levels 0–20 using Unix tools and logic-based problem solving.  
**Target Audience:** Beginners interested in cybersecurity and Linux fundamentals.

---

## 🛠️ Tools Used

- `SSH` – Secure Shell for accessing Bandit levels on port 2220
- `cat`, `ls`, `cd`, `pwd` – Basic file navigation
- `find`, `file`, `du`, `sort`, `uniq` – File discovery and filtering
- `grep`, `strings`, `tar`, `gzip`, `bzip2`, `xxd`, `tr` – Text and file manipulation
- `nc`, `openssl`, `bash` – Networking and scripting
- `chmod`, `ssh -i` – File permissions and key-based SSH login

---

## 🚀 Setup Instructions

1. Launch your terminal (preferably on Kali Linux or any Unix-based system).
2. Connect to Bandit Level 0 using:
   ```bash
   ssh bandit0@bandit.labs.overthewire.org -p 2220
   ```
3. Password for bandit0 is `bandit0`.
4. Read the instructions displayed after login for the current level.
5. Use Linux tools to discover and retrieve the password for the next level.
6. Continue this cycle until Level 20.

---

## 📚 Walkthrough Summary

Each level is documented with:
- **Challenge Objective**
- **Command(s) Used**
- **Password Output**
- **Key Lessons**

These solutions are written in a beginner-friendly narrative that highlights logic, command syntax, and problem-solving rationale.

---

## 🧠 Sample Solution Format

### Level 3

**Goal:** Find a hidden file starting with `.` in the `inhere` directory.

**Solution:**
```bash
cd inhere
ls -a
cat .hidden
```

**Output:**
```
<next_level_password>
```

**Takeaway:** Use `ls -a` to list hidden files. Dotfiles are often overlooked but may contain important data.

---

## 📝 Takeaways

- Reinforced foundational Linux knowledge
- Learned practical security concepts like privilege escalation and remote service interaction
- Developed the ability to automate repetitive CLI tasks
- Improved persistence and troubleshooting strategies essential to cybersecurity work

---

## 🧭 Final Notes

This walkthrough demonstrates practical command-line and cybersecurity skills necessary for SOC analysts, red teamers, and aspiring penetration testers.

*This guide is still a work-in-progress, but I will continue to update weekly!*  
