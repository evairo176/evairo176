<div align="center">

# Dicki Prasetya

**Senior Fullstack Developer** · enterprise systems, data platforms, AI tooling

[![Portfolio](https://img.shields.io/badge/folio.evairo.fun-0e75b6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://folio.evairo.fun)
[![Lab](https://img.shields.io/badge/lab.evairo.fun-1f2937?style=for-the-badge&logo=vercel&logoColor=white)](https://lab.evairo.fun)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dicki-prasetya-3a7587195/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dickiprasetya176@gmail.com)

<img src="https://komarev.com/ghpvc/?username=evairo176&label=views&color=0e75b6&style=flat" alt="profile views" />

</div>

Saya membangun sistem yang dipakai orang setiap hari, bukan purwarupa. Empat tahun terakhir di dunia enterprise: platform komplain multi-cabang, sistem helpdesk dengan SLA, modul voucher, dan POS retail. Fokus saya mengubah workflow bisnis yang berantakan menjadi sistem yang bisa dioperasikan orang non-teknis tanpa pelatihan panjang.

Sekarang **Senior Fullstack Developer di PT Duta Intidaya Tbk (Watsons)**.

---

## Yang sedang saya kerjakan

| Area | Isi |
| --- | --- |
| **Enterprise apps** | ASP.NET Core + React, SQL Server, alur approval berlapis, notifikasi email transaksional |
| **Data platforms** | PostgreSQL, ETL bertahap anti-timeout, staging table, sync incremental |
| **POS & retail** | Offline-first mobile client, sync outbox, event-driven backend, RabbitMQ |
| **DevOps** | Docker Compose, Nginx gateway, Cloudflare Tunnel, IIS subpath deploy, CI via GitHub Actions |

---

## Tech stack

**Backend**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black)

**Data**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Proyek pilihan

### QManager-GO
Dashboard manajemen modem Quectel RM500Q-GL. Baca sinyal, kelola band, atur APN, dan jadwalkan reboot lewat UI web, langsung dari perangkat LTE. Backend Go yang dikompilasi untuk ARMv7 dan berjalan di dalam modem itu sendiri.

`Go` `TypeScript` `React` `ARMv7` `OpenWrt`
→ [evairo176/qmanager](https://github.com/evairo176/qmanager)

### Employee Management
Aplikasi manajemen karyawan dengan Angular 22 dan Tailwind v4. CRUD berlapis, filter per departemen, dan form validasi ketat.

`Angular 22` `TypeScript` `Tailwind v4`
→ [evairo176/employee-management](https://github.com/evairo176/employee-management)

### Go RAG
Pipeline retrieval-augmented generation yang ditulis murni di Go. Chunking dokumen, embedding, dan pencarian vektor tanpa Python di jalur produksi.

`Go` `Vector Search` `LLM`
→ [evairo176/golang_rag](https://github.com/evairo176/golang_rag)

### Portfolio situs
Situs portofolio dua lapis. Versi utama statis penuh untuk kecepatan, versi lab dengan TanStack Router untuk eksperimen UI, artikel, dan data proyek yang dihasilkan saat build.

`Astro` `TanStack Router` `Vite` `Tailwind` `Playwright`
→ [folio.evairo.fun](https://folio.evairo.fun) · [lab.evairo.fun](https://lab.evairo.fun) · [evairo176/folio-astro](https://github.com/evairo176/folio-astro)

### POS Ecosystem
Sistem POS retail dengan backend event-driven dan klien mobile offline-first. Transaksi tercatat lokal, dikirim sebagai outbox, dan direkonsiliasi per batch. Gateway Nginx memisahkan API publik, admin web, dan worker latar.

`Node.js` `Prisma` `PostgreSQL` `RabbitMQ` `React Native` `Docker`
→ endpoint produksi [pos-api.evairo.fun](https://pos-api.evairo.fun/api/v1/health)

---

## Prinsip kerja

**Verifikasi dulu, klaim belakangan.** Kalau saya bilang endpoint jalan, saya sudah memanggilnya. Kalau saya bilang UI sudah di tengah, saya sudah mengukur bounding box-nya.

**Hapus sebelum menambah.** Kode terbaik adalah yang tidak perlu ditulis. Fitur yang tidak dipakai akan dihapus, bukan dikomentari.

**Logika keluar dari komponen.** Komponen hanya merender. Fetch, state, dan perhitungan masuk hook. Satu file satu tanggung jawab.

**Mode gelap itu bukan afterthought.** Kontras, bayangan, dan warna aksen dirancang bersamaan dengan mode terang.

---

## Aktivitas GitHub

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=evairo176&theme=dark&hide_border=true&border_radius=8)](https://git.io/streak-stats)

<img height="160" src="https://github-readme-stats.vercel.app/api?username=evairo176&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=evairo176&layout=compact&theme=dark&hide_border=true&langs_count=8" alt="top languages" />

</div>

---

<div align="center">

Terbuka untuk diskusi seputar sistem enterprise, integrasi data, dan arsitektur backend.

[folio.evairo.fun](https://folio.evairo.fun) · [LinkedIn](https://www.linkedin.com/in/dicki-prasetya-3a7587195/) · [Email](mailto:dickiprasetya176@gmail.com)

</div>
