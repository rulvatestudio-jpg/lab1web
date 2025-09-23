# Lab1Web Praktikum HTML Dasar

## Tujuan Praktikum
- Mahasiswa dapat memahami struktur dasar HTML.
- Mahasiswa dapat memahami penggunaan tag-tag dasar HTML.
- Mahasiswa dapat membuat dokumen HTML sederhana.

---

## Langkah 1: Membuat Struktur Dasar HTML
Pada langkah pertama, saya membuat struktur dasar HTML yang mencakup `DOCTYPE`, tag `<html>`, `<head>`, dan `<body>`. Struktur dasar ini adalah fondasi dari setiap dokumen HTML.


<img width="1920" height="1200" alt="Screenshot 2025-09-22 221510" src="https://github.com/user-attachments/assets/686aed41-393b-4953-852a-f55f62c0bff1" />

#Langkah 2: Menambahkan Paragraf#

Langkah berikutnya adalah menambahkan beberapa paragraf menggunakan tag <p>. Paragraf pertama menjelaskan tujuan praktikum HTML, sedangkan paragraf kedua memberikan penjelasan lebih lanjut mengenai topik yang dibahas.

<img width="1920" height="1200" alt="Screenshot 2025-09-22 221927" src="https://github.com/user-attachments/assets/45d35ba3-115d-4b40-b4fc-64a41fd2d0fd" />

Langkah 3: Menyisipkan Gambar

Menambahkan gambar dengan tag <img>. Saya menggunakan atribut src untuk menentukan lokasi gambar, serta atribut width dan height untuk mengatur ukuran gambar.
<img width="1920" height="1200" alt="Screenshot 2025-09-22 222122" src="https://github.com/user-attachments/assets/87988e27-38eb-47c8-8f44-a903ec6302f9" />






. Lakukan perubahan pada kode sesuai dengan keinginan Anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

Jawaban:
Ketika terjadi kesalahan penulisan tag HTML (misalnya, tag yang tidak ditutup dengan benar atau penulisan tag yang salah), browser akan mencoba untuk menampilkan halaman meskipun ada kesalahan.

Contoh kesalahan: Jika kita menulis <p>Ini adalah paragraf (tanpa menutup tag </p>), browser mungkin akan tetap menampilkan konten, tetapi tidak akan mengikuti struktur yang benar.

Pengaruhnya: Meskipun halaman bisa ditampilkan, kesalahan ini bisa menyebabkan layout yang tidak diinginkan atau tampilan yang rusak. Beberapa elemen bisa saling tumpang tindih atau tidak ditampilkan sesuai harapan. Oleh karena itu, penting untuk menulis tag HTML dengan benar dan sesuai standar.

2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!

Jawaban:

Tag <p> (Paragraph): Tag ini digunakan untuk membuat sebuah paragraf dalam HTML. Setiap tag <p> akan memulai baris baru dan memberikan jarak antar paragraf. Biasanya digunakan untuk menampung beberapa kalimat atau teks yang terkait dalam satu kesatuan.

Tag <br> (Break Line): Tag ini digunakan untuk memulai baris baru dalam satu paragraf atau elemen teks. Tag ini tidak memiliki tag penutup, dan hanya digunakan untuk membuat pemisahan baris tanpa membuat paragraf baru.

Perbedaan utama:

<p> membuat satu blok teks dengan spasi antar paragraf.

<br> hanya membuat baris baru dalam teks tanpa memberi jarak atau membuat paragraf baru.

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

Jawaban:

Atribut alt: Atribut ini memberikan deskripsi teks yang menggantikan gambar jika gambar tidak dapat ditampilkan. Ini juga berguna untuk aksesibilitas, memberikan informasi kepada pengguna yang mengandalkan pembaca layar (screen reader) agar dapat memahami konten gambar.

Contoh: <img src="logo.png" alt="Logo Universitas Pelita Bangsa">

Atribut title: Atribut ini memberikan informasi tambahan yang muncul saat pengguna mengarahkan kursor (hover) di atas gambar. Ini lebih bersifat informatif atau memberi petunjuk, dan tidak digunakan untuk menggantikan gambar.

Contoh: <img src="logo.png" title="Logo UPB">

Perbedaan utama:

alt digunakan untuk menggantikan gambar jika gambar gagal ditampilkan atau untuk aksesibilitas.

title digunakan untuk memberikan informasi tambahan yang muncul saat pengguna mengarahkan kursor ke gambar.

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

Jawaban:
Agar gambar tampil proporsional, sebaiknya hanya satu atribut (baik width atau height) yang diisi, sementara yang lainnya dibiarkan kosong atau otomatis menyesuaikan. Jika kedua atribut diisi, gambar bisa terlihat terdistorsi (terentang atau terkompresi) karena browser akan memaksa gambar mengikuti dimensi yang ditentukan tanpa mempertimbangkan aspek rasio gambar asli.

Contoh yang benar:

Menentukan hanya width: <img src="logo.png" width="200"> (dan tinggi otomatis menyesuaikan).

Menentukan hanya height: <img src="logo.png" height="200"> (dan lebar otomatis menyesuaikan).

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?

Jawaban:
Atribut target digunakan untuk menentukan di mana sebuah link (hyperlink) akan dibuka. Berikut adalah nilai yang dapat digunakan untuk atribut target:

_blank: Membuka link di tab atau jendela baru. Ini sering digunakan untuk membuka tautan eksternal agar tidak menutup halaman asal.

Contoh: <a href="https://www.example.com" target="_blank">Link</a>

_self: Membuka link di dalam jendela atau tab yang sama. Ini adalah nilai default jika atribut target tidak digunakan.

Contoh: <a href="page.html" target="_self">Link</a>

_top: Membuka link di jendela atau frame penuh, yang akan menimpa seluruh isi dari frame saat ini. Biasanya digunakan dalam konteks halaman dengan banyak frame.

Contoh: <a href="page.html" target="_top">Link</a>

_parent: Membuka link di dalam frame induk dari frame saat ini. Jika tidak ada frame induk, maka ini sama dengan menggunakan _self.

Contoh: <a href="page.html" target="_parent">Link</a>

Ringkasan:

_blank: Buka link di tab atau jendela baru.

_self: Buka link di tab yang sama (default).

_top: Buka link di jendela penuh, menghapus semua frame.

_parent: Buka link di frame induk dari frame saat ini.
