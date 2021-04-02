# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
~~~
## Langkah 1 
Persiapan membuka VSCode dan Browser.
Buka VScodedan buat file HTML baru, setelah itu buat struktur dasar HTML.
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar </title>
</head>
<body>
</body>
</html>
~~~
![1 1](https://user-images.githubusercontent.com/81820421/113442325-0b9f9380-941a-11eb-9bc8-ed443efe6c38.JPG)
![1](https://user-images.githubusercontent.com/81820421/113442326-0cd0c080-941a-11eb-954f-481f712beb2e.JPG)


## Langkah 2
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
~~~
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p> 
 ~~~
 
![2 1](https://user-images.githubusercontent.com/81820421/113442471-4f929880-941a-11eb-9468-e74b141d2c04.JPG)
![2](https://user-images.githubusercontent.com/81820421/113442475-50c3c580-941a-11eb-9afb-6cb78f8639df.JPG)

## Langkah 3

Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
 ~~~
 
![3](https://user-images.githubusercontent.com/81820421/113443392-1a874580-941c-11eb-9583-8b2f0d7589c7.JPG)

![3 1](https://user-images.githubusercontent.com/81820421/113442556-718c1b00-941a-11eb-8dea-38bd128cc2d6.JPG)


Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
~~~
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
~~~

![4](https://user-images.githubusercontent.com/81820421/113443430-2d017f00-941c-11eb-8124-3895fcb44580.JPG)


![4 1](https://user-images.githubusercontent.com/81820421/113442630-97192480-941a-11eb-9b03-8af415eb2c7d.JPG)

## LANGKAH 4
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
~~~
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
~~~

  ![5](https://user-images.githubusercontent.com/81820421/113443455-37bc1400-941c-11eb-83d1-9869b8479748.JPG)

![5 1](https://user-images.githubusercontent.com/81820421/113442769-de9fb080-941a-11eb-9789-d6ce8690e08c.JPG)

## LANGKAH 5
~~~
Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html.
~~~
![5](https://user-images.githubusercontent.com/81820421/113443523-5a4e2d00-941c-11eb-851f-9e723d8c8628.JPG)


![5 1](https://user-images.githubusercontent.com/81820421/113443037-5cfc5280-941b-11eb-8461-0f39ccb6f7eb.JPG)
![logo](https://user-images.githubusercontent.com/81820421/113442898-1a3a7a80-941b-11eb-8467-8dad0e32b1f4.JPG)

## LANGKAH 6
~~~
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>  
  ~~~
![6](https://user-images.githubusercontent.com/81820421/113443548-6803b280-941c-11eb-9715-1655d9066535.JPG)

![6 1](https://user-images.githubusercontent.com/81820421/113442994-4a821900-941b-11eb-8988-6a1bc68708ea.JPG)

## JAWAB PERTANYAAN

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
~~~
Ya pasti ada ERROR karena codingan setiap huruf besar dan kecil tanda koma dan titik juga harus sama ,kalau tidak sama menjadi error.
~~~
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!

~~~
Paragraf pada dokumen HTML dibuat dengan tag <p>. Selain itu ada tag pendukung lainnya seperti 
<br>, <hr>, <pre>.
<br>: break-line (untuk berpindah ke baris selanjutnya)
~~~

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

~~~
img menunjukkan image yang berarti gambar dan oleh karenanya digunakan untuk menyisipkan gambar. Gambar didalam sebuah dokumen HTML tidak dimasukkan sepenuhnya pada file (.html, misalnya) akan tetapi, hanya merujukkan file sumber gambar tersebut berada (disimpan).

alt
Menunjukkan sebuah alternate text (teks pengganti) yang akan muncul apabila gambar tidak dapat ditampilkan.

Contoh:

<img src="https://www.apacara.com/logo.png" alt="logo apacara.com" />
tulisan "logo apacara.com" akan muncul apabila gambar logo.png tidak dapat ditampilkan.

Ketika gambar di tampilkan akan terlihat sebuah title. sedangkan, jika gambar gagal ditampilkan akan menampilkan teks atribut alt.
~~~

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
 ~~~
 kedua atribut harus di isi semua, karena jika hanya salah satunya maka gambar tersebut akan terlihat terlalu lebar atau tinggi.
 ~~~
 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, 
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

~~~
Telah di tentukan, untuk blank akan menambah tab baru terlebih dahulu maka akan menampilkan link yang dituju.
~~~



