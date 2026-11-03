<div align="center">

# Hizam Nahari
### Teknisi Perangkat Keras (BNSP) & Praktisi Otomasi Linux

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/%5B%20ID%20Indonesia%20%28Utama%29%20%5D-238636?style=for-the-badge&logo=github&logoColor=white" alt="Bahasa Indonesia" /></a>
  <a href="./README.en.md"><img src="https://img.shields.io/badge/%5B%20US%20English%20%5D-0A66C2?style=for-the-badge&logo=github&logoColor=white" alt="English" /></a>
</p>

<p align="center">
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portofolio-megapass.web.id%2Fteknisi-0A66C2?style=flat-square&logo=googlechrome&logoColor=white" alt="Profil Teknisi" /></a>
  <a href="https://skill.megapass.web.id"><img src="https://img.shields.io/badge/Portal_Keahlian-skill.megapass.web.id-0071E3?style=flat-square&logo=safari&logoColor=white" alt="Portal Skill Megapass" /></a>
  <img src="https://img.shields.io/badge/Lokasi-Sidoarjo%2C%20Jawa%20Timur-D32F2F?style=flat-square&logo=googlemaps&logoColor=white" alt="Lokasi" />
  <img src="https://img.shields.io/badge/Sertifikasi-BNSP%20Elektronika%20%26%20Ponsel-4EAA25?style=flat-square&logo=target&logoColor=white" alt="Tersertifikasi" />
  <img src="https://img.shields.io/badge/Fokus-Hardware%20Repair%20%26%20Zero--Bloat%20Software-blueviolet?style=flat-square" alt="Fokus" />
  <img src="https://komarev.com/ghpvc/?username=4ntiDandruff&style=flat-square&color=0A66C2&label=Profile+Views" alt="Profile Views" />
</p>

---

</div>

## Halo dari Meja Servis

Saya **Hizam Nahari**, teknisi perangkat keras laptop dan ponsel di Sidoarjo, Jawa Timur.

Sehari-hari saya sibuk di meja kerja ruko: pegang solder, blower uap, multitester, suntik tegangan buat raba komponen yang korslet, baca skema boardview, dan ganti IC di motherboard.

**Kenapa teknisi hardware bikin software?**  
Karena saya capek mengulang pekerjaan manual yang buang-buang waktu. Daripada bolak-balik klik kanan ekstrak file skema, ngetik parameter flash BIOS panjang-panjang yang rawan salah, atau bersihin HP pelanggan satu per satu, mending saya bikinkan skrip dan aplikasinya sendiri. 

Buat saya, nyari jalur short 19V di motherboard sama debug script di terminal Linux itu rasanya sama persis: butuh sabar baca skema, cari akar masalahnya sampai tuntas, dan lega banget pas mesinnya hidup normal lagi.

---

### Kenapa Namanya `@4ntiDandruff`?

Nama ini datang dari pengalaman harian pas nanganin laptop atau HP pelanggan:

* **Ketombe di Komputer**: Banyak perangkat lemot bukan karena mesinnya rusak, tapi karena kebanyakan "ketombe"—aplikasi sampah bawaan pabrik, telemetri, dan proses siluman di latar belakang yang bikin kipas muter kencang padahal cuma buat ngetik Word.
* **Gaya 4 Leetspeak**: Huruf A diganti angka 4 biar khas anak terminal, pendek, dan cepat diketik.
* **Pengingat Diri**: Biar setiap software atau skrip yang saya tulis tujuannya jelas: buang hal-hal yang mubazir, hemat RAM, dan bikin sistem kerja enteng lagi.

<p align="center">
  <img src="https://raw.githubusercontent.com/4ntiDandruff/4ntiDandruff/main/assets/circuit-probing-station.svg?raw=true" width="100%" alt="Automated Circuit Micro-Probing & Debloating Station" />
</p>

---

## Aplikasi & Perkakas yang Saya Pakai Kerja

Semua repositori di sini bukan tugas kuliah atau proyek coba-coba. Ini perkakas yang memang saya buat dan pakai sendiri tiap hari di meja servis:

### [Megabox Releases](https://github.com/4ntiDandruff/megabox-releases)
Aplikasi desktop ruang kerja teknisi untuk Windows & Linux.  
Daripada buka belasan jendela browser, terminal, dan file panduan yang bikin layar penuh dan makan RAM, semuanya saya satukan di satu aplikasi mandiri berbasis Tauri v2 (Rust). Ukurannya kecil, responsif, dan konsumsi memori enteng di bawah 40MB.  
`Tauri v2` • `Rust` • `Desktop Native` • `Windows & Linux`

### [Ekosistem Zero-Bloat Skills](https://skill.megapass.web.id)
Kumpulan 39 modul SOP teknisi meja servis dan otomasi Linux bare-metal.  
Panduan kerja nyata dari meja servis yang disinkronkan langsung ke asisten AI (Google Antigravity, Claude Code, OMP, OpenCode, Codex). Dibangun tanpa beban runtime node_modules agar hemat RAM dan lancar dijalankan di PC kerja ruko hemat daya (Core i3-3240).  
`Linux Bare-Metal` • `AI Agent Skills` • `Zero-Bloat Architecture` • `Python/Bash`

### [CH341A BIOS Flasher](https://github.com/4ntiDandruff/CH341A-BIOS-Flasher-Tauri)
Antarmuka desktop praktis buat alat flash BIOS USB (flashrom).  
Ngetik perintah flashrom panjang-panjang di terminal saat chip BIOS lagi dijepit itu rawan salah ketik. Tool ini membungkusnya jadi tombol yang jelas: deteksi IC otomatis, backup dump, verifikasi 3 tahap, dan isi firmware dengan aman sebelum chip disolder balik ke board.  
`Tauri v2` • `Rust` • `TypeScript` • `flashrom`

### [Mobile View](https://github.com/4ntiDandruff/mobile-view)
Ekstensi browser Chromium buat uji tampilan HP langsung di layar monitor.  
Mode inspect responsive bawaan browser (F12) sering kaku dan nggak ngasih gambaran jangkauan jempol di HP asli. Ekstensi ini ngasih bingkai ukuran ponsel nyata dan otomatis refresh lewat event inotify kernel Linux saat kode disimpan.  
`JavaScript` • `Chromium Manifest V3` • `Tailwind CSS` • `HTML5`

### [ADB Mobile Debloater](https://github.com/4ntiDandruff/adb-uninstaller)
Alat bersih-bersih aplikasi sampah di Android via kabel USB.  
Banyak HP pelanggan (Samsung, Xiaomi, Oppo, Vivo) memorinya penuh gara-gara aplikasi bawaan yang nggak bisa dicopot lewat setelan biasa. Tool desktop ini buat nyopot aplikasi bandel secara massal dan aman lewat ADB, tanpa perlu risiko root.  
`Tauri v2` • `React` • `Android Debug Bridge (ADB)`

### [Windows Optimizer Toolkit](https://github.com/4ntiDandruff/windows-optimizer)
Skrip pembersih file sementara dan penjinak startup Windows.  
Dibuat pakai PowerShell dan Batch murni. Beresin laptop pelanggan yang lemot dalam hitungan detik tanpa perlu pasang aplikasi cleaner pihak ketiga yang malah nyampah iklan.  
`PowerShell` • `Batch` • `Windows Utilities`

### [Auto-Extract Downloads](https://github.com/4ntiDandruff/auto-extract-downloads)
Daemon Linux yang mengekstrak file arsip otomatis begitu selesai diunduh.  
Tiap habis download skema boardview atau file BIOS, arsip zip/rar langsung diekstrak otomatis di background. Jalan di background dengan beban CPU 0% saat siaga, jadi tangan teknisi nggak perlu lepas dari keyboard.  
`POSIX Shell` • `inotify-tools` • `Systemd User Unit`

### [Reverse SSH Tunnel](https://github.com/4ntiDandruff/reverse-ssh-tunnel)
Terowongan remote SSH tembus NAT dengan auto-reconnect.  
Dibuat biar saya bisa remote server dan meja kerja ruko dari mana saja dengan aman, meski koneksi internet ruko pakai IP dinamis atau berada di balik NAT tanpa port forwarding.  
`OpenSSH` • `Bash` • `Watchdog Daemon`

---

## Alat Kerja Sehari-hari

Saya pilih alat kerja yang simpel, transparan, dan nggak banyak tingkah:

* **OS**: Linux (Ubuntu / Debian / Kubuntu). Stabil, enteng, log sistemnya jelas, dan nggak ada proses aneh-aneh di latar belakang.
* **Skrip Otomasi**: Bash & Python. Buat bikin perkakas cepat, pengolah data, dan penghubung antar-layanan.
* **Backend**: Python FastAPI & SQLite. Mudah dirawat, alurnya lurus, dan database SQLite WAL tahan banting kalau mendadak mati lampu di ruko.
* **Tampilan Web**: HTML5, Tailwind CSS, Alpine.js. Tanpa proses build rumit (zero build-step), edit file langsung kelihatan hasilnya di browser.
* **Aplikasi Desktop**: Tauri v2 (Rust). Aplikasi native yang ukurannya kecil, cepat dibuka, dan hemat RAM dibanding Electron.
* **Version Control**: Git & GitHub. Buat nyatet riwayat perubahan dan simpan dokumentasi kerjaan.

---

## Cerita di Balik MEGAPASS

Unit usaha servis yang saya jalankan di Sidoarjo bernama **Megapass Intra Solusindo**:

* **Mega**: Nama istri saya tercinta. Pengingat kenapa saya harus kerja jujur, teliti, dan bertanggung jawab setiap hari.
* **PASS**: Kata paling melegakan di meja teknisi. Kalau instrumen tes sudah menampilkan tulisan **PASS** warna hijau, artinya perangkat yang tadinya mati sudah sembuh total, tegangannya normal, fungsi hardware beres, dan siap diserahkan balik ke pemiliknya.

Prinsip ini yang saya bawa ke semua kerjaan: mau nyolder kaki chip mikro ukuran milimeter atau nulis logika kode program, semuanya dikerjakan seteliti mungkin sampai beneran layak dinyatakan **PASS**.

---

## Sertifikasi Resmi & Pelatihan Hardware

Pemahaman elektronika saya dibangun lewat jalur pelatihan fisik dan uji kompetensi resmi:

* **BNSP (Badan Nasional Sertifikasi Profesi)** — Teknisi Elektronika & Perangkat Keras Ponsel
* **BMY Yogyakarta** — Spesialisasi Analisa Skematik Jalur & Motherboard Laptop
* **ITS Surabaya (PRODISTIK)** — D1 Teknologi Informasi & Dasar Perancangan Sirkuit
* **PTC Indonesia & Arsalabs** — Reparasi Hardware Ponsel Tingkat Lanjut
* **Magistra Utama** — Program Teknisi Komputer & Jaringan

Dokumentasi sertifikat fisik dan portofolio servis ada di: **[megapass.web.id/teknisi](https://megapass.web.id/teknisi/)**

---

<div align="center">

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/Website-megapass.web.id-000?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Website" /></a>
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portofolio-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Teknisi" /></a>
  <a href="https://skill.megapass.web.id"><img src="https://img.shields.io/badge/Portal_Keahlian-skill.megapass.web.id-0071E3?style=for-the-badge&logo=safari&logoColor=white" alt="Skill Portal" /></a>
</p>

**Megapass Intra Solusindo • Sidoarjo, Indonesia**  
*Teknisi Perangkat Keras (BNSP) & Praktisi Otomasi Linux*

</div>
