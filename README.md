# Pertemuan 09 - List dan Pengolahan Data Numerik

**Mata Kuliah:** Algoritma dan Pemrograman  
**Program Studi:** S1 Pendidikan Matematika FKIP Untirta  
**Nama:** Suci Ramadhani  
**NIM:** 2225250177  
**Kelas:** 3B  
**Tahun Ajaran:** 2026/2027 Ganjil

## Tujuan

Mempelajari penggunaan list Python untuk menyimpan, mengakses, mengubah, dan mengolah kumpulan data numerik. Materi ini juga menerapkan perulangan, seleksi, dan fungsi untuk menghitung statistik sederhana serta mengelompokkan nilai mahasiswa berdasarkan batas kelulusan.

## Struktur Program

- `latihan/01_buat_list.py`: Membuat list dan menghitung banyak data.
- `latihan/02_indeks_slicing.py`: Mengakses elemen dengan indeks dan slicing.
- `latihan/03_manipulasi_list.py`: Mengubah, menambah, menyisipkan, dan menghapus elemen.
- `latihan/04_agregasi_nilai.py`: Menghitung total, rata-rata, nilai minimum, dan maksimum.
- `latihan/05_filter_kelulusan.py`: Menyeleksi nilai yang memenuhi batas kelulusan.
- `latihan/06_fungsi_statistik.py`: Menghitung rata-rata menggunakan fungsi.
- `praktik/analisis_nilai_mahasiswa.py`: Mengolah nilai mahasiswa dan menampilkan ringkasan statistik serta kelulusan.

## Cara Menjalankan

Program dijalankan menggunakan Python 3 melalui terminal VS Code.

Contoh menjalankan program utama:

```bash
python praktik/analisis_nilai_mahasiswa.py
```

Untuk menjalankan latihan, sesuaikan perintah dengan nama file yang ingin dijalankan. Contoh:

```bash
python latihan/01_buat_list.py
```

## Hasil Pengujian

Program utama menggunakan 10 data nilai mahasiswa:

`[78, 55, 90, 67, 60, 82, 45, 71, 88, 59]`

Hasil pengujian:

- Banyak data: 10
- Total nilai: 695
- Rata-rata: 69.50
- Nilai minimum: 45
- Nilai maksimum: 90
- Nilai yang lulus: `[78, 90, 67, 60, 82, 71, 88]`
- Jumlah mahasiswa lulus: 7
- Jumlah mahasiswa belum lulus: 3

Program juga menggunakan fungsi rata-rata yang mengembalikan 0 apabila menerima list kosong, sehingga tidak melakukan pembagian dengan nol.

## Test Case

| Data | Pengujian | Hasil yang Diharapkan |
|---|---|---|
| `[60, 70, 80]` | Rata-rata | 70.00 |
| `[60, 70, 80]` | Minimum dan maksimum | 60 dan 80 |
| `[60, 70, 80]` | Jumlah lulus | 3 |
| `[59, 60, 61]` | Kelulusan dengan batas 60 | 2 lulus |
| `[]` | Rata-rata list kosong | 0, tanpa error |

## Refleksi

Melalui latihan ini, saya memahami bahwa list dapat digunakan untuk menyimpan banyak nilai dalam satu variabel. Saya juga mempelajari cara mengakses elemen menggunakan indeks, mengambil sebagian data dengan slicing, serta mengubah isi list. Selain itu, saya memahami penggunaan perulangan, seleksi, dan fungsi untuk menghitung statistik serta menentukan kelulusan mahasiswa.

Kesalahan yang perlu diperhatikan adalah penggunaan indeks yang tidak sesuai, karena indeks list Python dimulai dari 0. Saya juga perlu memeriksa list kosong sebelum menghitung rata-rata agar tidak terjadi pembagian dengan nol.

## Referensi dan Bantuan

- Bahan Ajar Algoritma dan Pemrograman Pertemuan 09, List/Array dan Pengolahan Data Numerik Sederhana.
- Python Software Foundation, dokumentasi Python 3.