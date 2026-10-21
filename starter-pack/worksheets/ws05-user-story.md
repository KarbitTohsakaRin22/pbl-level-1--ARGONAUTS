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

#### **User Story 1 (Prioritas Utama / Core Feature)** 

- **Sebagai (** **_As a_ )** : 

Guru pengelola perpustakaan (Ibu Yunistia Sekar Sarworini, S.IP) 

- **Saya ingin (** **_I want to_ )** : <u>Mencari cara agar kondisi perpustakaan setelah sesi membaca siswa/i tidak berantakan</u> 

- **Sehingga (** **_So that_ )** : 

   - <u>Para pengola perpustakaan tidak kewalahan dan perpustakaan rapi</u> 

#### **User Story 2 (Fitur Manajemen Stok / Data)** 

- **Sebagai (** **_As a_ )** : Staff Perpustaan 

- **Saya ingin (** **_I want to_ )** : <u>Menjaga kerapihan dan peletakan buku sesuai posisi yang telah ditentukan setelah anak-anak membaca</u> 

- **Sehingga (** **_So that_ )** : 

   - <u>Dapat dilakukan pengecekan buku secara cepat saat sesi selesai</u> 

#### **User Story 3 (Fitur Pelaporan / Informasi)** 

- **Sebagai (** **_As a_ )** : Staff Perpustakaan 

- **Saya ingin (** **_I want to_ )** : 

   - <u>Perpustakaan banyak anak membaca</u> 

**_Sehingga (So that)_** _:_ 

##### <u>Minat baca dan pengetahuan siswa/i meningkat</u> 

### **4. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)** 

Susun kriteria penerimaan terstruktur untuk **User Story 1** (mencakup Skenario Sukses dan Skenario Penanganan Eror): 

#### **Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)** 

- **Diberikan (** **_Given_ )** : 

- Sesi membaca siswa sudah selesai, dan setiap buku yang dibaca memiliki posisi rak yang telah ditentukan (misalnya berdasarkan kode atau label warna). 

- 

- **Ketika (** **_When_ )** : 

siswa mengembalikan buku yang dibaca ke posisi rak sesuai label, lalu guru atau staf melakukan pengecekan akhir sesi dengan daftar periksa (checklist) kerapian. 

- **Maka (** **_Then_ )** : 

Seluruh buku berada di posisi yang benar, meja dan kursi kembali tertata, pengecekan selesai dalam waktu singkat \+- 10 Menit dan pengelola tidak perlu merapikan ulang secara manual. 

**Skenario 1B: Penanganan Pembayaran Kurang / Eror (Exception Path)** 

- **Diberikan (** **_Given_ )** : 

Sesi membaca telah selesai, dan terdapat buku yang masih tergeletak di meja atau diletakkan di rak yang salah. 

- **Ketika (** **_When_ )** : 

Guru atau staf melakukan pengecekan akhir dengan daftar periksa dan menemukan buku yang tidak sesuai posisinya. 

- **Maka (** **_Then_ )** : 

Buku tersebut ditandai pada checklist, dikembalikan ke rak yang benar oleh siswa yang bertugas (misalnya petugas piket kelas) atau oleh staf, dan hasil temuan dicatat sehingga dapat dijadikan bahan evaluasi sesi berikutnya. 

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

- **Phase Lead 3** : <u>Ale Gunner Saprudin (Tanggal: 21 Oktober 2026</u> 

- **Dosen Coach** : (Tanggal: ) [ ] Approved 

