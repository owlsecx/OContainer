# 🦉 OContainer

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OContainer** — Docker / OCI Container Security Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

Docker / OCI container & image security auditor (CIS Docker Benchmark)

---

## ✨ Features

- Daemon exposure — docker.sock perms, TCP 2375/2376, daemon.json hardening, docker info, auditd rules
- Dockerfile linter — root, :latest, ADD, curl|bash, ENV/ARG secrets, apt hygiene, HEALTHCHECK, layers
- Image & running-container audit (live or offline)
- Compose auditor with crash-proof YAML-subset parser
- Secrets scanner, CIS Docker mapping, score A–F
- Export TXT/MD/JSON/CSV, save chooser, clipboard, CLI
- Audit / read-only: never changes anything

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OContainer
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
