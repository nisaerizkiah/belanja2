# Praktikum 2 - Navigasi dan Layout Flutter    
Pada praktikum ini saya membuat aplikasi belanja sederhana menggunakan **Flutter** dengan fitur utama navigasi antar halaman dan pengiriman data menggunakan arguments. Aplikasi menampilkan daftar produk dalam bentuk GridView, lalu saat produk ditekan akan masuk ke halaman detail.  

Data produk dikirim melalui arguments dan dibaca di halaman tujuan dengan ModalRoute. Setiap produk memiliki atribut: nama, harga, gambar, stok, dan rating.

Struktur project dipisah menjadi beberapa folder (models, pages, widgets) agar kode lebih rapi. Aset gambar produk ditambahkan melalui folder assets dan didaftarkan di pubspec.yaml.  

Selain itu, pada halaman aplikasi saya menambahkan footer menggunakan bottomNavigationBar yang menampilkan identitas mahasiswa Nama & NIM nya.  

## Hasilnya 
- **HomePage** → menampilkan daftar produk dalam grid  
- **ItemPage** → menampilkan detail produk yang dipilih  
- **Footer** → selalu tampil di bawah halaman berisi Nama & NIM  <img width="1920" height="1200" alt="belanjaNew" src="https://github.com/user-attachments/assets/4d3d9aa0-5fcb-4011-b5e0-37573e7ea9d7" />
