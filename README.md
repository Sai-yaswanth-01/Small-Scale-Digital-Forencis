# 🕵️ Small Scale Digital Forensics Investigation  
**CSCI 6638 / 4438 – Final Project**

## 📌 Overview
This repository contains the final digital forensic investigation report for **CSCI 6638 / 4438 (Small Scale Digital Forensics)**.  
The project analyzes multiple digital devices seized in connection with suspicious activities at the **National Gallery of Art, Washington, D.C.**

Through forensic analysis, the team uncovered **two separate but intersecting criminal conspiracies**, demonstrating insider threats, encrypted communications, steganography, and virtual machine misuse.

---

## 👥 Team Members
- **Pravallika Siddam**
- **Sai Yaswanth Bobbili**
- **Srikanth Guduri**
- **Bala Bhavya Sri Bhimineni**

**Instructor:** Murat Gunestas  
**Course:** Small Scale Digital Forensics (CSCI 6638/4438)  
**Date:** December 4, 2025  

---

## 🧩 Case Summary

### 🔴 Plan A – Art Defacement (Political Motivation)
- **Objective:** Deface foreign artwork from *Majavia* to embarrass the United States.
- **Orchestrator:** Alex (foreign nationalist from Krasnovia)
- **Local Coordinator:** Carry (U.S.-based operative)
- **Techniques Used:**
  - Encrypted communications
  - Steganographic audio/video
  - Social engineering via a fake “flash mob” event
  - Reconnaissance using GPS, Wi-Fi mapping, and browser artifacts

---

### 🔵 Plan B – Stamp Theft (Financial Motivation)
- **Objective:** Steal high-value stamp collections from the gallery.
- **Participants:**
  - Tracy – Gallery supervisor (insider threat)
  - Pat – Law enforcement officer and Tracy’s brother
  - King – External accomplice
- **Techniques Used:**
  - Virtual machines for covert planning
  - Disguised MP3 files containing hidden instructions
  - Unauthorized access to insurance and security documents

---

## 💾 Evidence Analyzed

### Devices
- Tracy’s iPhone
- Tracy’s home and work computers
- Carry’s Android tablet
- Carry’s mobile phone
- Tracy’s external hard drive (VM disk)
- Network and browser artifacts

### Artifact Types
- Emails and SMS messages
- Encrypted and steganographic media
- Virtual machine disk files (`.vmdk`)
- Browser history (hidden and deleted)
- GPS and Wi-Fi location data
- Gallery security schedules
- Insurance and valuation PDFs
- Photographs of targeted stamps

---

## 🛠️ Tools & Technologies

### Hardware
- MacBook Air (2024)
- HP Laptop
- 2TB External Hard Drive

### Software
- **Autopsy 4.22.1** – Primary forensic analysis tool
- DB Browser for SQLite
- VirtualBox
- 7-Zip
- Native macOS forensic utilities
- Spreadsheet tools for timeline reconstruction

---

## 🔬 Methodology
The investigation followed a **forensically sound and legally defensible workflow**:

1. Evidence acquisition and integrity verification (SHA-256 hashing)
2. File identification and classification
3. Database, media, and artifact extraction
4. Communication and relationship analysis
5. Timeline reconstruction (standardized to EST)
6. Cross-device correlation
7. Documentation and reporting

Chain-of-custody principles were maintained throughout the process.

---

## 📊 Key Findings
- Tracy served as the **critical insider link**, leaking confidential security data.
- Carry coordinated foreign operatives using encrypted and hidden communications.
- Virtual machines and steganography were deliberately used to evade detection.
- GPS and browser data confirmed reconnaissance and operational planning.
- Digital artifacts conclusively established **intent, preparation, and coordination**.

---

## 📄 Final Report
The complete forensic report is available as a PDF in this repository and includes:
- Detailed findings per device
- Full communication timelines
- Screenshots and forensic artifacts
- Legal-quality documentation

---

## ⚠️ Disclaimer
This project is **strictly academic**. All individuals, organizations, and scenarios are fictional and used solely for educational purposes.

---

## ⭐ Acknowledgments
Special thanks to **Professor Murat Gunestas** for guidance throughout the course and investigation.
