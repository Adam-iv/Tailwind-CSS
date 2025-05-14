
Penjelasan CSS Grid 

Pada umumnya untuk mengatur layout sebuah website bisanya menggunakan CSS Flexbox dan CSS Grid, namun kedua CSS tersebut bukanlah kompetitor keduanya sama-sama dibutuhkan dan dapat saling berkolaborasi untuk menyusun layout yang kompleks.
Akan tetapi pada artikel ini saya hanya menjelaskan salah satu CSS saja yaitu CSS Grid.
Secara sederhana CSS Grid adalah CSS yang dapat membagi kolom pada website menjadi beberapa bagian sesuai yang diinginkan, baik secara horizontal maupun vertikal.
Penggunaan CSS Grid bertujuan untuk mempermudah developer untuk membuat layout dari design yang telah dibuat

Dasar-dasar CSS Grid

Sebelum mengetahui cara menggunakan CSS grid, berikut elemen-elemen penting yang perlu kamu ketahui:

Baris (row) dan kolom (column): elemen ini menjadi struktur dasar dari CSS grid. Baris adalah elemen horizontal, sedangkan kolom adalah elemen vertikal. Keduanya bersama-sama membentuk kerangka kerja untuk meletakkan konten.

Garis (line): garis adalah pembatas antara baris dan kolom. Dengan menentukan nomor garis, kamu bisa menempatkan item di area yang diinginkan.

Sel (cell): sel adalah ruang antara garis vertikal dan horizontal. Elemen ini berguna sebagai tempat untuk meletakkan konten.

Area: area adalah ruang yang dibentuk dari beberapa sel, memungkinkan kamu untuk mengelompokkan elemen.

Gap: gap adalah jarak antara baris dan kolom, memberikan ruang antar elemen.

Kontainer (container): container adalah elemen utama yang mengandung grid. Di sini, kamu akan mendefinisikan struktur grid.

Item: item adalah elemen yang ditempatkan di dalam grid.


Fungsi CSS Grid

Berikut adalah beberapa fungsi yang dapat diimplementasikan pada CSS grid:

Mengatur Baris dan Kolom: CSS Grid dapat mempermudah dalam mengatur pembuatan tata letak yang dinamis dalam bentuk baris dan kolom.

Mengatur Ukuran dan Posisi Elemen: CSS Grid dapat mengatur ukuran elemen grid. Contoh properti yang digunakan yaitu seperti grid-column, grid-row, grid-template-columns, dan grid-template-rows.

Mengatur Tata Letak Responsif: CSS Grid dapat mengatur untuk membuat desain website yang responsif dan sesuai dengan ukuran layar. Contoh properti yang digunakan yaitu seperti grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));

Mengatur Jarak Antar Elemen (Gap): CSS Grid dapat mengatur jarak antar elemen tanpa menggunakan padding atau margin. Properti yang digunakan yaitu gap, row-gap, dan column-gap.


Penerapan CSS Grid

 Disini kita mempunya 4 line kolom dan 3 line row, dengan masing masing 3 kotak di atas dan 3 kotak dibawah berikut codenya  : 

code html

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grid CSS</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div class="top-left">Top Left</div>
      <div class="top-right">Top Right</div>
      <div class="content">Content</div>
      <div class="bottom-left">Bottom Left</div>
      <div class="bottom-center">Bottom Center</div>
      <div class="bottom-right">Bottom Right</div>
    </div>
  </body>
</html>
```

code css

```
<style>
.container {
  margin-top: 20vh;
  display: grid;
  grid-template-columns: auto auto auto;
  grid-gap: 10px;
  background-color: coral;
  padding: 12px;
}

.container > div {
  background-color: skyblue;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  padding: 3em;
  border: 3px solid black;
}

.top-left {
  grid-column: 1/2;
}

.top-right {
  grid-column: 2/3;
}

.content {
  grid-column: 3/4;
}

.bottom-left {
  grid-column: 1/2;
}

.bottom-center {
  grid-column: 2/3;
}

.bottom-right {
  grid-column: 3/4;
}
</style>
```

Dapat dilihat dari code yang terdapat pada CSS masing masing divnya hanya mengambil 1/3 dari besar layar pada browser.

#1 Grid Column

Lalu bagaimana jika kita ingin merubah kotaknya dengan kotak contentnya memenuhi panjang browsernya dan kotak top left dan top right memenuhi ujung atas dari layar browsernya seperti berikut : 

Maka yang perlu dilakukan adalah merubah grid-column pada class top left menjadi 1/2 , merubah-grid column pada class top right menjadi 2/3 dan merubah grid-column pada class content menjadi 1/4.

Berikut code CSS yang telah dirubah

```
<style>
.container {
  margin-top: 20vh;
  display: grid;
  grid-template-columns: auto auto auto;
  grid-gap: 10px;
  background-color: coral;
  padding: 12px;
}

.container > div {
  background-color: skyblue;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  padding: 3em;
  border: 3px solid black;
}

.top-left {
  grid-column: 1/2;
}

.top-right {
  grid-column: 3/4;
}

.content {
  grid-column: 1/4;
}

.bottom-left {
  grid-column: 1/2;
}

.bottom-center {
  grid-column: 2/3;
}

.bottom-right {
  grid-column: 3/4;
}
</style>
```

Setelah melakukan perubahan code CSS diatas dapat dilihat sekarang kita mempunyai 1 tambahan line row secara otomatis yang sekarang menjadi 4 line row. 

#2 Grid Row

caranya cukup sederhana seperti jika kita ingin menyesuaikan grid kolomnya kita hanya harus merubah grid-column pada kelas yang diinginkan, 
begitu juga dengan row jika kita ingin menyesuaikan grid rownya maka kita harus menambahkan property grid-row pada class yang diinginkan seperti pada code berikut : 

```
<style>
.container {
  margin-top: 20vh;
  display: grid;
  grid-template-columns: auto auto auto;
  grid-gap: 10px;
  background-color: coral;
  padding: 12px;
  grid-auto-rows: minmax(100px, auto);
}

.container > div {
  background-color: skyblue;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  padding: 3em;
  border: 3px solid black;
}

.top-left {
  grid-column: 1/2;
  grid-row: 1/3;
}

.top-right {
  grid-column: 3/4;
}

.content {
  grid-column: 2/4;
}

.bottom-left {
  grid-column: 1/2;
}

.bottom-center {
  grid-column: 2/3;
}

.bottom-right {
  grid-column: 3/4;
}
</style>

```

Pada class container kita akan menambahkan code " grid-auto-rows: minmax(100px, auto);" yang fungsinya adalah menentukan mininmal rownya adalah 100px dan maksimal rownya adalah auto. 
Pada class top-left kita tambahkan grid-row : 1/3 yang fungsinya adalah untuk membuat panjang row dari line 1 sampai line 3 dan pada class content kita merubah grid-columnya agar dapat di isi oleh class top-left.
