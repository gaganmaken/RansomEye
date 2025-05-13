# 🔒 RansomEye

**RansomEye** is an AI-powered, real-time ransomware detection and response system designed for both **Linux** and **Windows** environments. It monitors the entire infrastructure stack — from filesystems and applications to networks and databases — to detect, respond, and report ransomware threats with forensic-grade evidence.

---

## 🚀 Features

- ✅ Real-time ransomware detection
- 🤖 AI/ML-based behavior anomaly detection (Isolation Forest, LSTM)
- 🔍 Filesystem, process, registry, and network scanning
- 🕵️ Root Cause Analysis with infection chain visualization
- 🛡️ Auto-response: kill, quarantine, isolate
- 🌐 Deep Packet Inspection for network attack tracing
- 📊 Real-time dashboard for visualization and evidence
- 📁 Evidence export in CSV, PDF, JSON

---

## 📚 Modules

| Module             | Description |
|--------------------|-------------|
| **File Scanner**   | Detects file encryption, mass rename activity |
| **AI Detection**   | ML-based detection of suspicious patterns |
| **RCA Engine**     | Tracks origin and propagation of infection |
| **eBPF/WMI Agent** | Kernel-level monitoring (Linux/Windows) |
| **DPI Module**     | Detects ransomware traffic patterns |
| **Auto Scanner**   | Scans infra, DBs, apps, and network hosts |
| **Dashboard**      | Real-time visual interface with alerts, logs |

---

## 📄 Reports & Evidence

- Forensic logs of all activity (files, processes, IPs, ports)
- Report generation in:
  - 📑 CSV
  - 📘 PDF
  - 🧾 JSON

---

## 🖥️ Supported Platforms

- ✅ Linux (Ubuntu 22.04+)
- ✅ Windows 10/11 (PowerShell-enabled)

---

## ⚙️ Tech Stack

- Python + FastAPI
- eBPF (BCC, pybpf)
- WMI (Windows)
- Zeek / Suricata (DPI)
- scikit-learn, pandas
- PDFKit, WeasyPrint
- PostgreSQL or SQLite

---

## 🛠️ Installation

```bash
git clone https://github.com/YOUR-USERNAME/ransomeye.git
cd ransomeye
bash install.sh
