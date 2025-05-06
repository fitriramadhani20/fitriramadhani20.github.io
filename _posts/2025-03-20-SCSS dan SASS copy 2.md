---
layout: post
title : <div class="bubble-effect blog-title">SCSS dan SASS</div>
---

penjelasan tentang SCSS dan SASS

![SCSS dan SASS]

---

## Pengertian SCSS dan SASS

SASS (Syntactically Awesome Stylesheets) adalah sebuah preprocessor untuk CSS yang dirancang agar penulisan kode CSS menjadi lebih efisien, mudah dibaca, dan dikelola. SASS memungkinkan developer menggunakan fitur pemrograman seperti variabel, nested rules (penulisan bersarang), mixins, inheritance, dan lainnya, yang tidak tersedia dalam CSS biasa.

SCSS (Sassy CSS) adalah sintaks atau format penulisan dari SASS yang mirip dengan CSS standar. Perbedaan utamanya adalah:

SASS menggunakan sintaks yang lebih ringkas tanpa kurung kurawal {} dan titik koma ;

SCSS menggunakan sintaks seperti CSS biasa, dengan kurung kurawal dan titik koma, sehingga lebih familiar bagi yang sudah terbiasa dengan CSS


Kedua format ini harus dikompilasi terlebih dahulu menggunakan tools seperti Dart Sass, Node-sass, atau bundler seperti Webpack, agar bisa dijalankan di browser sebagai CSS biasa.


---

## Fungsi dan Kegunaan SASS/SCSS

1. Mempermudah Penulisan CSS
Dengan fitur seperti nesting, variabel, dan mixin, penulisan CSS menjadi lebih bersih dan terstruktur.


2. Menggunakan Variabel
Variabel memungkinkan penyimpanan nilai seperti warna, ukuran font, dan lainnya untuk digunakan berulang kali.


3. Nesting (Penulisan Bersarang)
Menyederhanakan selektor yang bersarang, seperti dalam elemen HTML yang memiliki struktur hirarki.


4. Modularisasi Kode
Memungkinkan pemisahan kode ke dalam beberapa file (dengan @import atau @use) yang bisa digabung saat kompilasi.


5. Mixins dan Functions
Digunakan untuk membuat blok kode yang dapat digunakan kembali dengan parameter seperti fungsi pada bahasa pemrograman.


6. Inheritance (@extend)
Memungkinkan elemen untuk mewarisi properti dari selector lain.


7. Operasi Matematika
Mendukung perhitungan seperti penambahan, pengurangan, dan penggunaan satuan (px, em, rem, dll).


8. Lebih Konsisten dan Terorganisir
Sangat membantu dalam proyek besar agar pengelolaan style menjadi rapi dan scalable.

---

<img src="/assets/images/scss.png" alt="scss.png">
