# FAQ-PeGang
Tempat untuk menanyakan dan konsultasi seputar aplikasi pegang
- Klik tab Issues lalu klik tombol **New Issue**


## PeGang

Aplikasi pengelola data gudang yang simpel, mudah dan fleksibel. Dengan menggunakan berbagai Jenis Framework dan Library terbaik saat ini, menjadikan PeGang aplikasi yang cukup kompatibel dengan berbagai kondisi.


## Fitur

- Sistem multi pengguna
- Live aktifitas aplikasi
- Cetak laporan pembelian/penjualan dengan blanko kostum
- Keamanan login blokir setelah 3x percobaan
- Panduan penggunaan di setiap menu


## Demo

link: https://pegang.cf/


## Instalasi dan Konfigurasi

- Buat database di sistem kalian masing-masing
- Import file db_pegang.sql ke database yang telah dibuat
- cari file .env (ada di luar folder) 
- ubah isi file .env tersebut sesuai konfigurasi masing - masing


**Alamat web**
```
  app.baseURL = 'http://localhost:8080/'
```
ubah sesuai **nama domain dan path folder** yang digunakan, jika menggunakan web server lokal tetap menggunakan localhost sebagai domainnya tetapi dilanjut dengan nama folder aplikasi pegang

**Database**
```
  database.default.hostname = localhost
  database.default.database = pegang
  database.default.username = root
  database.default.password = 
```
ubah sesuai konfigurasi database masing-masing, contoh di atas adalah ketika menggunakan server lokal seperti XAMPP
## Pertanyaan
Jika kamu mempunyai pertanyaan seputar aplikasi PeGang ini silahkan kunjungi
forum khusus untuk aplikasi PeGang : https://github.com/billiyagi/FAQ-PeGang

## Lisensi
Baca di LISENSI.txt atau [Billiyagi Software License](https://pastebin.com/MpkdjBjT)


## Teknologi

**Client:** Bootstrap, JQuery

**Server:** PHP, Codeigniter 4


## Creator & Founder

- [@febrybilliyagi](https://www.github.com/billiyagi)


## Lainnya

Lihat project berbayar dan open source lainnya di -> https://billiyagi.github.io


