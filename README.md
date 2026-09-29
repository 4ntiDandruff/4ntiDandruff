<div align="center">

# Hizam Nahari
### Teknisi Elektronika & Pembelajar Software Engineering

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/%5B%20ID%20Indonesia%20%28Utama%29%20%5D-238636?style=for-the-badge&logo=github&logoColor=white" alt="Bahasa Indonesia" /></a>
  <a href="./README.en.md"><img src="https://img.shields.io/badge/%5B%20US%20English%20%5D-0A66C2?style=for-the-badge&logo=github&logoColor=white" alt="English" /></a>
</p>

<p align="center">
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portofolio-megapass.web.id%2Fteknisi-0A66C2?style=flat-square&logo=googlechrome&logoColor=white" alt="Profil Teknisi" /></a>
  <a href="https://github.com/4ntiDandruff/mobile-view"><img src="https://img.shields.io/badge/Ekstensi-Mobile%20View-0071E3?style=flat-square&logo=googlechrome&logoColor=white" alt="Ekstensi Mobile View" /></a>
  <img src="https://img.shields.io/badge/Lokasi-Sidoarjo%2C%20Jawa%20Timur-D32F2F?style=flat-square&logo=googlemaps&logoColor=white" alt="Lokasi" />
  <img src="https://img.shields.io/badge/Sertifikasi-BNSP%20Elektronika-4EAA25?style=flat-square&logo=target&logoColor=white" alt="Tersertifikasi" />
  <img src="https://img.shields.io/badge/Fokus-Belajar%20Software%20%26%20Hardware-blueviolet?style=flat-square" alt="Fokus" />
  <img src="https://komarev.com/ghpvc/?username=4ntiDandruff&style=flat-square&color=0A66C2&label=Profile+Views" alt="Profile Views" />
</p>

---

</div>

## Salam Kenal dari Meja Servis

Halo! Saya **Hizam Nahari**, seorang teknisi elektronika dari Sidoarjo, Jawa Timur. Keseharian saya banyak dihabiskan di meja servis berhadapan dengan solder, multitester, osiloskop, skematik boardview, dan bongkar-pasang komponen laptop maupun ponsel.

Di sela-sela pekerjaan hardware, saya punya ketertarikan besar pada sistem operasi Linux, otomasi pekerjaan ruko, dan saat ini sedang aktif belajar **Software Engineering & Web Development**. 

Bagi saya, logika menelusuri jalur tegangan pada motherboard memiliki kepuasan yang mirip dengan menyusun alur logika pada kode program: sama-sama menuntut ketelitian, kesabaran mencari akar masalah, dan keinginan membuat sistem berjalan stabil serta efisien.

---

### Cerita di Balik Nama `@4ntiDandruff`

Nama **`@4ntiDandruff`** berawal dari analogi sederhana di meja kerja servis:

* **Ketombe di dunia komputer**: Bagi teknisi, "ketombe" adalah tumpukan bloatware, aplikasi sampah bawaan pabrik, dan proses latar belakang yang membuat kipas laptop pelanggan menjerit padahal tidak sedang dipakai berat.
* **Angka 4 (Gaya Leetspeak)**: Menggantikan huruf `A` dengan angka `4` mengikuti kebiasaan lama komunitas open-source agar nama tetap utuh, rapi, dan mudah diketik langsung di terminal.
* **Perkakas Bersih-bersih**: Nama ini dipakai sebagai pengingat untuk selalu membuat skrip dan perkakas yang tujuannya merapikan sistem agar ringan kembali.

<p align="center">
  <img src="https://raw.githubusercontent.com/4ntiDandruff/4ntiDandruff/main/assets/circuit-probing-station.svg?raw=true" width="100%" alt="Automated Circuit Micro-Probing & Debloating Station" />
</p>

---

## Perkakas & Catatan Eksperimen dari Meja Kerja

Repositori di akun ini sebagian besar adalah catatan belajar pribadi dan perkakas bantu sederhana yang saya kembangkan untuk mempermudah pekerjaan servis di ruko:

### [Mobile View Browser Extension](https://github.com/4ntiDandruff/mobile-view)
**Ekstensi Browser Workbench untuk Pratinjau Tampilan Mobile Sekali Klik**
* **Latar Belakang**: Saat belajar membuat tampilan web responsif, membuka inspect element browser (F12) terasa kaku dan tidak mencerminkan wujud fisik layar ponsel yang sesungguhnya.
* **Eksperimen**: Membangun ekstensi browser Chromium Manifest V3 tanpa bundler rumit, lengkap dengan bingkai smartphone presisi dan dev-watcher auto-reload berbasis kernel inotify Linux.
* **Dampak Praktis (*Yang Artinya...*)**: *Memudahkan pengujian tampilan web di layar ponsel langsung dari browser desktop tanpa perlu bolak-balik meraih HP.*  
`JavaScript` • `Chromium Manifest V3` • `Tailwind CSS` • `HTML5`

### [Windows Optimizer Toolkit](https://github.com/4ntiDandruff/windows-optimizer)
**Kumpulan Skrip Pembersih Sistem Sederhana untuk PC Pelanggan**
* **Latar Belakang**: Banyak laptop pelanggan ruko melambat karena tumpukan cache dan aplikasi bawaan pabrik yang tidak terpakai.
* **Eksperimen**: Menyatukan skrip native PowerShell dan Batch untuk membersihkan file sementara dan menonaktifkan startup yang tidak perlu secara aman.
* **Dampak Praktis (*Yang Artinya...*)**: *Membantu proses servis rutin lebih teratur tanpa perlu mengunduh aplikasi pembersih asing.*  
`PowerShell` • `Batch` • `Windows Utilities`

### [CH341A BIOS Flasher Tauri](https://github.com/4ntiDandruff/CH341A-BIOS-Flasher-Tauri)
**Antarmuka Desktop Sederhana untuk Alat Flash EEPROM USB**
* **Latar Belakang**: Membaca dan menulis chip BIOS fisik menggunakan terminal Linux terkadang butuh pengetikan perintah yang cukup panjang.
* **Eksperimen**: Belajar membuat antarmuka visual sederhana berbasis Tauri v2 untuk menjalankan utilitas `flashrom` dengan tombol yang jelas.
* **Dampak Praktis (*Yang Artinya...*)**: *Memudahkan pengecekan tipe chip dan file backup BIOS sebelum disolder kembali.*  
`Tauri v2` • `Rust` • `TypeScript` • `flashrom`

### [Auto-Extract Downloads for Linux](https://github.com/4ntiDandruff/auto-extract-downloads)
**Skrip Ekstraksi Arsip Otomatis Berbasis Event Kernel**
* **Latar Belakang**: Sering mengunduh file skematik boardview dan driver dalam bentuk arsip zip/rar saat bekerja di Linux.
* **Eksperimen**: Menggunakan utilitas `inotify` agar sistem mendeteksi saat file unduhan selesai dan otomatis mengekstraknya tanpa perlu klik kanan berulang kali.
* **Dampak Praktis (*Yang Artinya...*)**: *Arsip skematik langsung siap dibuka di layar tanpa mengganggu alur kerja.*  
`POSIX Shell` • `inotify-tools` • `Systemd User Unit`

### [ADB Mobile Debloater](https://github.com/4ntiDandruff/adb-uninstaller)
**Eksperimen Tampilan Manajemen Aplikasi Android via USB**
* **Latar Belakang**: Membantu pelanggan menghemat penyimpanan ponsel yang penuh dengan aplikasi bawaan yang tidak bisa dicopot biasa.
* **Eksperimen**: Membuat tampilan grafis sederhana berbasis ADB dengan daftar paket aplikasi yang aman untuk dinonaktifkan.
* **Dampak Praktis (*Yang Artinya...*)**: *Membantu merapikan penyimpanan ponsel pelanggan secara terarah.*  
`Tauri v2` • `TypeScript` • `Android Debug Bridge (ADB)`

---

## Teknologi & Alat yang Sedang Dipelajari

Setiap alat yang saya pelajari dipilih karena kepraktisannya untuk kebutuhan nyata di meja kerja:

| Bidang | Alat | Alasan & Manfaat di Meja Belajar |
|---|---|---|
| **Sistem Operasi** | Linux (Ubuntu / Debian) | *Stabil, transparan, dan sangat ramah untuk memahami cara kerja sistem komputer.* |
| **Bahasa Skrip** | Bash / Shell & Python | *Cepat untuk membuat skrip pembantu kerja harian dan otomasi tugas rutin.* |
| **Backend & Web** | Python FastAPI & SQLite | *Alur kodenya lugas, mudah dibaca, dan database SQLite WAL sangat praktis tanpa instalasi rumit.* |
| **Tampilan Web** | HTML5, Tailwind CSS, Alpine.js | *Bisa langsung dipelajari dan diuji di browser tanpa proses build yang berat.* |
| **Version Control** | Git & GitHub | *Membantu mencatat riwayat perubahan kode dan belajar kolaborasi secara rapi.* |

---

## Kisah di Balik Nama MEGAPASS

Usaha servis yang saya jalankan di Sidoarjo bernama **Megapass Intra Solusindo**. Nama ini memiliki arti personal bagi saya:

* **Mega**: Nama panggilan istri tercinta, pengingat alasan untuk terus berusaha dan bertanggung jawab.
* **PASS**: Kata yang paling membahagiakan bagi teknisi. Tulisan **PASS** berlatar hijau adalah tanda bahwa perangkat yang rusak sudah sembuh, seluruh fungsi hardware lolos uji, dan siap diserahkan kembali kepada pemiliknya.

Filosofi ini yang saya pegang: setiap pekerjaan, baik solderan fisik maupun baris kode, dikerjakan dengan sungguh-sungguh hingga layak dinyatakan **PASS**.

---

## Riwayat Pelatihan & Sertifikasi Hardware

Dasar pemahaman teknis saya dibangun melalui pendidikan dan pelatihan terstruktur di bidang elektronika dan komputer:

* **BNSP (Badan Nasional Sertifikasi Profesi)** - Sertifikasi Kompetensi Teknisi Elektronika & Ponsel
* **BMY Yogyakarta** - Pelatihan Diagnosa Skematik & Motherboard Laptop
* **ITS Surabaya (PRODISTIK)** - D1 Teknologi Informasi & Dasar Sirkuit
* **PTC Indonesia & Arsalabs** - Pelatihan Perbaikan Perangkat Keras Ponsel
* **Magistra Utama** - Program Teknisi Komputer & Jaringan

Dokumentasi sertifikat dan kegiatan teknisi dapat dilihat di: **[megapass.web.id/teknisi](https://megapass.web.id/teknisi/)**

---

<div align="center">

<p align="center">
  <a href="https://megapass.web.id"><img src="https://img.shields.io/badge/Website-megapass.web.id-000?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Website" /></a>
  <a href="https://megapass.web.id/teknisi/"><img src="https://img.shields.io/badge/Portofolio-megapass.web.id%2Fteknisi-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Teknisi" /></a>
</p>

**Megapass Intra Solusindo • Sidoarjo, Indonesia**  
*Teknisi Elektronika & Pembelajar Software Engineering*

</div>