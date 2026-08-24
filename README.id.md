<div align="center">

<img src="https://raw.githubusercontent.com/4ntiDandruff/4ntiDandruff/main/assets/header.svg" alt="Hizam Nahari - Teknisi Elektronika & Otomasi Sistem" width="100%" />

<br/>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/Language-🇺🇸%20English-blue?style=flat-square" alt="English" /></a>
  <a href="./README.id.md"><img src="https://img.shields.io/badge/Bahasa-🇮🇩%20Indonesia-red?style=flat-square" alt="Bahasa Indonesia" /></a>
</p>

<p align="center">
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Sertifikat%20%26%20Portofolio-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Profil Teknisi" /></a>
  <img src="https://img.shields.io/badge/Lokasi-Sidoarjo%2C%20Jawa%20Timur-D32F2F?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Lokasi" />
  <img src="https://img.shields.io/badge/BNSP%20%26%20BMY-10%20Sertifikasi%20Resmi-4EAA25?style=for-the-badge&logo=target&logoColor=white" alt="Tersertifikasi" />
  <a href="https://github.com/4ntiDandruff?tab=followers"><img src="https://img.shields.io/github/followers/4ntiDandruff?style=for-the-badge&color=blueviolet&label=FOLLOWERS" alt="Followers" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pengalaman-12%2B%20Tahun-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Perangkat%20Tertangani-1000%2B%20Unit-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Nilai%20Ujian%20BNSP-100%2F100%20Teori-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Rating%20Servis-4.9%20★-yellow?style=flat-square" />
</p>

---

</div>

## 🔧 Tentang Saya & Meja Servis

Saya teknisi elektronika dan pemilik **Megapass Intra Solusindo** di Sidoarjo. Keseharian saya berhadapan langsung dengan blower, solder uap, multitester, osiloskop, dan skematik *boardview* — mulai dari nyari jalur korslet, analisa drop tegangan, sampai angkat-pasang IC HP dan laptop.

Saya mulai coding bukan untuk gaya-gayaan bikin portofolio, tapi murni karena butuh alat bantu saat servis:
- Capek hafalin perintah terminal tiap kali mau flash BIOS laptop $\rightarrow$ Saya bikin **CH341A Flasher GUI**.
- Repot hapus aplikasi bawaan (*bloatware*) di puluhan HP servisan satu-satu $\rightarrow$ Saya bikin **ADB Uninstaller**.
- Hijrah ke Linux (**Kubuntu 26.04**) dan ngerasa ribet pas mau ekstrak file arsip di jendela dialog import $\rightarrow$ Saya bikin background service **Auto-Extract Downloads**.

> **Prinsip Kerja**: *"Kalau masalahnya bisa selesai pakai script ringan yang 0% beban CPU, ya itu yang dipakai. Gak perlu aplikasi berat atau ribet."*

---

## 📜 Sertifikasi & Pelatihan Resmi

Keahlian servis dan hardware saya didasari oleh sertifikasi profesi nasional dan pelatihan resmi:

| Lembaga | Bidang Kompetensi | Keterangan |
|---|---|---|
| 🏆 **BNSP** | Reparasi Telepon Seluler | **Nilai Teori Sempurna (100/100)** pada ujian elektronika & sirkuit |
| 🔬 **BMY Yogyakarta** | Spesialis Motherboard Laptop & Skematik | Analisa motherboard mati total & no display pakai osiloskop |
| 🎓 **ITS Surabaya (PRODISTIK)** | D1 Teknologi Informasi | Dasar kelistrikan, pembuatan jalur PCB, & teknik solder presisi |
| 📱 **PTC Indonesia & Arsalabs** | Servis HP Lanjutan & Angkat Pasang IC | Reball IC, pelacakan jalur tegangan, & penanganan HP mati total |
| 💻 **Magistra Utama** | Hardware & Jaringan Komputer | Teknisi hardware komputer, instalasi jaringan, & dasar web |
| 🤝 **TESPOIN** | Asosiasi Teknisi Ponsel Indonesia | Anggota resmi asosiasi teknisi nasional |

👉 *Foto fisik sertifikat dan meja servis bisa dilihat langsung di:* **[megapass.web.id/teknisi](https://megapass.web.id/teknisi/)**

---

## 💻 Alat & Teknologi yang Dipakai

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,rust,tauri,python,typescript,react,fastapi,flask,htmx,tailwind,sqlite,git,docker&theme=dark" alt="Tech Stack" />
</p>

| Bidang | Alat & Bahasa | Penggunaan Nyata |
|---|---|---|
| **Hardware & Servis** | CH341A Flasher, `flashrom`, Multitester, Osiloskop, Boardview | Angkat pasang IC, baca skema motherboard, recovery firmware BIOS/UEFI |
| **Linux & Desktop** | KDE Plasma 6, Wayland, Bash Script, `inotifywait`, Systemd | Bikin background service otomatis yang ringan tanpa makan RAM/CPU |
| **Aplikasi Desktop GUI** | Tauri v2, Rust, React, TypeScript, Vite | Bikin tampilan GUI desktop yang kencang dan enteng untuk alat-alat servis |
| **Web & Dashboard** | Python (FastAPI, Flask), HTMX, Tailwind CSS v4, SQLite | Bikin sistem dashboard bengkel dan web bisnis tanpa bloatware JavaScript |

---

## ⚡ Proyek yang Lahir dari Meja Servis

### 🚀 [Auto-Extract Downloads for Linux](https://github.com/4ntiDandruff/auto-extract-downloads)
**Background Service Ekstraksi Arsip Otomatis untuk Linux Desktop (KDE/GNOME)**  
Mengatasi ribetnya ekstrak file saat mau import berkas di Linux. Berjalan otomatis di background via event kernel (`inotify`) dengan **0% CPU saat idle** dan RAM cuma **~1.5 MB**. Dilengkapi 9 pengaman (anti-loop saat kompres folder sendiri, deteksi sisa storage, dan filter file disk image).  
`Shell` • `inotify-tools` • `Systemd User Unit` • `libnotify` • `unar/7z`

### 🔌 [CH341A BIOS Flasher Tauri](https://github.com/4ntiDandruff/CH341A-BIOS-Flasher-Tauri)
**Aplikasi GUI Desktop untuk Alat Flash CH341A USB**  
Aplikasi pembungkus engine `flashrom` untuk meja servis laptop. Menghilangkan repotnya ketik perintah terminal, bisa deteksi tipe IC otomatis, verifikasi hasil baca/tulis, dan aman buat flash BIOS.  
`Tauri v2` • `Rust` • `TypeScript` • `Python` • `flashrom`

### 🤖 [ADB Uninstaller](https://github.com/4ntiDandruff/adb-uninstaller)
**Aplikasi Debloat Android dengan Bantuan AI**  
Alat bantu servis HP untuk menghapus aplikasi bawaan secara massal (*batch*) di banyak HP sekaligus via kabel USB, lengkap dengan panduan paket mana yang aman dihapus.  
`Tauri v2` • `React` • `TypeScript` • `Android Debug Bridge (ADB)`

### 🌐 [kalenderia.my.id](https://github.com/4ntiDandruff/kalenderia.my.id)
**Mesin Percetakan & Sistem Workshop Kalender Presisi Sidoarjo**  
Aplikasi web komersial untuk workshop percetakan kalender di Sidoarjo. Dibuat pakai pendekatan *no-build* (Flask + HTMX) biar loading-nya instan dan bebas lemot.  
`Python Flask` • `HTMX` • `Tailwind CSS v4` • `Jinja2`

---

<div align="center">

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/Website-megapass.web.id-000?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Website" /></a>
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portofolio%20Teknisi-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portofolio" /></a>
</p>

*Dibuat langsung dari meja servis Megapass • Sidoarjo, Jawa Timur, Indonesia.*

</div>
