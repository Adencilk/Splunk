# TryHackMe Splunk Labs & Blue Team Writeups

Repository for documenting my progress, lab notes, security analysis, and SPL (Search Processing Language) queries from **TryHackMe (THM)** Splunk rooms. This serves as a personal knowledge base for security monitoring, threat hunting, and digital forensics.

## 🚀 Repository Structure

*   📁 `cheatsheets/` — Quick reference guides for SPL syntax, command breakdowns, and common security event IDs.
*   📁 `rooms/` — Individual folders for each completed TryHackMe Splunk room, containing notes, writeups, and `.spl` files.

---

## 📊 Lab Progress Tracker

| Room Name | Difficulty | Status | Focus Area |
| :--- | :--- | :--- | :--- |
| Splunk: Basic | Easy | ✅ Completed | UI Navigation, Basic SPL commands |
| Splunk: Exploring | Easy | ✅ Completed | Search optimization, Event parsing |
| Splunk: Data Manipulation | Medium | ⏳ In Progress | Data models, lookups, regex |
| Incident Handling with Splunk | Medium | 📅 Planned | Attack timeline reconstruction |

---

## 🛠️ Core Skills Developed

*   **Threat Hunting:** Querying Windows Event Logs (Sysmon), Linux Syslog, and Web Server logs to track malicious activity.
*   **Incident Reconstruction:** Mapping out attacker lifecycles, identifying lateral movement, and building malicious timelines.
*   **Log Analysis:** Advanced data parsing using commands like `stats`, `eval`, `rex` (Regex), and `transaction`.

---

## 📖 How I Structure My Room Writeups

Each room folder inside `rooms/` follows a clean, structured documentation process:
1.  **Objective:** What was the goal of the simulation or incident response?
2.  **Artifacts:** What log sources were used (e.g., Sysmon, Fortinet, Apache)?
3.  **Attack Timeline:** A chronological breakdown of how the attacker breached and moved through the environment.
4.  **SPL Playbook:** The exact search queries used to uncover indicators of compromise (IOCs).

---

## ⚖️ Disclaimer

This repository is strictly for educational purposes and personal study. No direct flag answers or unauthorized spoilers are provided to preserve the learning experience for others on TryHackMe.
