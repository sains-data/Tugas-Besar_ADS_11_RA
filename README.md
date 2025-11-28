TUGAS BESAR ANALISIS DATA STSTISTIKA KELOMPOK 11_RA:

1.NAMA ANGGOTA:

Della Ainisa Fitri (124450095)

Risa Romadona (124450127) 

Najwa Putri Yopu (124450123)

___________________________________________________________________________________________
CARA MENJALANKAN SCRIPT

Siapkan Struktur Folder
Pastikan project memiliki folder:
/data/, /code/, /output/, /poster/, dan README.md.

Masukkan Dataset
Simpan file dataset kamu (misal: Book1.csv) ke dalam folder /data/.

Buka Script Analisis
Masuk ke folder /code/, lalu buka file script R yang digunakan untuk analisis.

Install Semua Paket yang Dibutuhkan

install.packages(c("dplyr", "ggplot2", "readr", "RColorBrewer"))


Atur Lokasi File Dataset (File Path)
Pada bagian pembacaan data dalam script, sesuaikan path menjadi lokasi dataset kamu:

df <- readr::read_csv(
  "D:/TUGAS SEM 3/ADS/Book1.csv",
  locale = locale(encoding = "Latin1")
)


Jalankan Script dari Awal Sampai Akhir

Klik Run All di RStudio
atau
Tekan Ctrl + Shift + Enter

Maka seluruh proses—mulai dari pembersihan data, perhitungan statistik, visualisasi, hingga uji hipotesis—akan berjalan otomatis.
_________________________________________________________________________________________________________________________________

PAKET R YANG DIGUNAKAN 

dplyr – Untuk pembersihan data, transformasi kolom, dan perhitungan statistik deskriptif (mean, median, modus, sd, varians).

ggplot2 + RColorBrewer – Untuk visualisasi seperti boxplot dan bar chart dengan palet warna yang modern dan estetik.

readr – Untuk membaca CSV dengan encoding Latin1 agar data dapat terbaca tanpa error.
__________________________________________________________________________________________________________________________________

PENJELASAN SINGKAT DATASET

Dataset ini merupakan hasil survei terhadap lebih dari 450 mahasiswa dan berisi berbagai informasi penting seperti IPK terakhir,
jenis tempat tinggal (Asrama, Kos, Tinggal dengan Orangtua, Kontrakan, dan lainnya), jam belajar per minggu, pekerjaan serta pendapatan orang tua,
dan data demografis seperti jenis kelamin, tinggi badan, dan pendidikan terakhir. Analisis dilakukan untuk melihat ukuran pemusatan dan
penyebaran IPK (mean, median, modus, standar deviasi, dan varians), membandingkan IPK berdasarkan jenis tempat tinggal, membuat visualisasi sebagai 
bentuk eksplorasi data, serta melakukan uji hipotesis (uji-t) untuk mengetahui apakah terdapat perbedaan signifikan antar kelompok tempat tinggal tertentu.
_____________________________________________________________________________________________________________________________________________________

STRUKTUR REPOSITORY

data_ads : data yang belum di bersihkan 

data_11 : data yang sudah di bersihkan 

code    : script R (kode_11_RA)

output  : tabel & hasil uji 

poster  : poster A1 (PDF)

README.md  : dokumentasi proyek 






