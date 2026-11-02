# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05** 

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria** 

Mata Kuliah: **Konsep Sistem Informasi (KSI)** Kerangka Kerja: **Project-Based Learning (PBL) Level 1** Fase Learning Spine: **Fase 3 — Define (Minggu 3)** Sub-CPMK / SFIA: **S-01.1 (Intermediate - Problem Framing) & S-03.1 (Intermediate - Pemetaan SI)** | **SFIA BUSA L1, REQM L2** Keterkaitan Deliverable: **Bahan Utama Deliverable D2 (System & Solution Design - TPL-02)** 

### **1. Identifikasi Kelompok & Rotasi Kepemimpinan** 

- **Nama Kelompok** : Argonaut 

- **Objek UMKM Mitra** : Perpustakaan SD Muhammadiyah Nitikan 

- **Phase Lead 3 (Define)** : <u>Ale Gunner Saprudin</u> 

- **Anggota Tim** : 1. Raffi Adien Saputra 2. <u>Yudo Rahman</u> 3.Dafa Almer 4.Danis Al-Faiz 

### **2. Landasan Konseptual: Analisis Sistem "What" vs "How"** 

Dalam tahap _Systems Analysis_ , fokus utama tim adalah menentukan **APA (** **_What_ )** yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, **BUKAN BAGAIMANA (** **_How_ )** sistem dibangun secara teknis (Marakas & O'Brien, 2013). 

- **User Story** merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola: 

$$\text{"Sebagai [Peran Pengguna], Saya ingin [Kemampuan/Fitur], Sehingga [Manfaat Bisnis Nyata]"}$$ 

- **Acceptance Criteria (Given-When-Then)** mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021). 

### **3. Workspace A: Formulasi User Story Fungsional** 

Petakan minimal **3 User Story Utama** yang langsung menjawab akar masalah pada D1 / WS04: 

####User Story 1 (Prioritas Utama / Core Feature)

Sebagai (As a): Guru pengelola perpustakaan (Ibu Yunistia Sekar Sarworini, S.IP)
Saya ingin (I want to): Memiliki cara agar kondisi ruang perpustakaan, termasuk meja dan kursi, tetap rapi setelah sesi membaca siswa selesai
Sehingga (So that): Pengelola perpustakaan tidak kewalahan merapikan ruangan secara manual dan perpustakaan selalu tertata

User Story 2 (Fitur Manajemen Stok / Data)
Sebagai (As a): Staf perpustakaan
Saya ingin (I want to): Memastikan setiap buku dikembalikan ke posisi rak yang telah ditentukan setelah siswa selesai membaca
Sehingga (So that): Pengecekan buku dapat dilakukan dengan cepat saat sesi berakhir

User Story 3 (Fitur Pelaporan / Informasi)

Sebagai (As a): Staf perpustakaan
Saya ingin (I want to): Mendorong lebih banyak siswa untuk membaca di perpustakaan
Sehingga (So that): Minat baca dan pengetahuan siswa meningkat

4. Workspace B: Acceptance Criteria

 Skenario 1A: Perpustakaan Rapi Setelah Sesi Membaca (Happy Path)

Diberikan (Given):
Sesi membaca siswa sudah selesai, dan setiap buku yang dibaca memiliki posisi rak yang telah ditentukan (misalnya berdasarkan kode atau label warna).

Ketika (When):
Siswa mengembalikan buku yang dibaca ke posisi rak sesuai label, lalu guru atau staf melakukan pengecekan akhir sesi menggunakan daftar periksa (checklist) kerapian.

Maka (Then):
Seluruh buku berada di posisi yang benar, meja dan kursi kembali tertata, pengecekan selesai dalam waktu singkat (± 10 menit), dan pengelola tidak perlu merapikan ulang secara manual.

Skenario 1B: Ada Buku Tidak Sesuai Posisi (Exception Path)

Diberikan (Given):
Sesi membaca telah selesai, dan terdapat buku yang masih tergeletak di meja atau diletakkan di rak yang salah.

Ketika (When):
Guru atau staf melakukan pengecekan akhir menggunakan daftar periksa (checklist) dan menemukan buku yang tidak sesuai posisinya.

Maka (Then):
Buku tersebut ditandai pada checklist, lalu dikembalikan ke rak yang benar oleh staf, dan hasil temuan dicatat agar dapat menjadi bahan evaluasi sesi berikutnya

### **5. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)** 

- **Tanggal Validasi** : 21 Oktober 2026 

- **Narahubung Mitra** : Pengurus Perpustakaan 

- **Hasil Konfirmasi User Story** : 

   - [x] Seluruh User Story disetujui mitra 

[x] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada): 

### **6. Verifikasi Integritas AI (TPL-07) & Pengesahan** 

- **Penggunaan AI Co-pilot** : 

Apakah tim menggunakan AI untuk membantu merumuskan skenario _Given-When-Then_ ? [ ] Ya [x] Tidak 

_(Jika Ya, wajib melampirkan formulir_ **_TPL-07: AI Usage Disclosure & Verification Note_** _)_ . 

##### **Tanda Tangan Tim & Pengesahan Dosen** : 

- **Phase Lead 3** : <u>Ale Gunner Saprudin (Tanggal: 21 Oktober 2026</u>) 

- **Dosen Coach** : (Tanggal: ) [ ] Approved 

