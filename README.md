TUGAS BESAR ANALISIS DATA STSTISTIKA KELOMPOK 11_RA:

1.NAMA ANGGOTA:
Della Ainisa Fitri (124450095)
Risa Romadona (124450127) 
Najwa Putri Yopu (124450123)

Cara Menjalankan Script

Pastikan struktur folder project sudah sesuai: /data/, /code/, /output/, /poster/, dan README.md.

Masukkan dataset (misal: Book1.csv) ke dalam folder /data/.

Buka file script analisis yang ada di folder /code/.

Install semua paket yang diperlukan:

install.packages(c("dplyr", "ggplot2", "readr", "RColorBrewer"))


Sesuaikan file path dataset pada bagian pembacaan data:

df <- readr::read_csv("D:/TUGAS SEM 3/ADS/Book1.csv",
                      locale = locale(encoding = "Latin1"))


Jalankan seluruh script dari awal sampai akhir dengan menekan Run All
atau menggunakan shortcut Ctrl + Shift + Enter.

2. Paket R yang Digunakan

dplyr – Membersihkan data, mengubah tipe kolom, dan menghitung statistik deskriptif (mean, median, modus, sd, varians).

ggplot2 + RColorBrewer – Membuat visualisasi eksplorasi data seperti boxplot dan bar chart dengan palet warna estetik.

readr – Membaca file CSV menggunakan encoding Latin1 sehingga dataset dapat terbaca tanpa error.

3. Penjelasan Singkat Dataset

Dataset berisi data survei mahasiswa dengan lebih dari 450 responden. Variabel penting yang dianalisis mencakup:

IPK terakhir mahasiswa

Jenis tempat tinggal (Asrama, Kos, Tinggal bersama orang tua, Kontrakan, dll.)

Jam belajar per minggu

Pendidikan dan pekerjaan orang tua

Pendapatan keluarga serta data demografis lainnya

Analisis dilakukan untuk melihat ukuran pemusatan dan penyebaran IPK, membandingkan IPK antar jenis tempat tinggal, membuat visualisasi, serta melakukan uji hipotesis (uji-t).
