# MINI PROJECT PBW 1
## LUTHFI DAFFA PURBAYA
## 2409116102

---

## Teknologi yang Digunakan:
* **HTML**: Sebagai kerangka utama struktur halaman.
* **CSS**: Untuk styling  dan kustomisasi desain.
* **Bootstrap 5**: Framework yang digunakan untuk mempercepat pembuatan layout.
* **Vue.js**: Digunakan untuk menangani logika data secara reaktif dan manipulasi DOM agar lebih dinamis.

---

## 🎨 Tampilan & Fitur Utama

### 1. Navbar (Navigasi)
<img width="1905" height="66" alt="image" src="https://github.com/user-attachments/assets/2af5bc2f-bf85-4e26-b926-cf4c941c0df9" />

* **Tampilan**: Bar navigasi di bagian atas yang pada ssaat ditekan akan langsung mengarah ke halaman tertuju.
* **Penjelasan Kode**:Navbar dibuat menggunakan komponen navbar dari Bootstrap 5 dengan kelas navbar-expand-lg agar responsif dan fixed-top agar tetap berada di atas saat halaman di-scroll. Menu navigasi menggunakan anchor link (href="#section") sehingga dapat langsung mengarah ke section yang dituju.

### 2. Home
<img width="1895" height="862" alt="image" src="https://github.com/user-attachments/assets/4cbb5a70-6f05-435f-bb69-fb3318a1dee7" />

* **Tampilan**: Section ini menampilkan foto profil berbentuk kotak, nama lengkap dengan ukuran besar, deskripsi singkat (tagline), serta tombol “Tentang Saya”. Tata letak dibuat center.
* **Penjelasan Kode**: Home/Hero section dibuat menggunakan class Bootstrap d-flex align-items-center untuk memposisikan konten secara vertikal di tengah layar. Nama dan tagline ditampilkan menggunakan Vue.js dengan interpolation {{ }} sehingga data dapat dikelola melalui objek data() pada Vue. Tombol menggunakan class btn btn-primary dari Bootstrap untuk konsistensi desain.

### 3. About Me
<img width="1896" height="507" alt="image" src="https://github.com/user-attachments/assets/ccd044ee-8641-49a3-945a-3f06bbdf2a97" />

* **Tampilan**: Section ini berisi deskripsi diri, daftar pengalaman, serta daftar skill yang ditampilkan dalam bentuk progress bar.
* **Penjelasan Kode**: Layout dibuat menggunakan sistem grid Bootstrap (row, col-lg-6). Progress bar menggunakan komponen progress dari Bootstrap. Data skill ditampilkan menggunakan directive v-for dari Vue.js untuk melakukan looping array skills. Lebar progress bar diatur secara dinamis menggunakan binding :style="{ width: skill.level + '%' }".
  
### 4. Certificates
<img width="1894" height="705" alt="image" src="https://github.com/user-attachments/assets/b00d3479-3fa6-4171-a63e-d7e70185f777" />


* **Tampilan**: Section ini menampilkan daftar sertifikat dalam bentuk card dengan layout grid tiga kolom pada layar besar. Setiap card berisi judul sertifikat, penyelenggara, dan tahun.
* **Penjelasan Kode**: Card dibuat menggunakan komponen card dari Bootstrap 5. Layout grid menggunakan col-md-4 agar menjadi tiga kolom pada layar medium ke atas. Data sertifikat ditampilkan menggunakan Vue.js dengan directive v-for, sehingga setiap objek dalam array certificates otomatis dirender menjadi card baru.
  
### 5. Footer
<img width="1906" height="143" alt="image" src="https://github.com/user-attachments/assets/928bc3b9-54ea-48be-a5f4-4d28b6f53ef4" />

* **Tampilan**: Bagian bawah berisi informasi hak cipta dan username media sosial.
* **Penjelasan Kode**: Dibuat sederhana menggunakan tag `<footer>` dengan utility class dari Bootstrap untuk pengaturan warna latar belakang dan padding.

---

### Penggunaa Vue.Js
Tampilan: Data seperti nama, tagline, skill, dan sertifikat dapat ditampilkan secara dinamis tanpa perlu menulis ulang HTML.
Penjelasan Kode: Vue diinisialisasi menggunakan createApp() dan di-mount ke elemen dengan id #app. Fitur yang digunakan meliputi:
- Interpolation {{ }}
- Looping data v-for
- Binding atribut :style
- Struktur dasar Vue data()
Website tetap bersifat statis, namun Vue digunakan untuk meningkatkan keteraturan dan efisiensi pengelolaan data.

### Penggunaan Bootstrap 5
Website memiliki tampilan yang rapi, modern, dan responsif pada berbagai ukuran layar.
Bootstrap digunakan untuk:
- Navbar
- Grid System (container, row, col)
- Card
- Button
- Progress bar
- Responsive utilities
Penggunaan Bootstrap mempercepat proses styling dan memastikan konsistensi desain.
