# AI Framework: Deep Health Diagnosis Framework (DHDF)

![License](https://img.shields.io/github/license/gorilaxxx/ai-framework-deep-health)
![Last Commit](https://img.shields.io/github/last-commit/gorilaxxx/ai-framework-deep-health)
![Contributors](https://img.shields.io/github/contributors/gorilaxxx/ai-framework-deep-health)
![Issues](https://img.shields.io/github/issues/gorilaxxx/ai-framework-deep-health)
![Stars](https://img.shields.io/github/stars/gorilaxxx/ai-framework-deep-health)

**Versi:** v1.0  
**Status:** Dalam Pengembangan  
**Repositori:** `ai-framework-deep-health`  
**Penulis:** [@gorilaxxx](https://github.com/gorilaxxx)

---

## Overview

**Deep Health Diagnosis Framework (DHDF)** adalah kerangka kerja diagnosis kesehatan berbasis AI yang terstruktur dan interaktif.  
Framework ini dirancang untuk membantu proses diagnosis medis melalui pendekatan sistematis, validasi bertahap, dan kontrol berbasis iterasi.

Framework ini cocok digunakan oleh:
- Developer AI yang membangun sistem diagnosis berbasis prompt
- Praktisi IT dan HealthTech
- Peneliti di bidang medis dan teknologi AI

---

## Core Principles

Prinsip utama yang menjadi fondasi kerja dari DHDF:

- **Modular & Iteratif:** Diagnosis dilakukan dalam 10 tahap interaktif dan bertingkat.
- **Validasi Ganda:** Sebelum diagnosis dan rekomendasi keluar, sistem akan melakukan verifikasi internal 2–3 kali.
- **Legal-Aware:** Disesuaikan dengan regulasi kesehatan lokal (berbasis Indonesia sebagai baseline awal).
- **Context-Efficient:** Mendukung versi ringkas (compact) untuk model AI dengan keterbatasan context window/token.

---

## File Structure

```bash
/ai-framework-deep-health/
├── dhdf-v1.md              # Versi utama DHDF
├── dhdf-compact-v1.md      # Versi ringan (compact mode)
├── dhdf-flowchart.mmd      # Diagram alur (mermaid)
└── examples/
    ├── flu-diagnosis.md    # Contoh kasus diagnosis flu
    └── stomach-pain.md     # Contoh kasus diagnosis sakit perut

---

## How to Use

Contoh penggunaan prompt pada chatGPT:
***
"AI Health: Pasien mengeluh demam, batuk, dan pegal-pegal selama 3 hari terakhir. Tolong bantu diagnosis awal."
***

Langkah penggunaan:

1. Ambil URL raw file dari GitHub:
https://raw.githubusercontent.com/gorilaxxx/ai-framework-deep-health/main/dhdf-v1.md


2. Masukkan ke dalam prompt atau tetapkan sebagai referensi awal.


3. AI akan mengikuti struktur dan mekanisme DHDF secara otomatis.

---

## Activation

Untuk mengaktifkan DHDF secara otomatis di dalam sistem AI yang mendukung pre-prompting, gunakan kata kunci:

"AI Health:"

Pastikan file `dhdf-v1.md` telah dimuat sebelumnya ke dalam konteks.

---

## License

Proyek ini dilisensikan di bawah MIT License. Lihat file LICENSE untuk detail.

---

## Disclaimer

Framework ini disusun untuk keperluan edukasi, prototyping, dan riset.
Tidak dimaksudkan untuk menggantikan diagnosis medis oleh tenaga kesehatan profesional.
Penggunaan framework menjadi tanggung jawab penuh masing-masing pengguna.
---

## Ownership & Originality

Framework ini — Deep Health Diagnosis Framework (DHDF) — pertama kali dikonsep dan dikembangkan oleh @gorilaxxx.

Seluruh struktur, file, dan ide yang ada di dalam repositori ini terdokumentasi secara publik sejak April 2025.
Setiap penggunaan, rujukan, atau pengembangan lanjutan wajib mencantumkan sumber aslinya.

Untuk kolaborasi atau pertanyaan, silakan hubungi via GitHub atau buka issue.

---