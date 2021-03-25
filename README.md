

# Praktikum Pemrograman Web 1
Praktikum pemrograman web pertemuan 3.

## HTML
![html5logo](https://github.com/antonmartinus72/Lab1Web/blob/main/res/hmlt5_logo.png)
HTML (Hypertest Markup Language) merupakan bahasa markup yang digunakan untuk membuat sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai dengan yang diinginkan. HTML saat ini merupakan standar Internet yang didefinisikan dan dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).

## Kerangka Dasar HTML.
Berikut adalah kerangka dasar yang di gunakan dalam tag HMTL.
![code](https://github.com/antonmartinus72/Lab1Web/blob/main/Img/1b.jpg)

Keseluruhan html masih terlihat kosong tetapi pada baris 4 terdapat tag "<title>" yang berfungsi membuat judul halaman yang muncul pada tab browser.
![screenshoot](https://github.com/antonmartinus72/Lab1Web/blob/main/img/1a.jpg)

## Heading pada HTML
Heading pada html dapat dijadikan sebagai judul topik atau pembahasan.
![screenshoot](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/2a.jpg)

Jika diperhatikan setiap heading memiliki ukuran font yang berbeda. Ukuran ini adalah ukuran default yang diterapkan html.
Dapat di tulis seperti berikut :

![code](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/2b.jpg)
## Paragraf dan Horizontal Line
Dapat dilihat di bawah ***Heading 6*** terdapat garis horizontal, garis ini menggunakan tag `<hr>` .
![code](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/3.jpg)
Di bawah garis`<hr>` terdapat tag `<p>...</p>` yang digunakan untuk membuat sebuah paragraf. 
![code](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/3_code.jpg)

Parafgraf `<p>...</p>` juga dapat menggunakan atribut berikut :

 **Atribut `align="left"`.**
![ss_left](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/3a_code.jpg)
 
 **Atribut `align="right"`.**
![ss_right](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/3b_code.jpg) 

**Atribut `align="center"`.**
![ss_center](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/3c_code.jpg)

Jika di bandingkan, ketiganya membentuk posisi yang berbeda. Untuk paragraf tanpa atribut `align` jika dibandingkan dengan menggunakan atribut dengan value`align="left"` tidak terlihat perbedaan apapun. Ini karena nilai default untuk tag `<p>...</p>` sama seperti `align="left"`.

## Preformatted Text.
Jika kita perhatihan, pada tag paragraf `<p>` spasi dan enter akan di abaikan dan hanya akan di cetak satu kali, tidak peduli seberapa banyak kita memasukannya secara berulang.
Jika kita ingin spasi dan enter ditampilkan sesuai seberapa banyak yang kita tulis, maka dapat menggunakan tag `<pre>...</pre>`(**Preformatted Text**) atau format text sesuai yang kita masukan di dalam file html.
![ss_center](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/4.jpg)
Text yang ditampilkan berbeda meskipun format penulisan text di dalam html sama.
![ss_center](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/4_code.jpg)
## Break Line
Text dalam html juga dapat dipisah menggunakan tag `<br>`**(Break Line)**. 
![ss](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/5.jpg)
Text setelah tag `<br>` akan di letakan di baris bawah text sebelum tag `<br>`.
![code](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/5_code.jpg)

## Text Format
Dalam penulisan test tidak jarang kita membutuhkan penanda pada kosakata atau  kalimat yang memudahkan kita untuk menyadari jika terdapat maksud yang di tekankan pada text, kosakata atau kalimat.

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

Berikut tampilan jika di terapkan dalam paragraf :
![ss](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/6.jpg)
![code](https://github.com/antonmartinus72/Lab1Web/blob/main/mgi/6_code.jpg)
