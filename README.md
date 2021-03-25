

# Praktikum Pemrograman Web 1
Praktikum pemrograman web pertemuan 3.

## HTML

<img src="https://github.com/antonmartinus72/Lab1Web/raw/main/res/hmlt5_logo.png" height="300">

HTML (Hypertest Markup Language) merupakan bahasa markup yang digunakan untuk membuat sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai dengan yang diinginkan. HTML saat ini merupakan standar Internet yang didefinisikan dan dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).

## Kerangka Dasar HTML.
Berikut adalah kerangka dasar yang di gunakan dalam tag HMTL.

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/1_code.jpg)

Keseluruhan html masih terlihat kosong namun pada baris 4 terdapat tag `<title>` yang berfungsi untuk membuat judul halaman yang ditampilkan pada tab browser.

![screenshoot](https://github.com/antonmartinus72/Lab1Web/raw/main/img/1.jpg)

## Heading pada HTML
Heading pada html dapat dijadikan sebagai judul topik atau pembahasan.
![screenshoot](https://github.com/antonmartinus72/Lab1Web/raw/main/img/2.jpg)

Jika diperhatikan setiap heading memiliki ukuran font yang berbeda. Ukuran ini adalah ukuran default yang diterapkan html.
Dapat di tulis seperti berikut :

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/2_code.jpg)

## Paragraf dan Horizontal Line
Dapat dilihat di bawah ***Heading 6*** terdapat garis horizontal, garis ini menggunakan tag `<hr>` .

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/3.jpg)

Di bawah garis`<hr>` terdapat tag `<p>...</p>` yang digunakan untuk membuat sebuah paragraf. 
![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/3_code.jpg)

Parafgraf `<p>...</p>` juga dapat menggunakan atribut berikut :

 **Atribut `align="left"`.**
 
![ss_left](https://github.com/antonmartinus72/Lab1Web/raw/main/img/3a.jpg)
 
 **Atribut `align="right"`.**
 
![ss_right](https://github.com/antonmartinus72/Lab1Web/raw/main/img/3b.jpg) 

**Atribut `align="center"`.**

![ss_center](https://github.com/antonmartinus72/Lab1Web/raw/main/img/3c.jpg)

Jika di bandingkan, ketiganya membentuk posisi yang berbeda. Untuk paragraf tanpa atribut `align` jika dibandingkan dengan menggunakan atribut dengan value`align="left"` tidak terlihat perbedaan apapun. Ini karena nilai default untuk tag `<p>...</p>` terlihat sama hasilnya seperti atribut value `align="left"`.

## Preformatted Text.
Jika kita perhatihan, pada tag paragraf `<p>` spasi dan enter akan di abaikan dan hanya akan di cetak satu kali, tidak peduli seberapa banyak kita memasukannya secara berulang.
Jika kita ingin spasi dan enter ditampilkan sesuai seberapa banyak yang dimasukan, maka dapat menggunakan tag `<pre>...</pre>`(**Preformatted Text**) atau format text sesuai yang kita masukan di dalam file html.

![ss_center](https://github.com/antonmartinus72/Lab1Web/raw/main/img/4.jpg)

Text yang ditampilkan memiliki format berbeda meskipun format penulisan text di dalam html sama.

![ss_center](https://github.com/antonmartinus72/Lab1Web/raw/main/img/4_code.jpg)

## Break Line
Text dalam html text atau paragraf sebagai contoh kasus, juga dapat dipisah menggunakan tag `<br>` **(Break Line)** seperti di bawah ini. 

![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/5.jpg)

Text setelah tag `<br>` akan di letakan di baris bawah text sebelum tag `<br>`.

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/5_code.jpg)

## Text Format
Dalam penulisan text tidak jarang kita membutuhkan penanda pada kosakata atau  kalimat yang memudahkan kita untuk menyadari jika terdapat maksud yang di tekankan pada text, kosakata atau kalimat.

 - `<b>...</b>` (<b>Bold text</b>)
 - `<strong>...</strong>` (<strong>Important text</strong>).
 - `<em>...</em>` (<em> Emphasized text</em>).
 - `<mark>...</mark>` (<mark> Marked text </mark>).
 - `<small>...</small>` ("Belajar HTML" **menjadi >** <small> "Belajar HTML" </small> (Smaller text size)).
 - `<del>...</del>` (<del>Deleted text</del>).
 - `<ins>...</ins>` (<ins>Inserted text</ins>).
 - `<sub>...</sub>` (This is <sub>sub format</sub> example).
 - `<sup>...</sup>` (This is <sup>sup format</sup> example).

Sudah terlihat perbedaannya dari contoh di atas. Namun untuk **Bold Text** dan **Important Text** terlihat sama. Hanya saja, Important text dapat mempengaruhi penelusuran dalam mesin pencari (Google, Yahoo, dll.).

Berikut tampilannya jika di terapkan dalam paragraf :

![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/6.jpg)

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/6_code.jpg)

## Tag Anchor dan Hyperlink
Hyperlink atau biasa di sebut "*link*" merupakan elemen yang dapat dipakai untuk menghubungkan halaman ke halaman lainnya. 

![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/7.jpg)

Dapat dilihat pada bagian sudut kanan bawah pada gambar diatas. Terdapat alamat website yang muncul pada browser (Chrome). Alamat ini muncul ketika kursor menyentuh link yang ada pada browser tersebut. Link ini yang akan mengantarkan kita ke alamat yang ada pada link.

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/7_code.jpg)

Hyperlink dibuat menggunakan tag Anchor `<a>...</a>`. Bagian terpenting lainnya adalah atribut `href` yang value-nya akan di isi dengan alamat yang dituju.

## Tag Image
Tag `<img>` image  digunakan untuk menampilkan objek gambar pada halaman html.

![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/8.jpg)

Tag `<img>` harus memiliki atribut `src` untuk dapat menampilkan gambar. Atribut `src` digunakan untuk mendefinisikan alamat tempat dimana gambar akan diambil.  Selain itu, tag `<img>` dapat di isi dengan atribut berikut :

 -  `width` digunakan untuk menentukan lebar gambar.
 - `height` digunakan untuk menentukan tinggi gambar.
 - `alt` digunakan untuk memberikan keterangan file gambar.
 - `title` digunakan untuk memberikan judul pada gambar.
 
 Pada gambar di atas, terdapat tiga gambar logo html 5 yang memiliki ukuran yang berbeda. Sesuai urutan, ketiga gambar tersebut masing masing memiliki artibut `widht`, `height` dan `widht` & `height` secara bersamaan. 
 
Hanya terlihat perbedaan ukuran pada gambar urutan 1 dan 2, itu dikarenakan value yang di berikan pada atribut `widht`, `height` pada masing-masing gambar berbeda. Sedangkan pada gambar urutan 3, dimensi gambar ikut berubah, ini disebabkan karena kedua dimensi lebar dan tinggi gambar diubah oleh atribut `widht` dan  `height` yang diterapkan secara bersamaan.

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/8_code.jpg)

Atribut "alt" berfungsi sebagai nama alternatif pada gambar. Atribut `alt` dapat berguna jika alamat gambar yang di definisikan dalam atribut `src` di dalam tag `<img>` tidak ditemukan.

![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/8a.jpg)

Value dari atribut `alt` dapat tampil jika atribut `src` dalam tag `<img>`  di tulis dengan salah dan akan merespon juga bila alamat tidak ditemukan atau dihapus.

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/8a_code.jpg)

Value dari atribut `title` dapat tampil jika kita meletakan kursor di atas gambar dengan menunggu sebentar.

![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/8b.jpg)

## Image sebagai Hyperlink

Gambar yang ditampilkan pada halaman html juga dapat berfungsi sebagai hyperlink.
![ss](https://github.com/antonmartinus72/Lab1Web/raw/main/img/9.jpg)

Dengan memilih salah satu gambar di atas, kita akan di arahkan ke website yang telah di definisikan pada atribut `href` berikut :

![code](https://github.com/antonmartinus72/Lab1Web/raw/main/img/9_code.jpg)

