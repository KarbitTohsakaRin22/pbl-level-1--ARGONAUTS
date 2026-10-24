# **WS04: Problem Identification & Scope**

**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Fase Learning Spine**: **Fase 2 — Frame (Problem Discovery & Scope)**  
**Minggu / Alokasi Waktu**: Minggu 2 / 14 Jam Belajar  
**Sub-CPMK / SFIA**: S-01.1 (Introduce - Problem Framing) | SFIA BUSA L1 (_Business Analysis_), IRMG L1  
**Penanggung Jawab Fase**: **Phase Lead 2 (Frame — Mahasiswa B)**  
**Keterkaitan Deliverable**: Sumber Utama Penyusunan **Deliverable D1 (Problem Brief - TPL-01)**

## **1\. Identifikasi Tim & Objek Proyek**

| **Elemen Informasi**          | **Rincian Identitas Kelompok & Mitra**     |
| ----------------------------- | ------------------------------------------ |
| **Nama Kelompok / Kelas**     | \[ Argonaut / A \]                         |
| **Phase Lead 2 (Frame - M2)** | \[ Yudo Rahman Badrakusuma — 2600016021 \] |
| **Nama UMKM Mitra Lapangan**  | \[ Perpustakaan Sd Muhammadiyah Nitikan \] |
| **Pemilik / Kontak Mitra**    | \[ Yunistia Sekar Sarworini, S.I.P \]      |

## **2\. Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)**

Gunakan temuan kuantitatif dari WS03 untuk memisahkan antara **Gejala Permukaan (_Symptoms_)** dan **Akar Masalah Utama (_Root Cause_)** operasional bisnis mitra:

| **No** | **Kategori Observasi**            | **Gejala Permukaan (_Symptoms_)**                                                                              | **Akar Masalah Operasional (_Root Cause_)**                                                   | **Bukti Kuantitatif (_Baseline Data_)**         |
| ------ | --------------------------------- | -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| **1**  | **Proses Proses peminjaman buku** | Pihak perpustakaan Mengelolah buku Menggunakan Aplikasi Ibra agar Pihak perpustakaan Tahu buku yang Menghilang | Anak anak lebih tertarik Dengan buku Ilustrasi/bergambar Seperti Komik Indonesia Ensikiopedia | Rata-rata waktu Transaksi = **15 Detik/orang**. |
| **2**  | **Pengelolaan Stok Buku**         | Pihak perpustakaan Kurang nya tenaga Kerja di Perpustakaan                                                     | Anak anak sering Meminjam buku di Perpustakaan tetapi buku Selalu hilang saat Peminjaman      | Selisih stok rata-Rata **0,5% per Bulan**.      |
| **3**  | **Rekapitulasi Stok Buku**        | Pihak perpustakaan Tidak mendapatkan Bantuan dari pihak Lain                                                   | Pihak perpustakaan Salah mencatat saat ada Pinjaman buku                                      | Durasi rekap Harian = **30–60 Menit/malam**.    |

## **3\. Perumusan Problem Statement Kontekstual**

Berdasarkan analisis di atas, rumuskan **Problem Statement** utama dalam 1–2 paragraf terstruktur.  
_Petunjuk_: Hindari mendefinisikan masalah sebagai _"Mitra belum memiliki aplikasi Python/komputer"_. Definisikan dari hambatan bisnis nyata mitra!

**Rumusan Problem Statement Kelompok**:  
_"Pencatatan transaksi dan inventaris yang masih dilakukan secara manual menggunakan buku kertas nota di \[Nama UMKM Mitra\] (kondisi As-Is) menyebabkan bottleneck operasional berupa waktu transaksi kasir yang lambat (90 detik/pelanggan), keterlambatan pemesanan ulang stok akibat selisih stok 12% per bulan, serta waktu rekapitulasi harian pemilik usaha yang memakan waktu hingga 1,5 jam setiap malam. Kondisi ini menghambat efisiensi operasional dan potensi pertumbuhan omzet mitra."_

## **4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (_Scope Creep_) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (_In-Scope_)** dan apa yang **Di Luar Cakupan (_Out-of-Scope_)**:

 ┌───────────────────────────────────────────┐

│ SYSTEM BOUNDARY (BATASAN SISTEM) │

│ │

│ \[ IN-SCOPE: Fitur yang Akan Dibangun \] │

│ 1. Pencatatan transaksi kasir berbasis konsol (CLI). │

│ 2. Pengurangan stok otomatis setiap transaksi berhasil. │

│ 3. Pencetakan ringkasan rekapitulasi harian untuk pemilik. │

│ │

│─────────────────────────────────────────── │

│ │

│ \[ OUT-OF-SCOPE: Di Luar Cakupan Proyek \] │

│ 1. Integrasi gateway pembayaran e-wallet / QRIS otomatis. │

│ 2. Fitur penggajian karyawan / manajemen HRD. │

│ 3. Pemesanan stok otomatis ke supplier luar. │ └────────────────────────────────────────────┘

### **Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| **No** | **Modul / Fitur Sistem**                                                    | **Status Cakupan (_In-Scope / Out-of-Scope_)** | **Alasan Pertimbangan Kelayakan (O'Brien)**                                                                                                                                |
| ------ | --------------------------------------------------------------------------- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**  | Pencatatan Transaksi Peminjaman Dan Pengembalian Buku Berbasis Aplikasi CLI | **IN-SCOPE**                                   | Kelayakan Operasional: Sangat di Butuhkan dalam pengelolaan Perpustakaan untuk mempercepat Proses transaksi dengan Pelayanan peminjaman dan Pengembalian buku perpustakaan |
| **2**  | Update Stok atau Ketersediaan buku Otomatis                                 | **IN-SCOPE**                                   | Kelayakan Teknis: Dapat di Implementasikan dengan logika Struktur data Pyhton untuk Memantau Keberadaan dan ketersediaan stok Buku secara real Time                        |
| **3**  | Laporan Rekapitulasi Harian dan peminjaman Stok buku                        | **IN-SCOPE**                                   | Kelayakan Ekonomi: Memberikan Nilai value bagi pengelola atau Sekolah untuk recap harian tanpa Pencatatan manual                                                           |
| **4**  | Integrasi Rf ID/Barcode Scanner otomatis                                    | **OUT-OF-SCOPE**                               | Keterbatasan waktu 1 Semester/ Kompleksitas integrasi perangkat keras di PBL Level 1                                                                                       |
| **5**  | Multi-cabang/<br><br>Integrasi perpustakaan Luar                            | **OUT-OF-SCOPE**                               | Perpustakaan SD Muhammadiyah Nitikan saat inI memiliki di 4 Cabang Lokasi Sekolah                                                                                          |

## **5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| **Indikator Kinerja**                          | **Kondisi As-Is (Baseline)**  | **Target To-Be (Expected)**                  | **Estimasi Persentase Peningkatan**                                   |
| ---------------------------------------------- | ----------------------------- | -------------------------------------------- | --------------------------------------------------------------------- |
| Waktu pelayanan Transaksi Peminjaman Buku      | **15 detik** / orang          | **< 5 detik /orang**                         | Peningkatan efisiensi **66.7%**                                       |
| Durasi rekapitulasi Harian dan Peminjaman buku | **30-60 menit** / malam       | **< 5 menit / malam**                        | Penghematan waktu **83.3%**                                           |
| Akurasi pencatatan Dan selisih stok buku       | Selisih stok **0,5%** / bulan | **Akurasi > 99%**<br><br>**(selisih <0,1%)** | Penurunan Signifikanpada Tingkat kesalahan Pencatatan dan buku Hilang |

## **6\. Refleksi & Lembar Pengesahan Phase Lead**

### **A. Pertanyaan Refleksi Tim**

1. _Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?_
   - **Jawab**: \[ Jelaskan analisis kelayakan teknis dan kemampuan tim \]
2. _Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?_
   - **Jawab**: \[ Jelaskan hasil konfirmasi awal ke mitra \]

### **B. Tanda Tangan Pengesahan Phase Lead 2**

Disusun oleh Phase Lead 2 (Frame): \[ Yudo Rahman Badrakusuma — 2600016021 \]

```
Tanggal Penyusunan: [ 23 Oktober 2026 ]
Tanda Tangan Phase Lead 2: ____________________
Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]
Catatan Dosen: __________________________________________________
```


