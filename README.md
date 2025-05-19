# **KELOMPOK 4**
**Nama Kelompok:**

1. Adam Izmu Vriezgi
2. Alisia Maulidina
3. Fathurrahman
4. Wahyu Saputra
5. Robby sugara
---
# **📌 Penjelasan Mengenai Git&Github**
## ✏️ Pengertan Git
Git adalah sebuah *Version Control System* (VCS) terdistribusi yang digunakan untuk mengelola perubahan pada file atau repository suatu proyek.  Sistem ini memungkinkan para pengembang perangkat lunak untuk berkolaborasi secara efisien, melacak riwayat perubahan kode, serta kembali ke versi sebelumnya jika diperlukan.
## 📋 Perintah Dasar Git
1. **Commit:** Untuk menyimpan perubahan ke dalam repositori versi lokal.
2. **Branch:** Fitur yang membuat jalur pengembangan terpisah dari main branch.
3. **Merge:** Proses menggabungkan perubahan dari satu branch ke branch yang lain.
4. **Remote:** Mengelola repositori dari jarak jauh.
5. **Push:** Memindahkan perubahan lokal ke repositori jarak jauh.
6. **Pull:** Mengunduh dan menggabungkan perubahan dari repositori jarak jauh ke repositori lokal.
7. **Clone:** Membuat salinan lokal dan repositori jarak jauh.
## 🧩 Fungsi Git
1. **Untuk berkolaborasi**

   Memanfaatkan Git untuk mengerjakan proyek dengan kerja sama tim.
2. **Proyek open source**

   Git adalah toolh yang bersifat open source, sehingga dapat digunakan untuk membuat perangkat lunak open source.
3. **Membantu organisir**

   Git bisa menyimpan proyek ke folder dalam bentuk v1, v2, v3, dan juga memiliki sau proyek yangmengggunakan database khususyang berisi semua versi file.
4. **Sebagai platform fleksibilitas**

   Karena dapat digunakan sebagai solusi untuk hosting pada semua proyek
5. **Menjadi backup**

   Jika terjadi kesalahan dalam melakukan pengembangan, git dapat dengan mudah mengembalikan menjadi versi sebelumnya.
## **✏️ Pengertian Github**
Github adalah sebuah platform online berbasis web yang digunakan oleh pengembang perangkat lunak untuk menyimpan dan mengelola kode serta mendokumentasikan dan mengontrol perubahannya.
## **📋 Perintah Dasar Github**
1. **Commit:** Menyimpan perubahan dengan pesan commit.
2. **Branch:** Fitur yang membuat jalut pengembang terpisah dari main branch.
3. **Remote:** Menampulkan URL repositori.
4. **Fetch:** Mengambil perubahan terbari tanpa menggabungkannya.
5. **Push:** Mengirim perubahan dari lokal ke github.
## **🧩 Fungsi Github**
1. **Kontrol versi kode**

   Memungkinkan untuk kembali keversi sebelumnya jika terjadi kesalahan.
2. **Kolaborasi tim**

   Fitur pull request dan code review mempermudah kerja tim.
3. **Menyimpan kode di cloud**

   kode bisa diaksen dari mana saja.
4. **Manajemen proyek**

   Github menyediakan issues, milestones, dan project board untuk mengatur tugas dan fitur seperti trello.
5. **Integritas DevOps**

   Mendukung otomatisasi workflow seperti build, test, dan deploy dengan github actions.
6. **Open source**
   
   banyak open source besar seperti react dan node.js di-host di github.
7. **Dokumentasi proyek**

   Bisa menambah dokumentadi engggunakan file README.md.
8. **Kontrol akses**

   Bisa membuat repositori publik atau privat.
---
# **📌 Penjelasan CSS Flexbox**
## **✏️ Pengertian CSS Flexbox**
Flexbox adalah sistem tata letak di CSS yang dirancang untuk menyusun, meratakan, dan membagi ruang di antara elemen-elemen dalam sebuah container bahkan ketika ukuran elemen atau container-nya bersifat dinamis atau belum diketahui secara pasti.
Seiring dengan semakin beragamnya perangkat yang digunakan untuk mengakses web, tampilan situs harus bisa menyesuaikan diri secara responsif terhadap berbagai ukuran layar. Flexbox hadir sebagai solusi yang efektif untuk memenuhi kebutuhan ini.
## **💡 Konsep dasar**
- **Flex containers**

  Flex container adalah elemen dasar dalam flexbox. Saat kamu menetapkan sebuah elemen sebagai flex container ( menggunakan display: flex atau display: inline-flex), semua elemen anak dari elemen tersebut menjadi flex item.
- **Flex items**

  Flex item adalah elemen-elemen yang berada di dalam flex container. Salah satu hal unik dari Flexbox adalah kamu memiliki kontrol besar atas bagaimana item ini harus tumbuh, menyusut, dan bagaimana harus diselaraskan terhadap satu sama lain.
- **Main axis and cross axis**

  Flexbox bekerja berdasarkan dua sumbu: sumbu utama (main axis) dan sumbu lintang (cross axis).
Sumbu utama adalah arah di mana flex item diletakkan secara berurutan di dalam container. Sedangkan sumbu lintang adalah sumbu yang tegak lurus terhadap sumbu utama.
- **Penyelarasan (alignment)**

  Flexbox menyediakan serangkaian properti untuk memudahkan menyelaraskan item, baik di sumbu utama maupun lintang. Properti seperti align-items, align-self, justify-content, dan align-content memungkinkan kamu mengontrol penyelarasan ini.
- **Fleksibilitas (Flexibility)**

  Flex item bisa diatur agar "tumbuh" atau "menyusut" untuk mengisi ruang yang tersedia di flex container. Artinya, di container yang memiliki ruang ekstra, item dapat diatur untuk memperluas ukurannya. Sementara di container yang terlalu penuh, item bisa diatur untuk menyusut.

## **📋 Properti penting dalam CSS Flexbox**
- **Display**

  Display adalah titik awal dai flexbox. Dengan menetapkan value flex atau inline-flex pada properti display suatu elemen, kamu mengubahnya menjadi flex container yang berarti elemen anaknya menjadi flex item.
- **Flex-direction**

  Display adalah titik awal dai flexbox. Dengan menetapkan value flex atau inline-flex pada properti display suatu elemen, kamu mengubahnya menjadi flex container yang berarti elemen anaknya menjadi flex item.
- **Justify-content**

  Properti justify-content dipakai untuk menentukan bagaimana flex item harus didistribusikan di sepanjang sumbu utama container. Properti ini berguna untuk penyelarasan dan penyeimbangan ruang antar item.
- **Align-items**

  Jika justify-content bekerja pada main axis, align-items fokus pada cross axis.
Properti ini berguna untuk mengatur posisi item secara vertikal (atau horizontal, tergantung arah flex). Kamu bisa memilih value seperti flex-start  (value default dari align-items), flex-end, center, baseline, atau stretch untuk mengontrol bagaimana item tersebut diselaraskan dan mendistribusikan ruang yang tersedia.
- **Flex-grow, flex-shrink, dan flex-basis**
  Ketiga properti ini bekerja bersama untuk menentukan bagaimana flex item tumbuh dan menyusut relatif terhadap yang lain dalam flex container.
flex-grow mengontrol bagaimana item memanfaatkan ruang tambahan, flex-shrink menentukan bagaimana item berkurang saat ruang terbatas, dan flex-basis menetapkan ukuran dasar item sebelum mendistribusikan ruang tambahan.
## **🔍 penerapan dari css-flexbox**
membuat layout navigasi yang responsif.

HTML :
```
<nav class="navbar">
     <a href="#" class="logo">Logo</a>
     <ul class="nav-links">
       <li><a href="#">Home</a></li>
       <li><a href="#">About</a></li>
       <li><a href="#">Services</a></li>
       <li><a href="#">Contact</a></li>
     </ul>
   </nav>
```


CSS :
```
.navbar {
  display: flex;
  justify-content: space-between; 
  align-items: center;
  background-color: #f0f0f0;
  padding: 10px;
}
```

```
.nav-links {
  list-style: none; 
  display: flex; 
  margin: 0; 
  padding: 0; 
}
```

```
.nav-links li {
  margin-left: 15px;
}
```

```
.nav-links li a {
  text-decoration: none; 
  color: #333;
}
```

```
/* Responsive design (opsional) */
@media (max-width: 768px) {
  .nav-links {
    flex-direction: column;
    align-items: flex-start; 
  }
```

```
  .nav-links li {
    margin-left: 0; 
    margin-bottom: 10px;
  }
}
```


## Penjelasan:
- display:

  flex; pada .navbar dan .nav-links membuat elemen-elemen tersebut menjadi flex container dan flex item, yang memungkinkan kita menggunakan properti flexbox.
- justify-content:

  space-between; mengatur item-item dalam .navbar agar tersebar dengan sama rata di sepanjang sumbu utama (horizontal).
- align-items:

  center; mengatur item-item dalam .navbar agar berada di tengah secara vertikal.
- flex-direction:

  column; pada media query membuat navigasi menjadi vertikal pada layar kecil.
- align-items:

  flex-start; pada media query membuat navigasi dimulai dari awal pada layar kecil.

---
# **📌 Penjelasan CSS Grid**
## **✏️ Penjelasan CSS Grid**
Pada umumnya untuk mengatur layout sebuah website bisanya menggunakan CSS Flexbox dan CSS Grid, namun kedua CSS tersebut bukanlah kompetitor keduanya sama-sama dibutuhkan dan dapat saling berkolaborasi untuk menyusun layout yang kompleks.
Akan tetapi pada artikel ini saya hanya menjelaskan salah satu CSS saja yaitu CSS Grid.
## **📋 Dasar-dasar CSS Grid**
Sebelum mengetahui cara menggunakan CSS grid, berikut elemen-elemen penting yang perlu kamu ketahui:

- Baris (row) dan kolom (column): elemen ini menjadi struktur dasar dari CSS grid. Baris adalah elemen horizontal, sedangkan kolom adalah elemen vertikal. Keduanya bersama-sama membentuk kerangka kerja untuk meletakkan konten.

- Garis (line): garis adalah pembatas antara baris dan kolom. Dengan menentukan nomor garis, kamu bisa menempatkan item di area yang diinginkan.

- Sel (cell): sel adalah ruang antara garis vertikal dan horizontal. Elemen ini berguna sebagai tempat untuk meletakkan konten.

- Area: area adalah ruang yang dibentuk dari beberapa sel, memungkinkan kamu untuk mengelompokkan elemen.

- Gap: gap adalah jarak antara baris dan kolom, memberikan ruang antar elemen.

- Kontainer (container): container adalah elemen utama yang mengandung grid. Di sini, kamu akan mendefinisikan struktur grid.

Item: item adalah elemen yang ditempatkan di dalam grid.
## **💡 Fungsi CSS Grid**
Berikut adalah beberapa fungsi yang dapat diimplementasikan pada CSS grid:

- Mengatur Baris dan Kolom: CSS Grid dapat mempermudah dalam mengatur pembuatan tata letak yang dinamis dalam bentuk baris dan kolom.

- Mengatur Ukuran dan Posisi Elemen: CSS Grid dapat mengatur ukuran elemen grid. Contoh properti yang digunakan yaitu seperti grid-column, grid-row, grid-template-columns, dan grid-template-rows.

- Mengatur Tata Letak Responsif: CSS Grid dapat mengatur untuk membuat desain website yang responsif dan sesuai dengan ukuran layar. Contoh properti yang digunakan yaitu seperti grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));

- Mengatur Jarak Antar Elemen (Gap): CSS Grid dapat mengatur jarak antar elemen tanpa menggunakan padding atau margin. Properti yang digunakan yaitu gap, row-gap, dan column-gap.
## **🔍 Penerapan CSS Grid**
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
----
# 📌 Penjelasan Tailwind CSS
## 🌀 Pengertian Tailwind CSS
Tailwind CSS adalah framework CSS berbasis utility-first, yang artinya ia menyediakan class-class kecil (utility classes) untuk membangun desain langsung di markup HTML-mu. Contaohnya seperti ```bg-blue-500```, ```text-white```, ```px-4```, dan utility class lainnya.
## ⚙️ Fitur Utama Tailwind CSS
1. **Utility-firs**
   
     Tailwind menyediakan ribuan utility classes seperti ```text-center```, ```text-xl```, ```text-gray-70```,  ```grid, flex```, ```justify-between```, dll
2. **Customizable**

   Menggunakan file konfigurasi ```tailwind.config.js``` kamu bisa Menambahkan warna, ukuran, atau breakpoints baru
3. **Responsive & Dark Mode**

   Built-in support untuk responsivitas dan dark mode ```md:text-lg```, ```lg:flex```, ```dark:bg-gray-900```

4. **JIT (Just-In-Time) Engine**

   Hanya menghasilkan CSS yang kamu gunakan, sehingga ukuran file lebih kecil dan cepat.

## ✅ Kelebihan Tailwind CSS
- Cepat membangun antarmuka tanpa menulis CSS manual.
- Konsisten karena semua komponen dibangun dari utility class yang sama.
- Responsive design sangat mudah dibuat.
- Cocok untuk desain custom tanpa tergantung pada komponen UI dari framework lain seperti Bootstrap.

## ❌ Kekurangan Tailwind CSS
- HTML bisa terlihat penuh class (terkesan "berantakan").
- Butuh waktu untuk terbiasa dengan naming class.
- Tidak seperti Bootstrap, tidak ada komponen siap pakai (kamu membangun sendiri dari nol atau pakai UI kit seperti Tailwind UI).

## ✔️Implementasi Tailwind CSS
mplementasi Tailwind CSS berarti menggunakan kerangka kerja CSS ini untuk membuat desain web. Tailwind CSS memungkinkan pengembang untuk membuat tampilan web dengan mudah dan cepat, terutama dengan menggunakan kelas utilitas yang telah disediakan. 

**Utility Class:**
```
bg-blue-500, text-white, px-4
<button class="bg-blue-500 text-white px-4 py-2 rounded">
  Klik Saya
</button>
Implementasi: Menggunakan utility classes dasar (bg-, text-, px-, py-) seperti yang dijelaskan dalam pengantar Tailwind.
```

**Utility-first:** 
```
text-center, text-xl, text-gray-700
<h1 class="text-center text-xl text-gray-700">
  Selamat Datang di Tailwind
</h1>
Implementasi: Menunjukkan bagaimana utility class dapat langsung digunakan tanpa CSS custom — sesuai fitur Utility-first.
```

**Customizable:**
```
Konfigurasi Warna
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      colors: {
        'brand-primary': '#1e40af',
      }
    }
  }
}
<div class="bg-brand-primary text-white p-4">
  Warna Kustom dari Config
</div>
Implementasi: Menambahkan warna kustom menggunakan tailwind.config.js, sesuai fitur Customizable.
```


**Responsive:**
```
md:text-lg, lg:flex
<div class="text-base md:text-lg lg:flex">
  Teks ini responsif tergantung ukuran layar.
</div>
Implementasi: Mendemonstrasikan responsive design built-in seperti disebut di fitur ke-3.
```
**Dark Mode:**
```
dark:bg-gray-900
<div class="bg-white dark:bg-gray-900 text-black dark:text-white p-4">
  Mode terang dan gelap otomatis.
</div>
Implementasi: Menunjukkan dukungan untuk dark mode, sesuai fitur bawaan Tailwind.
```
**JIT Engine:**
```
Class Otomatis
<p class="text-[22px] text-[#ff5722]">
  Teks dengan ukuran dan warna custom menggunakan JIT
</p>
Implementasi: Kelas tidak standar (text-[22px], text-[#ff5722]) tetap bisa digunakan berkat JIT Engine.
```
**Antarmuka Cepat:**
 ```
Komponen UI tanpa CSS
<div class="shadow-lg p-6 rounded bg-white">
  <h2 class="text-xl font-bold">Card</h2>
  <p class="text-gray-600">Ini card tanpa tulis CSS sama sekali.</p>
</div>
Implementasi: Bangun UI cepat langsung di HTML tanpa menulis CSS — sesuai kelebihan utama Tailwind.
```
**Desain Konsisten dengan Utility Class**
 ```
<div class="grid grid-cols-2 gap-4">
  <div class="bg-gray-100 p-4">Box 1</div>
  <div class="bg-gray-100 p-4">Box 2</div>
</div>
Implementasi: Gunakan utility class yang konsisten untuk semua komponen — seperti disebut dalam kelebihan Tailwind.
```
**Desain Responsif Mudah**
```
<img src="foto.jpg" class="w-full md:w-1/2 rounded-lg" />
Implementasi: Hanya dengan 2 class, membuat gambar yang responsif — mendukung kelebihan “Responsive design sangat mudah dibuat”.
```
**HTML Penuh Class (Kekurangan)**
 ```
<div class="bg-white border border-gray-300 p-4 text-sm text-gray-700 rounded shadow-sm hover:bg-gray-100 transition-all duration-300">
  Contoh elemen dengan banyak class
</div>
Implementasi: Menunjukkan kekurangan yang disebutkan — HTML menjadi penuh class, tampak “berantakan”.
```
