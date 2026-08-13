<h1 align="center">Hizam Nahari</h1>

<p align="center">
  <b>Circuit Technician → Systems Automation</b><br>
  I fix what other shops declare dead, then write the tools that make it faster.
</p>

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/megapass.web.id-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <img src="https://img.shields.io/badge/Sidoarjo-Indonesia-D32F2F?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <a href="https://github.com/4ntiDandruff?tab=followers"><img src="https://img.shields.io/github/followers/4ntiDandruff?style=for-the-badge&color=success&label=FOLLOWERS" alt="Followers" /></a>
</p>

---

## About

I'm a certified circuit technician (BMY Yogyakarta · BNSP) running **Megapass Intra Solusindo**, an electronics repair shop in Sidoarjo. My day job is a hot air station, a multimeter, and a boardview file — tracing power rails and reworking ICs on phones and laptops.

Software wasn't the plan. It happened because the repair bench kept hitting the same walls: flashing BIOS chips through cryptic CLI flags, debloating dozens of Android devices by hand, checking whether the shop's network was actually up. So I started building the missing tools, one bench problem at a time.

Everything here is **shop-tested code** — written for a working service counter, not a portfolio.

- 🔧 **Hardware first** — schematic tracing, IC-level rework, boardview analysis
- 🤖 **Automation second** — desktop GUIs that wrap ugly CLIs into something a technician can actually use
- 🌐 **Infrastructure to keep it running** — a 5-node mesh serving live dashboards and bots

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,react,rust,tauri,fastapi,flask,bash,linux,git,sqlite,vite,nodejs&theme=dark" alt="Tech stack" />
</p>

| Layer | Tools |
|---|---|
| **Desktop apps** | Tauri v2 · React · TypeScript · Rust |
| **Backend / API** | FastAPI · Flask · SQLite |
| **Bench hardware** | CH341A programmer · hot air station · multimeter · oscilloscope · `flashrom` |
| **Ops** | PM2 · systemd · SSH · Tailscale mesh · Cloudflare Tunnel · AdGuard Home |

---

## Projects

### 🔌 [CH341A BIOS Flasher](https://github.com/4ntiDandruff/CH341A-BIOS-Flasher-Tauri)
Desktop GUI for the CH341A USB programmer. Wraps `flashrom` so BIOS/UEFI chip reads, writes, and verification stop being a memory test on command-line flags. Built for the Megapass bench and used on real repair jobs.

`Tauri v2` · `Python` · `TypeScript` · `flashrom`

### 🤖 [ADB Uninstaller](https://github.com/4ntiDandruff/adb-uninstaller)
Android debloater with AI-assisted package resolution. Batch-strips bloatware across multiple connected devices and keeps a self-growing knowledge base of what each obscure package actually does — so you learn the safe removals instead of guessing.

`Tauri v2` · `React` · `TypeScript` · `ADB`

### 🪟 [Windows Optimizer](https://github.com/4ntiDandruff/windows-optimizer)
Windows maintenance, bloatware cleanup, and performance scripts. Written to be driven remotely over SSH from a Linux workstation, because the customer's machine is usually on the other side of the counter.

`PowerShell` · `Python` · `SSH`

### 🧰 Shop infrastructure *(private)*
Flask dashboards, Telegram ops bots, and a FastAPI + React repair-bench assistant running on a Tailscale mesh. Network monitoring, PM2 control, and schematic lookup for the service counter.

`Flask` · `FastAPI` · `SQLite` · `PM2`

---

## Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=4ntiDandruff&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" />
</p>

---

## How I Build

**Simple beats clever.** If a shell one-liner solves it, that's the answer — I'm not adding five layers of abstraction to check the time. Every tool here started as a real problem at the bench, so it ships when it works on the bench.

**Hardware intuition, applied to software.** Debugging a program isn't that different from tracing a dead rail: follow the signal, find where it drops, fix the cause instead of the symptom.

---

## Active Repositories

- 📅 **[kalenderia.my.id](https://github.com/4ntiDandruff/kalenderia.my.id)** — Workshop Percetakan Kalender Presisi Sidoarjo 2027 (Python Flask + HTMX + Tailwind v4)

---

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/Visit-megapass.web.id-000?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Site" /></a>
</p>

<p align="center">
  <i>Megapass Intra Solusindo — electronics repair & diagnostics · Sidoarjo, Indonesia</i>
</p>
