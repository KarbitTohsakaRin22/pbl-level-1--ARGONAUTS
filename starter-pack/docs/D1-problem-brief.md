# D1 — Problem Brief

**Project**: Digital Problem Framing Mini Project — [Perpustakaan SD Muhammadiyah Nitikan]
**Tim**: [Yudo Rahman, Dafa almer dzaky, Ale Gunner Saprudin, Raffi Adien Saputra,Danish Al Faiz  ] | **Tanggal**: [21/10/2026] | **Versi**: [v1.A; 0]
**Template**: TPL-01

> **Petunjuk**: Hapus teks dalam `[...]` dan huruf miring setelah diisi.
> Worksheet terkait: WS03, WS04

---

## 1. Profil Organisasi / Unit Usaha

- **Nama unit usaha**: [SD Muhammadiyah Nitikan]
- **Jenis usaha / layanan**: [Unit Perpustakaan Sekolah]
- **Lokasi**: [Jalan Kranon Nitikan No.UH 6, RT.45/RW.11, Sorosutan, Kec. Umbulharjo, Kota Yogyakarta, Daerah Istimewa Yogyakarta 55162]
- **Deskripsi singkat operasional**: [Menyediakan, Menyimpan buku kebutuhan sekolah,Siswa/i SD Muhammadiyah Nitikan, jam operasional 07:00 - 14:00]
- **Narahubung / pemilik**: [Yunistia Sekar Sarworini, S.I.P. Pustakawan]

## 2. Deskripsi Masalah Utama

- **Masalah utama**: [Kurangnya Tenaga Kerja, dan siswa/i yang tidak kondusif selama/setelah membaca]
- **Pihak yang terdampak**: [Pengurus Perpustakaan. Guru-guru kewalahan dan perpustakaan yang berantakan]
- **Frekuensi / keparahan**: [Jam istirahat dan waktu membaca siswa, setiap kali ada sesi membaca siswa, tidak terlalu mengganggu]

## 3. Batasan Sistem (Scope)

- **Diselesaikan dalam proyek ini**:
  1. Manajemen katalog buku: data buku (judul, kode, kategori), serta posisi rak yang telah ditentukan untuk setiap buku (User Story 2).
  2. Pencatatan peminjaman dan pengembalian buku, termasuk status buku (tersedia, dipinjam, belum kembali).
  3. Fitur penataan akhir sesi membaca: daftar periksa (checklist) kerapian, penandaan buku yang salah posisi atau belum kembali ke rak, dan jadwal siswa piket.
  4. Pencarian buku cepat berdasarkan judul, kode, atau lokasi rak, agar pengecekan di akhir sesi selesai dalam waktu singkat.
  5. Pencatatan kunjungan dan aktivitas membaca siswa per sesi.
  6. Dashboard dan laporan: jumlah siswa yang membaca, buku yang belum kembali, buku paling sering dibaca, dan hasil pengecekan kerapian per sesi.
  7. Pengaturan hak akses pengguna (guru pengelola, staf perpustakaan, siswa piket/siswa).

- **Tidak diselesaikan (dan alasan)**:
  1. Penambahan tenaga pengelola baru: keputusan sekolah, di luar kendali proyek. Aplikasi hanya mengurangi beban kerja.
  2. Pengadaan perangkat dan infrastruktur (komputer, pemindai barcode, jaringan, rak baru): membutuhkan anggaran di luar proyek.
  3. Integrasi dengan sistem akademik atau data induk siswa sekolah: membutuhkan akses dan izin dari pihak lain, sehingga data siswa diinput atau diimpor manual.
  4. Program peningkatan minat baca (lomba, kampanye literasi): aplikasi hanya menyediakan datanya, bukan programnya.
  5. Penegakan disiplin siswa dan perubahan tata tertib: aplikasi hanya membantu lewat alur dan jadwal piket yang jelas.
  6. Fitur denda dan pembayaran: tidak terkait akar masalah kerapian dan kurangnya tenaga.

- **Asumsi yang dipakai**:
  1. Perpustakaan dikelola oleh Ibu Yunistia Sekar Sarworini, S.IP, dibantu staf dengan jumlah tenaga terbatas.
  2. Sekolah menyediakan perangkat (komputer atau ponsel) dan koneksi internet yang cukup untuk menjalankan aplikasi.
  3. Seluruh koleksi buku dan data siswa dapat diinput atau diimpor sebelum aplikasi dipakai.
  4. Setiap buku memiliki kode/label dan posisi rak yang jelas.
  5. Pengelola dan staf bersedia mengikuti pelatihan singkat, dan siswa dapat mengikuti arahan penggunaan dasar.
  6. Sekolah mengizinkan sistem siswa piket bergiliran dan menyediakan waktu perapian di akhir sesi membaca.
 

## 4. Data Kuantitatif Pendukung

| Indikator | Nilai/Baseline | Sumber Data | Tanggal |
|---|---|---|---|
| [waktu layanan rata-rata] | [30 detik - 1 menit] | [wawancara] | [21/10] |
| [jumlah peminjaman buku per hari] | [3-5] | [wawancara] | [23/10] |
| [jumlah staff aktif] | [3 orang] | [wawancara] | [21/10] |

## 5. Pernyataan Kebutuhan Awal (ringkasan ke D2)

- Kebutuhan inti yang akan dijawab prototipe: [
  
  1. Mengatur kunjungan anak saat jam transit pulang, supaya tidak masuk bersamaan dalam jumlah besar.
  2. Membedakan anak yang datang untuk membaca atau meminjam dari anak yang hanya menunggu, sehingga fungsi perpustakaan sebagai tempat membaca tetap terjaga.
  3. Meringankan pengawasan 3 staf saat jam padat, dengan alur yang jelas dan tidak perlu menjaga anak satu per satu.
  4. Memanfaatkan aplikasi Ibra dan alur kerja yang sudah ada, bukan membuat sistem baru dari nol.
  5. Mencatat data kunjungan (jumlah anak per hari, jam paling ramai, lama anak tinggal) sebagai dasar evaluasi dan perbaikan berikutnya.
]

## 6. Daftar Rujukan / Bukti

- [Observasi lapangan tanggal 21,23,29]
- [Wawancara pemilik tanggal 23,29]
- [Dokumen pendukung lainnya]![alt text](<anak membaca.jpeg>)
![alt text](<anak membaca 2.jpeg>)


**Status**: ⬜ Draf → ⬜ Review Tim → ⬜ Validasi Pemilik → ⬜ Final (Gate 1)
