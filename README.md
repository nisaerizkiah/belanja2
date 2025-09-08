# Praktikum 2 - Navigasi dan Layout Flutter    
Pada praktikum ini saya membuat aplikasi belanja sederhana menggunakan **Flutter** dengan fitur utama navigasi antar halaman dan pengiriman data menggunakan arguments. Aplikasi menampilkan daftar produk dalam bentuk GridView, lalu saat produk ditekan akan masuk ke halaman detail.  

Data produk dikirim melalui arguments dan dibaca di halaman tujuan dengan ModalRoute. Setiap produk memiliki atribut: nama, harga, gambar, stok, dan rating.

Struktur project dipisah menjadi beberapa folder (models, pages, widgets) agar kode lebih rapi. Aset gambar produk ditambahkan melalui folder assets dan didaftarkan di pubspec.yaml.  

Selain itu, pada halaman aplikasi saya menambahkan footer menggunakan bottomNavigationBar yang menampilkan identitas mahasiswa Nama & NIM nya.  

## Hasilnya 
- **HomePage** → menampilkan daftar produk dalam grid  
- **ItemPage** → menampilkan detail produk yang dipilih  
- **Footer** → selalu tampil di bawah aplikasi berisi Nama & NIM  