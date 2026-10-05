# Lab3Web - Praktikum 3: CSS Dasar

Nama : Hafiz Faturrohman
NIM : 312210375
Kelas : I251C
Mata Kuliah : Pemrograman Web (Praktikum 3: CSS Dasar)

# Soal
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline
CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector
tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada
browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-
paragraf"> )`

# Jawab
1. Ketika property dan value CSS diubah, tampilan halaman web akan ikut berubah sesuai dengan aturan CSS yang diberikan.
Kode awal:
Contohnya:
  `body {
     background-color: #eaf2f8;
}`
Perubahan tersebut akan membuat warna latar belakang halaman menjadi lebih terang.
Contoh lainnya:
.`hero h1 {
    font-size: 55px;   
}`
Perubahan `font-size` akan membuat ukuran judul pada bagian hero menjadi lebih besar.
2. `h1 { ... }` digunakan untuk memberikan style kepada semua elemen `<h1>` yang terdapat pada halaman.
3. Ketiga jenis CSS tersebut dapat digunakan pada halaman HTML, tetapi inline CSS memiliki prioritas lebih tinggi dibandingkan internal CSS dan external CSS apabila mengatur property yang sama dan tidak terdapat `!important`.
4. Selector ID `(#)` memiliki tingkat spesifisitas lebih tinggi daripada selector Class `(.)`.
