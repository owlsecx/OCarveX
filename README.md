# 🦉 OCarveX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OCarveX** — Binary File Carver & Forensic Extractor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OCarveX is a binary file carver and forensic extractor that pulls embedded files out of raw binary streams by magic signature. It can reconstruct fragmented data, perform deep forensic analysis and generate carving reports, using only the Python standard library. It runs interactively from a menu or with a configurable output directory.

---

## ✨ Features

- Signature-based carving of embedded files from binary streams
- Fragmented-data reconstruction
- Deep forensic analysis of carved objects
- Carving report generation
- Configurable output directory
- No external dependencies — standard library only

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OCarveX
./OCarveX -o ./carved/
./OCarveX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
