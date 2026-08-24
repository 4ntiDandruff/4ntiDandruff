<div align="center">

# Hizam Nahari
### *Certified Circuit Technician • Hardware Hacker • Systems Automation Engineer*

<p align="center">
  <b>"I trace dead power rails on the repair bench, then engineer the native tools to automate the rest."</b>
</p>

<p align="center">
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Verified%20Credentials-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Technician Profile" /></a>
  <img src="https://img.shields.io/badge/Sidoarjo-Indonesia-D32F2F?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/BNSP%20%26%20BMY-10%20Official%20Certifications-4EAA25?style=for-the-badge&logo=target&logoColor=white" alt="Certified" />
  <a href="https://github.com/4ntiDandruff?tab=followers"><img src="https://img.shields.io/github/followers/4ntiDandruff?style=for-the-badge&color=blueviolet&label=FOLLOWERS" alt="Followers" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-12%2B%20Years-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Hardware%20Fixed-1000%2B%20Devices-success?style=flat-square" />
  <img src="https://img.shields.io/badge/BNSP%20Score-100%2F100%20Theory-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Customer%20Rating-4.9%20★-yellow?style=flat-square" />
</p>

---

</div>

## 🛠️ The Philosophy & Background

I am a certified hardware circuit technician running **Megapass Intra Solusindo**, an electronics diagnostic & board-level repair lab in Sidoarjo, Indonesia. My core environment is a hot air rework station, digital multimeters, oscilloscopes, and boardview schematics — diagnosing motherboard shorts, tracing voltage drops across power rails, and micro-soldering ICs.

Software was never meant to be an academic pursuit. It was forged on the repair counter out of sheer friction:
- Flashing BIOS chips through cryptic CLI flags $\rightarrow$ Built **CH341A Flasher GUI**.
- Manually debloating dozens of customer Android phones $\rightarrow$ Built **ADB Uninstaller**.
- Migrated from Windows to **Kubuntu (KDE 6 / Wayland)** and hit file-picker isolation $\rightarrow$ Built **Auto-Extract Downloads** (Event-driven Linux daemon).

> **The Hardware Rule**: *"If a shell one-liner or native daemon solves the problem, that is the answer. No bloatware, zero CPU polling, pure cause-and-effect logic."*

---

## 📜 Verified Competence & Certifications

All hardware work and tooling are backed by national standard certifications and formal vocational training:

| Certification / Body | Focus Area | Credential Highlights |
|---|---|---|
| 🏆 **BNSP (National Certification)** | Cellular & Microelectronics Repair | **Perfect Theory Score (100/100)** on circuit architecture & electronics |
| 🔬 **BMY Yogyakarta** | Motherboard & Schematic Specialist | Laptop motherboard no-power/no-display diagnostics with oscilloscopes |
| 🎓 **ITS Surabaya (PRODISTIK)** | D1 Information Technology | Circuit design, precision soldering, & IT vocational foundation |
| 📱 **PTC Indonesia & Arsalabs** | Advanced Phone & IC Rework | Micro-soldering, IC reballing, power-rail tracing, & firmware flashing |
| 💻 **Magistra Utama** | Hardware & Software Engineering | Computer hardware technician, networking, & web development |
| 🤝 **TESPOIN Member** | Indonesian Mobile Technicians | Official national professional technician association |

👉 *View physical certificates & workstation setup:* **[megapass.web.id/teknisi](https://megapass.web.id/teknisi/)**

---

## 💻 Technical Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,rust,tauri,python,typescript,react,fastapi,flask,htmx,tailwind,sqlite,git,docker&theme=dark" alt="Tech Stack" />
</p>

| Domain | Stack & Toolchain | Focus / Implementation |
|---|---|---|
| **Hardware & Bench** | CH341A Programmer, `flashrom`, Multimeter, Oscilloscope, Boardview | IC-level rework, schematic analysis, BIOS/UEFI firmware recovery |
| **Linux & Desktop Systems** | KDE Plasma 6, Wayland, POSIX Bash, `inotifywait`, Systemd Daemons | Native background daemons, zero-polling desktop automations |
| **GUI & Tooling** | Tauri v2, Rust, React, TypeScript, Vite | Fast, cross-platform desktop GUIs wrapping lower-level hardware CLIs |
| **Backend & Web Engineering** | Python (FastAPI, Flask), HTMX, Tailwind CSS v4, SQLite | Lightweight, reactive business dashboards & high-conversion web apps |
| **Systems & Operations** | Linux Daemons, Systemd, Process Management, Local Service Ops | Lightweight background services, local automation, and diagnostic tooling |

---

## ⚡ Featured Engineering Projects

### 🚀 [Auto-Extract Downloads for Linux](https://github.com/4ntiDandruff/auto-extract-downloads)
**Event-Driven Archive Extraction Daemon with 9-Layer Safety Fuses**  
Solves file-picker import friction on Linux Desktop (KDE/GNOME). Uses kernel interrupt signals (`inotify`) to extract `.zip`, `.rar`, `.7z` instantly with **0% idle CPU** and **~1.5 MB RAM**. Features **Self-Compress Loop Guard**, disk undervoltage cutoff, and dynamic CLI switches (`auto-extract limit/depth`).  
`Shell` • `inotify-tools` • `Systemd User Unit` • `libnotify` • `unar/7z`

### 🔌 [CH341A BIOS Flasher Tauri](https://github.com/4ntiDandruff/CH341A-BIOS-Flasher-Tauri)
**Professional Hardware GUI for CH341A USB Programmer**  
A desktop application wrapping `flashrom` for laptop & motherboard repair benches. Eliminates manual command memorization and provides visual chip detection, read/write verification, and safe ROM flashing.  
`Tauri v2` • `Rust` • `TypeScript` • `Python` • `flashrom`

### 🤖 [ADB Uninstaller](https://github.com/4ntiDandruff/adb-uninstaller)
**AI-Powered Android Debloater & Package Resolver**  
Desktop tool designed for phone servicing. Batch-removes vendor bloatware across multiple USB-connected devices and maintains a self-learning knowledge base for safe package removal.  
`Tauri v2` • `React` • `TypeScript` • `Android Debug Bridge (ADB)`

### 🌐 [kalenderia.my.id](https://github.com/4ntiDandruff/kalenderia.my.id)
**High-Precision Commercial Printing Engine & Workshop System**  
Production web application for custom calendar manufacturing in Sidoarjo. Engineered with a clean no-build philosophy for instant reactivity and zero JavaScript bloat.  
`Python Flask` • `HTMX` • `Tailwind CSS v4` • `Jinja2`

---

## 📈 Activity & Development

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=4ntiDandruff&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" />
</p>

---

<div align="center">

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/Visit-megapass.web.id-000?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Site" /></a>
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Technician%20Portfolio-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Technician" /></a>
</p>

*Built with precision on the bench • Shipped to production.*  
**Megapass Intra Solusindo • Sidoarjo, East Java, Indonesia**

</div>
