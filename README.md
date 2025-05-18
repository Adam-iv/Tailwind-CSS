# **KELOMPOK 4**
**Nama Kelompok:**

1. Adam Izmu Vriezgi
2. Alisia Maulidina
3. Fathurrahman
4. Wahyu Saputra
5. Robby Sugaea
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

