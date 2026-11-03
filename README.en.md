<div align="center">

# Hizam Nahari
### Certified Hardware Technician (BNSP) & Linux Systems Automation Practitioner

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/%5B%20ID%20Indonesia%20%5D-0A66C2?style=for-the-badge&logo=github&logoColor=white" alt="Bahasa Indonesia" /></a>
  <a href="./README.en.md"><img src="https://img.shields.io/badge/%5B%20US%20English%20%28Active%29%20%5D-238636?style=for-the-badge&logo=github&logoColor=white" alt="English" /></a>
</p>

<p align="center">
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portfolio-megapass.web.id%2Fteknisi-0A66C2?style=flat-square&logo=googlechrome&logoColor=white" alt="Technician Profile" /></a>
  <a href="https://skill.megapass.web.id"><img src="https://img.shields.io/badge/Skill_Portal-skill.megapass.web.id-0071E3?style=flat-square&logo=safari&logoColor=white" alt="Megapass Skill Portal" /></a>
  <img src="https://img.shields.io/badge/Location-Sidoarjo%2C%20East%20Java-D32F2F?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Certification-BNSP%20Electronics%20%26%20Mobile-4EAA25?style=flat-square&logo=target&logoColor=white" alt="Certified" />
  <img src="https://img.shields.io/badge/Focus-Hardware%20Repair%20%26%20Zero--Bloat%20Software-blueviolet?style=flat-square" alt="Focus" />
  <img src="https://komarev.com/ghpvc/?username=4ntiDandruff&style=flat-square&color=0A66C2&label=Profile+Views" alt="Profile Views" />
</p>

---

</div>

## Greetings from the Workbench

I am **Hizam Nahari**, a laptop and mobile phone hardware technician based in Sidoarjo, East Java, Indonesia.

My workdays revolve around the repair bench: holding soldering irons, hot air rework stations, multimeters, injecting DC voltage to track down overheated shorted components, reading boardview schematics, and replacing damaged ICs on motherboards.

**Why does a hardware technician write software?**  
Because repetitive, manual tasks waste valuable time. Instead of repeatedly right-clicking to extract schematic archives, typing lengthy, error-prone BIOS flashing parameters, or cleaning customer phones one by one, I build dedicated scripts and desktop utilities to automate the routine.

To me, tracking down a 19V short circuit on a motherboard feels identical to debugging a script in a Linux terminal: both require patience to study the schematics, digging until the real root cause is solved, and that genuine sense of relief when the machine boots back up cleanly.

---

### Why the Name `@4ntiDandruff`?

This handle came straight from everyday bench work fixing customer laptops and phones:

* **System "Dandruff"**: Most slow machines aren't broken physically. They're just clogged with "dandruff"—factory bloatware, aggressive telemetry, and background junk that spins cooling fans to max speed while typing a simple text document.
* **Leetspeak Style (4)**: Swapping the letter 'A' for '4' is a classic terminal habit—short, clean, and quick to type.
* **Personal Reminder**: A constant prompt that every script or tool I build should do one clear job: cut out the waste, save RAM, and keep systems feeling snappy.

<p align="center">
  <img src="https://raw.githubusercontent.com/4ntiDandruff/4ntiDandruff/main/assets/circuit-probing-station.svg?raw=true" width="100%" alt="Automated Circuit Micro-Probing & Debloating Station" />
</p>

---

## Daily Tools & Workbench Projects

The repositories here aren't classroom homework or throwaway experiments. These are tools I built to solve actual bottlenecks on my repair bench:

### [Megabox Releases](https://github.com/4ntiDandruff/megabox-releases)
A unified multi-platform desktop workspace for technicians (Windows & Linux).  
Instead of cluttering screens with dozens of disconnected terminal tabs, web reference pages, and cheat sheets that eat up RAM, everything is combined into a lightweight native app built on Tauri v2 (Rust). Fast startup, zero clutter, and memory usage under 40MB.  
`Tauri v2` • `Rust` • `Desktop Native` • `Windows & Linux`

### [Zero-Bloat Skills Ecosystem](https://skill.megapass.web.id)
A collection of 39 technician SOP modules for workbench hardware and bare-metal Linux.  
Real repair bench playbooks synced directly to AI coding agents (Google Antigravity, Claude Code, OMP, OpenCode, Codex). Engineered with a zero build-step design and no runtime node_modules, running smoothly on low-power workshop PCs (Core i3-3240) under 50MB RAM.  
`Linux Bare-Metal` • `AI Agent Skills` • `Zero-Bloat Architecture` • `Python/Bash`

### [CH341A BIOS Flasher](https://github.com/4ntiDandruff/CH341A-BIOS-Flasher-Tauri)
A clean, visual desktop GUI for USB EEPROM flashing tools (flashrom).  
Typing long flashrom commands in a terminal while clamping down a physical BIOS chip invites mistakes. This tool turns the workflow into straightforward controls: auto IC detection, dump backup, 3-pass verification, and safe firmware writing before soldering the chip back on the board.  
`Tauri v2` • `Rust` • `TypeScript` • `flashrom`

### [Mobile View](https://github.com/4ntiDandruff/mobile-view)
A Chromium browser extension for instant smartphone layout testing.  
Default browser responsive modes (F12) can feel clumsy and don't simulate how a real thumb reaches across a phone screen. This extension provides accurate device frames and triggers live reload via Linux kernel inotify events when code files are saved.  
`JavaScript` • `Chromium Manifest V3` • `Tailwind CSS` • `HTML5`

### [ADB Mobile Debloater](https://github.com/4ntiDandruff/adb-uninstaller)
A desktop batch uninstaller for stubborn Android bloatware via USB.  
Customer phones (Samsung, Xiaomi, Oppo, Vivo) frequently run out of space due to pre-installed apps that can't be removed through normal settings. This tool strips away clutter safely via ADB without needing root access.  
`Tauri v2` • `React` • `Android Debug Bridge (ADB)`

### [Windows Optimizer Toolkit](https://github.com/4ntiDandruff/windows-optimizer)
Lightweight maintenance scripts for temporary files and stealth startup tasks.  
Written in pure PowerShell and Batch. Cleans up slow customer laptops in seconds without installing third-party cleaner tools that push unwanted ads.  
`PowerShell` • `Batch` • `Windows Utilities`

### [Auto-Extract Downloads](https://github.com/4ntiDandruff/auto-extract-downloads)
A Linux background daemon that unpacks archives immediately after download.  
Whenever a schematic archive or BIOS zip finishes downloading, it unpacks automatically. Runs at 0% idle CPU via inotify-tools so your hands never need to leave the keyboard.  
`POSIX Shell` • `inotify-tools` • `Systemd User Unit`

### [Reverse SSH Tunnel](https://github.com/4ntiDandruff/reverse-ssh-tunnel)
NAT-bypassing reverse SSH tunnel with auto-reconnect and self-healing watchdogs.  
Allows me to securely connect to my workbench and shop servers from anywhere, even behind strict carrier NAT or dynamic home IP setups without port forwarding.  
`OpenSSH` • `Bash` • `Watchdog Daemon`

---

## Daily Workbench Stack

I stick to tools that are straightforward, reliable, and stay out of the way:

* **Operating System**: Linux (Ubuntu / Debian / Kubuntu). Rock-solid, lightweight, crystal-clear logs, with zero hidden background telemetry.
* **Automation**: Bash & Python. Fast scripting, data parsing, and connecting background services.
* **Backend**: Python FastAPI & SQLite. Easy to maintain, clear code flow, and SQLite WAL that shrugs off sudden workshop power cuts.
* **Web UI**: HTML5, Tailwind CSS, Alpine.js. Zero build-step setups: edit the file, save, and see results instantly in the browser.
* **Desktop Apps**: Tauri v2 (Rust). Native binaries that stay small, launch instantly, and sip RAM compared to Electron.
* **Version Control**: Git & GitHub. Tracking infrastructure configuration and keeping documentation organized.

---

## The Story Behind MEGAPASS

My repair shop in Sidoarjo is called **Megapass Intra Solusindo**:

* **Mega**: My wife's name. A steady reminder of why I work with care, honesty, and diligence every single day.
* **PASS**: The best feeling at the bench. When diagnostic tools display a green **PASS**, it means the dead board is restored, voltages are stable, hardware functions are verified, and the machine is ready to return to its owner.

I apply that same standard across everything: whether soldering a microscopic pin or writing application logic, I keep working until it genuinely earns a **PASS**.

---

## Hardware Training & Official Certifications

My foundation in electronics comes from formal hands-on training and certified testing:

* **BNSP (National Professional Certification Agency)** — Certified Electronics & Mobile Hardware Technician
* **BMY Yogyakarta** — Laptop Schematics & Motherboard Hardware Diagnostics
* **ITS Surabaya (PRODISTIK)** — D1 Information Technology & Circuit Design Fundamentals
* **PTC Indonesia & Arsalabs** — Advanced Mobile Device Hardware Repair
* **Magistra Utama** — Computer Hardware & Network Engineering Program

Physical certificate documentation and service portfolio: **[megapass.web.id/teknisi](https://megapass.web.id/teknisi/)**

---

<div align="center">

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/Website-megapass.web.id-000?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Website" /></a>
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portfolio-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Technician" /></a>
  <a href="https://skill.megapass.web.id"><img src="https://img.shields.io/badge/Skill_Portal-skill.megapass.web.id-0071E3?style=for-the-badge&logo=safari&logoColor=white" alt="Skill Portal" /></a>
</p>

**Megapass Intra Solusindo • Sidoarjo, Indonesia**  
*Certified Hardware Technician (BNSP) & Linux Systems Automation Practitioner*

</div>
