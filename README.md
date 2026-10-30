# Dataset Putusan Pengadilan Tindak Pidana Narkotika

**Dataset-Narkotika_002_183**

Repository ini menyediakan kumpulan dokumen putusan pengadilan terkait tindak pidana narkotika yang diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia. Dataset mencakup dokumen putusan dari Pengadilan Negeri Bandung pada periode 2024–2025.

Dataset disusun untuk mendukung kegiatan pembelajaran mata kuliah **Information Retrieval**, khususnya dalam proses akuisisi, pengelolaan, dan pengolahan dokumen hukum.

---

## 1. Tentang Dataset

Dokumen hukum memiliki struktur dan karakteristik teks yang kompleks, sehingga memerlukan proses pengumpulan dan pengelolaan data yang sistematis sebelum dapat digunakan dalam sistem temu kembali informasi.

Dataset ini berisi enam dokumen putusan perkara narkotika yang dikumpulkan berdasarkan kategori dan klasifikasi tertentu pada Direktori Putusan Mahkamah Agung Republik Indonesia.

Setiap dokumen disimpan dalam format PDF, sedangkan informasi penting dari masing-masing putusan dirangkum dalam file spreadsheet untuk memudahkan identifikasi dan penelusuran dokumen.

## 2. Informasi Dataset

| Atribut | Keterangan |
|---|---|
| Nama Dataset | Dataset Putusan Pengadilan Tindak Pidana Narkotika |
| Sumber Data | Direktori Putusan Mahkamah Agung RI |
| Kategori | Pidana Khusus |
| Klasifikasi | Narkotika dan Psikotropika |
| Lembaga Peradilan | Pengadilan Negeri Bandung |
| Periode Putusan | 2024–2025 |
| Jumlah Dokumen | 6 dokumen |
| Format Dokumen | PDF |
| Format Metadata | XLSX |
| Bahasa Dokumen | Bahasa Indonesia |

## 3. Cakupan Dataset

Dataset terdiri atas enam dokumen putusan pengadilan dengan rincian sebagai berikut.

| No. | Nomor Putusan | Tahun | Lembaga Peradilan |
|---:|---|---:|---|
| 1 | 912/Pid.Sus/2024/PN Bdg | 2024 | PN Bandung |
| 2 | 917/Pid.Sus/2024/PN Bdg | 2024 | PN Bandung |
| 3 | 974/Pid.Sus/2024/PN Bdg | 2024 | PN Bandung |
| 4 | 1147/Pid.Sus/2025/PN Bdg | 2025 | PN Bandung |
| 5 | 1171/Pid.Sus/2025/PN Bdg | 2025 | PN Bandung |
| 6 | 1184/Pid.Sus/2025/PN Bdg | 2025 | PN Bandung |

## 4. Struktur Direktori

Repository ini memiliki struktur direktori sebagai berikut.

```text
Dataset-Narkotika_002_183/
│
├── Dataset/
│   └── Narkotika.zip
│
├── Overview/
│   └── Overview.xlsx
│
└── README.md
```

## 5. Deskripsi File

### 5.1 Dataset/Narkotika.zip

File arsip ZIP yang berisi enam dokumen putusan pengadilan dalam format PDF. Dokumen merupakan sumber utama yang digunakan dalam penyusunan dataset.

### 5.2 Overview/Overview.xlsx

File spreadsheet yang berisi ringkasan informasi dari setiap dokumen putusan. File ini digunakan sebagai dokumentasi metadata untuk membantu mengidentifikasi dan memahami isi dokumen.

## 6. Skema Metadata

File `Overview.xlsx` memiliki empat atribut utama sebagai berikut.

| Atribut | Deskripsi |
|---|---|
| No | Nomor urut dokumen dalam dataset. |
| No Putusan | Nomor identifikasi resmi putusan pengadilan. |
| Lembaga Peradilan | Nama pengadilan yang mengeluarkan putusan. |
| Barang Bukti | Informasi barang bukti yang tercantum dalam dokumen putusan. |
| Amar Putusan | Ringkasan keputusan hakim terhadap perkara yang diperiksa. |

## 7. Metodologi Pengumpulan Data

Pengumpulan dataset dilakukan melalui beberapa tahapan berikut.

1. **Penentuan sumber data:** Menggunakan Direktori Putusan Mahkamah Agung Republik Indonesia sebagai sumber dokumen.
2. **Penentuan kategori dan klasifikasi:** Memilih kategori Pidana Khusus dengan klasifikasi Narkotika dan Psikotropika.
3. **Penentuan lembaga peradilan:** Memilih Pengadilan Negeri Bandung sebagai sumber putusan.
4. **Pengumpulan dokumen:** Mengunduh dokumen putusan yang memenuhi kriteria pengumpulan.
5. **Penyusunan metadata:** Mengidentifikasi nomor putusan, lembaga peradilan, barang bukti, dan amar putusan.
6. **Pengorganisasian dataset:** Mengelompokkan dokumen PDF ke dalam arsip ZIP dan menyimpan metadata dalam spreadsheet.

## 8. Cara Menggunakan Dataset

Untuk menggunakan dataset, pengguna dapat mengikuti langkah berikut:

1. Unduh repository atau file `Dataset/Narkotika.zip`.
2. Ekstrak file ZIP untuk memperoleh dokumen putusan dalam format PDF.
3. Buka `Overview/Overview.xlsx` untuk melihat ringkasan dan metadata setiap dokumen.
4. Gunakan dokumen PDF dan metadata sebagai masukan untuk proses pengolahan dokumen hukum lebih lanjut.

## 9. Sumber Data

Seluruh dokumen putusan dalam dataset diperoleh dari sumber publik berikut:

**Direktori Putusan Mahkamah Agung Republik Indonesia**

https://putusan3.mahkamahagung.go.id/direktori.html

## 10. Pemanfaatan Dataset

Dataset ini disusun untuk mendukung kegiatan praktikum dan pembelajaran Information Retrieval, terutama dalam:

- Akuisisi dan pengelolaan dokumen hukum.
- Preprocessing dokumen teks.
- Ekstraksi informasi dari putusan pengadilan.
- Pengindeksan dokumen.
- Pengembangan sistem temu kembali informasi berbasis dokumen hukum.

## 11. Anggota Kelompok

| No. | Nama | NIM |
|---:|---|---|
| 1 | [Safwa Nusaibah] | [202310370311002] |
| 2 | [Intan Dwi Rahmadhani] | [202310370311183] |

---
