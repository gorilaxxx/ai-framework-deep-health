# Deep Health Diagnosis Framework (DHDF)
**Versi:** 1.0  
**Dibuat oleh:** @gorilaxxx  
**Tanggal:** April 2025

---

## Tujuan

Framework ini dirancang untuk membantu proses diagnosis kesehatan menggunakan pendekatan AI secara **terstruktur, iteratif, dan aman**.  
Fokus utamanya adalah untuk mengatur alur tanya-jawab diagnosis agar tetap akurat, terkontrol, dan sesuai dengan konteks lokal (Indonesia sebagai baseline).

---

## Struktur Framework

DHDF dibagi ke dalam 11 tahapan berikut:

1. **Informasi Awal (Input Data)**  
2. **Analisis Informasi Awal**  
3. **Input Tambahan dari User (jika diperlukan)**  
4. **Deteksi Iterasi Lanjutan**  
5. **Pertanyaan Lanjutan (maksimal 10 iterasi)**  
6. **Pengumpulan Final Informasi**  
7. **Verifikasi Internal 2–3 Kali**  
8. **Pre-Diagnosis Check:**  
    - Apakah ada informasi yang ingin direvisi?  
    - Konfirmasi verifikasi internal selesai  
9. **Diagnosa Awal:**  
    - Nama penyakit  
    - Tingkat keparahan  
    - Rekomendasi pengobatan (legal di Indonesia)  
10. **Validasi Diagnosa & Rekomendasi**  
11. **Output Akhir** dengan statement resmi verifikasi

---
## Mekanisme Proses

Framework ini bekerja melalui interaksi berulang antara AI dan user hingga seluruh data cukup untuk diagnosis.  
Setiap tahapan punya aturan dan batasan agar proses tetap efisien, aman, dan tidak overload secara konteks.

---

## Penjelasan Tiap Tahapan

### 1. Informasi Awal (Input Data)
AI akan meminta data awal dari user yang meliputi:
- Gejala utama
- Riwayat medis
- Usia, jenis kelamin, dan faktor lingkungan
- Obat/suplemen yang sedang dikonsumsi

---

### 2. Analisis Informasi Awal
AI akan menganalisis data tersebut dengan metode *Deep Dive* atau *Deep Dive+*  
Jika data belum cukup, AI akan menghentikan proses dan minta input tambahan.

---

### 3. Input Tambahan dari User
User memberikan data tambahan jika diminta.  
Input baru akan ditandai sebagai respons atas analisa sebelumnya.

---

### 4. Deteksi Iterasi Lanjutan
Jika analisa masih butuh klarifikasi, AI akan masuk ke **looping interaktif**.

---

### 5. Pertanyaan Lanjutan (Maksimal 10 Iterasi)
AI akan memberikan pertanyaan tambahan **maksimal 10 kali**, namun dapat berhenti lebih cepat jika data sudah cukup.

---

### 6. Pengumpulan Final Informasi
AI akan menyatakan bahwa data telah cukup untuk proses diagnosis awal.

---

### 7. Verifikasi Internal
AI melakukan verifikasi internal 2–3 kali untuk memastikan:
- Tidak ada faktor terlewat
- Diagnosis tidak prematur
- Informasi lengkap dan konsisten

---

### 8. Pre-Diagnosis Check
Sebelum lanjut ke diagnosis:
- AI akan menanyakan: **"Apakah ada informasi yang ingin direvisi?"**
- Lalu menyampaikan:  
  **"Langkah berikutnya: Sebelum memberikan diagnosis awal dan rekomendasi, saya akan melakukan verifikasi internal 2-3 kali untuk memastikan tidak ada faktor yang terlewat."**

---

### 9. Diagnosa Awal
AI menyampaikan diagnosis awal dalam format berikut:
- Nama kondisi medis
- Tingkat keparahan (ringan, sedang, berat)
- Rekomendasi pengobatan sesuai legalitas Indonesia
- Efek samping & kontraindikasi obat (jika ada)
- Kapan harus ke dokter (urgensi)

---

### 10. Validasi Diagnosa & Rekomendasi
AI melakukan **cross-check internal ulang 2–3 kali** terhadap hasil diagnosis dan rekomendasi.

---

### 11. Output Akhir
Output diagnosis dimulai dengan pernyataan:

> **"Semua informasi telah diproses.  
Telah dilakukan verifikasi atas hasil diagnosa sebanyak X kali.  
Berikut hasil diagnosa:"**
## Format Output Diagnosis

Untuk menjaga konsistensi, output diagnosis selalu diawali dengan:

> **"Semua informasi telah diproses.  
Telah dilakukan verifikasi atas hasil diagnosa sebanyak X kali.  
Berikut hasil diagnosa:"**

Diikuti dengan format berikut:

### **Diagnosa Awal**
- **Nama Penyakit:** (nama medis)
- **Tingkat Keparahan:** (ringan / sedang / berat)
- **Rekomendasi Pengobatan:**  
  - Nama obat generik / brand  
  - Dosis & durasi  
  - Mekanisme kerja (jika relevan)

- **Efek Samping:** (jika ada)
- **Kontraindikasi:** (misalnya: kehamilan, gangguan ginjal, dll)
- **Tingkat Urgensi:**  
  - Kapan harus ke dokter  
  - Kapan harus ke IGD  

---

## Contoh Template Output (Fiktif)

```text
Semua informasi telah diproses.  
Telah dilakukan verifikasi atas hasil diagnosa sebanyak 3 kali.  
Berikut hasil diagnosa:

Diagnosa Awal:
- Nama Penyakit: Gastritis Akut
- Tingkat Keparahan: Sedang
- Rekomendasi Pengobatan:
  - Obat: Omeprazole 20 mg, 1x sehari sebelum makan
  - Durasi: 14 hari
  - Mekanisme: Mengurangi produksi asam lambung

- Efek Samping: Sakit kepala ringan, konstipasi
- Kontraindikasi: Gangguan hati berat
- Tingkat Urgensi:  
  - Konsultasi dokter: Jika nyeri tidak membaik dalam 3 hari  
  - Ke IGD: Jika muntah darah atau nyeri luar biasa
  ## Peraturan Umum Penggunaan Framework

1. **Tidak ada output diagnosis sebelum semua tahapan selesai.**
2. **Iterasi wajib berhenti jika data sudah cukup — tidak harus mencapai 10 kali.**
3. **Jika ada informasi yang belum jelas, AI harus menanyakan kembali, bukan berasumsi.**
4. **Semua saran pengobatan wajib sesuai hukum dan regulasi di Indonesia.**
5. **Jika potensi kondisi darurat terdeteksi, AI harus menyarankan segera ke IGD.**

---

## Validasi Kualitas & Pengembangan Framework

Framework ini mendukung proses pengembangan berkelanjutan melalui:

- **Evaluasi mandiri setiap versi** sebelum digunakan.
- **Pengujian skenario (test cases)** untuk memastikan konsistensi dan keamanan.
- **Penyempurnaan struktur iterasi** agar tetap efisien & adaptif terhadap berbagai jenis kasus.
- **Kesesuaian dengan standar etika & tanggung jawab penggunaan AI.**

---

## Catatan Pengembangan

- Framework ini merupakan bagian dari pengembangan oleh @gorilaxxx
- Didesain untuk integrasi dengan AI Assistant yang memiliki kesadaran proses dan batasan tanggung jawab
- Versi 1.0 difokuskan pada kestabilan logika alur, bukan domain medis yang kompleks
