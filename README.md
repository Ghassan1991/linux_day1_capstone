# 🐧 Linux Day 1 Capstone

**Author:** Ghassan Mohammed Alkahlout  
**Built with:** Bash Shell Scripts 🧠  
**Category:** Linux, Automation, System Scripting  

---

## 🧠 Overview

This capstone project demonstrates essential Linux automation skills using **shell scripting** —  
a foundation for any Data Science or MLOps workflow.

The goal is to simulate a small **DevOps-style system pipeline**,  
automating routine tasks like system reporting, file backup, and permission checks.

---

## ⚙️ Scripts Overview

| Script | Description |
|--------|-------------|
| 🧾 `system_report.sh` | Generates a quick system status report (disk, users, memory). |
| 💾 `backup.sh` | Creates timestamped backups of important files. |
| 🔐 `permissions_check.sh` | Validates and fixes file permissions automatically. |
| 🚀 `run_demo.sh` | Runs all scripts sequentially and saves output logs. |

---

## 🚀 How to Run

```bash
# Make scripts executable
chmod +x *.sh

# Run the full pipeline
./run_demo.sh
