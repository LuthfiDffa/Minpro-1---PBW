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

* **Tampilan**: Bar navigasi yang bersih di bagian atas dengan logo dan menu link yang akan berubah warna saat di-*hover*.
* **Penjelasan Kode**: Menggunakan komponen `navbar` dari Bootstrap 5 dengan kelas `fixed-top` agar navigasi tetap terlihat saat pengguna men-scroll halaman.

### 2. Home
<img width="1895" height="862" alt="image" src="https://github.com/user-attachments/assets/4cbb5a70-6f05-435f-bb69-fb3318a1dee7" />


### 3. Fitur / Services
* **Tampilan**: Daftar layanan atau fitur yang ditampilkan dalam bentuk kartu (cards).
* **Penjelasan Kode**: Di bagian ini, saya menggunakan **Vue.js** dengan direktif `v-for`. Jadi, data fitur disimpan dalam sebuah *array* objek, lalu diulang secara otomatis ke dalam komponen `card` Bootstrap. Ini membuat kode jauh lebih ringkas daripada menulis HTML manual satu per satu.

### 4. Form Interaktif / Kontak
* **Tampilan**: Formulir input di bagian bawah bagi pengguna untuk meninggalkan pesan.
* **Penjelasan Kode**: Menggunakan fitur `v-model` dari Vue.js untuk melakukan *two-way data binding*. Artinya, apa pun yang diketik user akan langsung tersimpan di variabel Vue dan bisa diproses (misal: memunculkan notifikasi "Berhasil" lewat `v-on:click`).

### 5. Footer
* **Tampilan**: Bagian bawah berisi informasi hak cipta dan link media sosial.
* **Penjelasan Kode**: Dibuat sederhana menggunakan tag `<footer>` dengan utility class dari Bootstrap untuk pengaturan warna latar belakang dan padding.

---
