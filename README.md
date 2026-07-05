# 🩺 LexiMed.ai — Large Language Model Clinical Decision Support System (CDSS)

> **Enterprise Health Orchestration System** > *Transforming Clinical Data Into Smart, Regulated, and Secure Medical Decisions.*

---

## 🚀 Repositori & Tautan Live Project

* **Official Production App (Frontend):** [https://www.leximedai.web.id/](https://www.leximedai.web.id/)
* **Official Backend API Gateway:** [https://lexi-med-ai-llm-rs-back-end.vercel.app/api](https://lexi-med-ai-llm-rs-back-end.vercel.app/api)
* **Production Database Engine:** Supabase PostgreSQL Cloud Cluster (`rs_uns_db`)
* **GitHub Repository:** [https://github.com/Iham93/Leximed.ai-Olivia-2026.git](https://github.com/Iham93/Leximed.ai-Olivia-2026.git)

---

## 👥 Tim Pengembang & Struktur Otoritas

* **Institusi:** D3 Teknik Informatika — PSDKU Sekolah Vokasi, Universitas Sebelas Maret (UNS) Madiun  

### 👨‍💻 Susunan Anggota Tim

| Nama Lengkap | NIM | Peran / Hak Akses Teknis |
| :--- | :--- | :--- |
| **Ilham Eka Saputra** | V3924005 | Anggota / Full-Stack Developer & AI Integration Lead |

* **Dosen Pembimbing:** Darmawan Lahru, S.Kom., M.MT  
* **NIP:** 1991091420200801

---

## 🔑 Kredensial Akses Sistem (Testing & Demo Juri)

> ⚠️ **PENTING — INFORMASI KATA SANDI UNIVERSAL:** > Untuk mempermudah proses pengujian, evaluasi, dan simulasi komprehensif oleh Dewan Juri secara lintas halaman otonom, **SELURUH AKUN PENGGUNA (13 Personil Medis)** di bawah ini telah dikunci menggunakan kata sandi massal yang sama, yaitu:  
> * KATA SANDI / PASSWORD UNIVERSAL: **`password`**

### 📋 Tabel Kredensial HIS Supabase Link (13 Personil Terdaftar)

| NIP / ID (Username) | Nama Lengkap | Role / Hak Akses | Ruang Lingkup Sistem & Unit Fungsionalitas | Password Akses | Status Akun |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **admin** | Super Admin | **ADMIN** | Audit Trail, User CRUD, RAG Vector Knowledge Injection | `password` | 🟢 Permenkes Aktif |
| **ADMIN-2** | Ilham A-2 | **ADMIN** | Manajemen Konfigurasi Cloud Node & Failover Interceptor | `password` | 🟢 Permenkes Aktif |
| **dr_tirta** | Dr. Tirta Mandira S. ARS | **DOKTER** | Clinical CDSS Workstation, Anti-Hallucination Core | `password` | 🟢 Permenkes Aktif |
| **dr_budi** | Dr. Budi Setiawan, Sp.PD | **DOKTER** | Clinical CDSS Partner — Poli Penyakit Dalam | `password` | 🟢 Permenkes Aktif |
| **dr_susi** | Dr. Susi Susanti, Sp.JP | **DOKTER** | Clinical CDSS Partner — Poli Jantung | `password` | 🟢 Permenkes Aktif |
| **dr_andi** | Dr. Andi Wijaya, Sp.S | **DOKTER** | Clinical CDSS Partner — Poli Saraf | `password` | 🟢 Permenkes Aktif |
| **PERAWAT-1** | Aisyah N. I. P. | **PERAWAT** | Handover Shift Dashboard, SOAP Summary & Diagnostics | `password` | 🟢 Permenkes Aktif |
| **RADIOLOGI-01** | Ilham Eka S. | **RADIOLOGI** | PACS DICOM Workstation & Gemini Vision AI Multimodal | `password` | 🟢 Permenkes Aktif |
| **MANAJEMEN-1** | M. Akyas F. | **MANAJEMEN** | Executive Command Center, BOR & Sebaran Tren Penyakit | `password` | 🟢 Permenkes Aktif |
| **ASISTEN-1** | Dr Tirta Asisten | **ASISTEN** | Loket Triage Awal, Input Metrik TTV & Keluhan Utama | `password` | 🟢 Permenkes Aktif |
| **asisten_budi** | Soni Asisten Dr. Budi | **ASISTEN** | Registrasi Klinis Pasien — Poli Penyakit Dalam | `password` | 🟢 Permenkes Aktif |
| **asisten_susi** | Sinta Asisten Dr. Susi | **ASISTEN** | Registrasi Klinis Pasien — Poli Jantung | `password` | 🟢 Permenkes Aktif |
| **asisten_andi** | Doni Asisten Dr. Andi | **ASISTEN** | Registrasi Klinis Pasien — Poli Saraf | `password` | 🟢 Permenkes Aktif |

---

## 🎯 Tinjauan Masalah Lapangan & Sasaran Solusi

LexiMed.ai hadir untuk memitigasi kendala operasional administratif dan teknologis pada fasilitas kesehatan berdasarkan data sekunder yang tervalidasi:

1.  **Beban Dokumentasi Manual:** Menyita hingga 40% waktu kerja tenaga klinis secara berulang, sehingga mereduksi jam interaksi esensial bersama pasien langsung di ruang rawat.
2.  **Halusinasi AI & Risiko Kesalahan Medis:** Adanya celah kerentanan penyimpulan data fiktif (*hallucination*) pada implementasi rekam medis elektronik konvensional jika tidak dikawal sirkuit pembatas yang ketat.
3.  **Resistensi Adopsi Teknologi Baru:** Kurva pembelajaran yang rumit dan faktor kegagalan *usability* sistem memicu tingginya penolakan integrasi digital oleh para staf medis.
4.  **Amanat Kepatuhan Hukum Nasional:** Tuntutan pemenuhan regulasi transaksional Rekam Medis Elektronik (RME) yang menyeluruh di seluruh faskes wilayah sesuai ketentuan **Permenkes No. 24 Tahun 2022**.
5.  **Isolasi Informasi Klinis (Silo Data):** Terputusnya sirkuit alur data antar unit departemen kesehatan (Poliklinik, Perawat, Radiologi, Farmasi) yang memperlambat penegakan asuhan medis.

---

## ⚙️ Enterprise Core Infrastructure (Stack Teknologi)

### 🖥️ Frontend Layer (Client-Side Component)
* **Framework Inti:** React.js 18 & Vite Build System (Compiler ultra-cepat)
* **Styling Engine:** Tailwind CSS & Glassmorphism Premium Layout
* **Motion Engine:** Framer Motion (Transisi staggered micro-animation sinematik)
* **Routing Gateway:** React Router v6

### 🖥️ Backend & Database Layer (Server-Side Component)
* **API Framework:** Laravel 11 API Architecture
* **Security Token:** Laravel Sanctum Token-Based Authentication Engine
* **Database Cloud Engine:** Supabase PostgreSQL Serverless Cluster (`rs_uns_db`)
* **Model Relasional:** Eloquent ORM & REST JSON Endpoint Gateways

### 🧠 Hybrid Intelligence AI Stack (Dual-Engine Redundancy Model)
* **Core LLM Processing:** Groq SDK — Llama 3.3 70B (Kecepatan sub-detik untuk teks medis terstruktur)
* **Multimodal Image Intelligence:** Gemini 1.5 Flash Vision AI (Mengekstrak berkas citra medis PACS DICOM)
* **Orchestrator Node:** VoltAgent Orchestrator Pipeline (Context-aware manager untuk membaca cache localStorage pasien)
* **Knowledge Retrieval Engine:** RAG Knowledge Vector Base (Pencarian dokumen Pedoman Praktik Klinis / SOP)
* **Middleware Ingestion:** OpenClaw Layer Framework (Menjaga keandalan request massal dari client ke API Laravel)

---

## 🔄 Cara Kerja Alur Kerja Sistem (Human-in-the-Loop)

Untuk mensimulasikan keandalan sistem RME LexiMed.ai, kami menyarankan Dewan Juri mengikuti **Urutan Pengujian Klinis (Workflow Flow)** lintas halaman otonom berikut:

### 1. Node Admin (Kunci Konfigurasi Awal)
* **Aksi:** Login sebagai `admin` | Password: `password`
* **Cara Kerja:** Admin mengelola data kredensial staf medis (CRUD) dan melakukan injeksi berkas SOP Medis/PPK baru ke dalam RAG Knowledge Base untuk memelihara memori jangka panjang AI dan membasmi halusinasi teks model.

### 2. Node Asisten (Registrasi & Triage Pasien)
* **Aksi:** Login sebagai `ASISTEN-1` | Password: `password`
* **Cara Kerja:** Menginput identitas pasien baru (atau klik Berobat Ulang pada daftar master historis pasien lintas minggu). Sistem otomatis melakukan auto-detect pemetaan poliklinik asal dokter DPJP tanpa dropdown manual.

### 3. Node Radiologi (PACS / Citra Medis Multimodal)
* **Aksi:** Login sebagai `RADIOLOGI-01` | Password: `password`
* **Cara Kerja:** Radiolog menerima rujukan instruksi pemeriksaan secara terintegrasi dari modul dokter. Radiolog mengunggah file citra rontgen pasien. Gemini 1.5 Flash Vision AI otomatis memindai gambar dan menyusun draf impresi radiologi objektif.

### 4. Node Perawat (TTV Tambahan & Handover Shift Otomatis)
* **Aksi:** Login sebagai `PERAWAT-1` | Password: `password`
* **Cara Kerja:** Perawat menginput data vitalis lanjutan. Modul ini mengotomatisasi dokumen Handover Shift (Timbang Terima) keperawatan secara terstruktur (SOAP) menggunakan kecerdasan buatan, menghilangkan kebutuhan menulis ulang laporan saat pergantian shift jaga.

### 5. Node Dokter (Clinical Decision Support System / CDSS)
* **Aksi:** Login sebagai `DOKTER-1` | Password: `password`
* **Cara Kerja:** Dokter poliklinik mengunci konteks pasien aktif. Mesin AI (Groq Llama 3.3) membaca riwayat klinis dan menyusun draf diagnosis awal serta menerbitkan 3 pertanyaan anamnesa verifikasi (Guardrail Anti-Halusinasi). Dokter melakukan validasi akhir, mengeksekusi penalaran kognitif RAG terikat pedoman pelayanan klinis, lalu menerbitkan Resume Medis (*Discharge Summary*) dalam satu klik.

### 6. Node Manajemen (Executive Command Center)
* **Aksi:** Login sebagai `MANAJEMEN-1` | Password: `password`
* **Cara Kerja:** Direksi rumah sakit memantau data agregat performa operasional faskes, tren demografi penyakit harian, serta visualisasi Bed Occupancy Rate (BOR) secara real-time untuk keperluan rapat kebijakan manajemen strategis.

---

## 🛠️ Panduan Instalasi Lokal (Local Development Setup)

### Langkah 1: Kloning Repositori Proyek
Buka terminal PowerShell Anda, lalu unduh berkas repositori proyek monorepo utama:
```bash
git clone [https://github.com/Iham93/Leximed.ai-Olivia-2026.git](https://github.com/Iham93/Leximed.ai-Olivia-2026.git)
cd Leximed.ai-Olivia-2026

```

### Langkah 2: Konfigurasi Core API Backend (Laravel 11)

Arahkan direktori terminal menuju subfolder backend:

```bash
cd llm-Rs-Leximed.ai-Backend
composer install
cp .env.example .env
php artisan key:generate

```

> 🌐 **Catatan Konfigurasi Basis Data:** Buka file `.env` menggunakan VS Code. Konfigurasikan kredensial koneksi database PostgreSQL Supabase Anda pada parameter `DB_HOST`, `DB_DATABASE`, `DB_USERNAME`, dan `DB_PASSWORD`. Masukkan token `GROQ_API_KEY` Anda.

Setelah konfigurasi environment selesai, jalankan perintah migrasi tabel:

```bash
php artisan migrate --seed
php artisan serve

```

Backend lokal Anda akan berjalan normal pada port default: `http://127.0.0.1:8000`

### Langkah 3: Konfigurasi Workstation Frontend (React + Vite)

Buka terminal PowerShell baru, lalu masuk ke direktori subfolder client frontend:

```bash
cd ../llm-Rs-Leximed.ai-Frontend
npm install
cp .env.example .env

```

Buka file `.env` di folder frontend tersebut, lalu arahkan endpoint ke server Laravel lokal Anda:

```env
VITE_API_URL="http://localhost:8000/api"
VITE_APP_NAME="LexiMed.ai Digital Assistant (Lokal)"

```

Nyalakan server development lokal frontend menggunakan instruksi compiler Vite:

```bash
npm run dev

```

Buka browser dan akses aplikasi Anda di alamat `http://localhost:5173/`. Lakukan Hard Refresh (`Ctrl + F5`) untuk membersihkan cache browser.

---

## 📚 Tinjauan Literatur & Landasan Jurnal Ilmiah

Pengembangan arsitektur kecerdasan buatan LexiMed.ai didasari secara kokoh oleh 9 Jurnal Terverifikasi guna menjamin keamanan bioetika medis dan validitas sistem:

1. **Kurnia, J. A.:** *Tantangan Penerapan AI dalam Manajemen Rumah Sakit*. Landasan utama pemetaan tantangan riil kecerdasan faskes nasional (data tidak terstruktur dan kelemahan infrastruktur digital).
2. **Singhal et al. (2023):** *Large Language Models Encode Clinical Knowledge*. Bukti empiris kapabilitas model bahasa besar generasi terkini dalam menyandikan pengetahuan klinis setingkat pakar medis.
3. **Wornow et al.:** *Refining the Foundations of LLM for EHR*. Landasan kritis risiko halusinasi data klinis pada rekam medis elektronik, menjadi alasan utama LexiMed merancang sistem pengaman Dual-AI Redundancy Engine.
4. **Gao et al.:** *Retrieval-Augmented Generation for Large Language Models*. Fondasi implementasi teknis arsitektur RAG untuk mengunci penalaran AI berbasis dokumen basis pengetahuan eksternal lokal (SOP / PPK).
5. **Permenkes RI No. 24 Tahun 2022:** Payung hukum regulasi nasional yang mewajibkan seluruh fasilitas pelayanan kesehatan di Indonesia mengimplementasikan Rekam Medis Elektronik (RME).
6. **JUTEKOM (2026):** *Transformasi Sistem Informasi Menjadi Sistem Cerdas*. Cetak biru migrasi sistem informasi rumah sakit (SIMRS) konvensional pasif menjadi sistem cerdas pengambil keputusan yang adaptif.
7. **Orfanou et al. (2015):** *Usability Evaluation of the System Usability Scale*. Instrumen standardisasi metodologi pengujian kegunaan antarmuka web (skor target SUS ≥85 untuk kategori Excellent Workstation) guna menjamin kemudahan pemakaian sistem oleh nakes.
8. **Dietler et al. (2019):** *Health in the 2030 Agenda for Sustainable Development*. Landasan makro kontribusi sistem LexiMed.ai dalam menyukseskan target global SDGs poin 3 (Good Health and Well-Being).
9. **GPT-4 Technical Report (2023):** Tolok ukur (*benchmark*) kapabilitas model AI generatif dalam memproses penalaran data medis multimodal secara aman.

---

LexiMed.ai — "Transforming Clinical Data Into Smart Medical Decisions." © 2026 Team UNS Madiun Web Technology Competition Project. All Rights Reserved.

```

```
