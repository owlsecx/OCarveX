# 🪓 OCarve

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20Binary%20Analysis-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v2.0-cyan?style=flat-square"/>
</p>

> **OCarve** is a powerful binary file carving and forensic extraction tool. It recovers embedded, deleted, or hidden files from any binary stream (disk images, memory dumps, network captures, evidence files) using magic signature carving, entropy analysis, and deep forensic scanning.

---

## 📌 Overview

OCarve scans raw binary data for 30+ file types using header/footer detection and advanced carving logic. It supports full forensic analysis, hex inspection, string extraction, IOC hunting, and batch processing.

**No external dependencies** — works with Python standard library only.

---

## 🖥️ Modules

| # | Module                    | Description |
|---|---------------------------|-------------|
| **[1]** | **Carve File**            | Extract all embedded files using 30+ carving rules |
| **[2]** | **Forensic Scan**         | Full binary analysis (signatures, entropy, IOCs, polyglot detection) |
| **[3]** | **Hex Inspector**         | View file in hex + ASCII at any offset |
| **[4]** | **String Extractor**      | Extract ASCII, UTF-8, and UTF-16LE strings |
| **[5]** | **IOC Hunter**            | Extract URLs, IPs, emails, domains, and file paths |
| **[6]** | **Batch Carve**           | Carve all files in a folder |
| **[7]** | **Last Report**           | View results of the last operation |
| **[8]** | **Settings**              | Configure carving rules, entropy thresholds, output |

---

## 📊 Key Features

- **30+ Carving Rules** — JPEG, PNG, GIF, PDF, ZIP, RAR, GZIP, ELF, PE/EXE, MP3, MKV, SQLite, PSD, OLE, RTF, and more
- **Advanced Carving Engine** — Header + Footer detection, embedded size parsing (BMP, RIFF, PE), entropy-based end detection
- **Forensic Analysis** — Global & local entropy, polyglot detection, signature hits
- **IOC Extraction** — URLs, IPs, emails, Windows/Unix paths
- **String Harvesting** — ASCII + UTF-16LE with configurable minimum length
- **Hex Inspector** — Interactive hex dump with ASCII view
- **Batch Processing** — Carve entire directories
- **Detailed Reports** — JSON + TXT with hashes, offsets, entropy, and carved file list

---

## ⚙️ Requirements

- **Linux or Windows**
- **No additional dependencies** — uses only Python standard library

---

## 🚀 Usage

```bash
./OCarve

📁 Output

Carved Files — Saved to ocarve_results/carved/ with numbered names and original extensions
Rich Terminal Reports — Colored findings, entropy levels, signature hits
JSON & TXT Reports — Full forensic reports with timestamps, hashes, offsets, and IOCs
Entropy Zones — Detection of high-entropy (likely encrypted) regions


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED FORENSIC ANALYSIS USE ONLY
