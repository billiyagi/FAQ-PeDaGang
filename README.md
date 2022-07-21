
# Pegang

Aplikasi pengelola data gudang yang simpel, mudah dan fleksibel. Dengan menggunakan berbagai Jenis Framework dan Library terbaik saat ini, menjadikan PeGang aplikasi yang cukup kompatibel dengan berbagai kondisi.


## Fitur

- Sistem multi pengguna
- Live aktifitas aplikasi
- Cetak laporan pembelian/penjualan dengan blanko kostum
- Keamanan login blokir setelah 3x percobaan
- Panduan penggunaan di setiap menu


## Demo

link: http://pedagang.gq/

**Administrator**
username: admin
password: 12345678

**Pegawai**
username: pegawai
password: 12345678

## Instalasi dan Konfigurasi

- Buat database di sistem kalian masing-masing
- Import file db_pedagang.sql ke database yang telah dibuat
- cari file .env (ada di luar folder) 
- ubah isi file .env tersebut sesuai konfigurasi masing - masing


**Alamat web**
```
  app.baseURL = 'http://localhost:8080/'
```
ubah sesuai **nama domain** yang digunakan.

**Jika menggunakan server lokal** seperti XAMPP, ketika ingin menggunakan aplikasi pegang wajib menjalankan *PHP Local Development server*, caranya seperti berikut:

- Buka Terminal/CMD arahkan ke folder aplikasi PeGang
- ketik perintah **php spark serve**
- Lalu buka alamat server yang ada pada layar terminal biasanya http://localhost:8080 atau http://localhost:8000

**Database**
```
  database.default.hostname = localhost
  database.default.database = pedagang
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

