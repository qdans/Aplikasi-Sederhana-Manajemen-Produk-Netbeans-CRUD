# Aplikasi Manajemen Produk Sederhana (CRUD) dengan Java & MySQL

Aplikasi ini adalah sistem manajemen produk berbasis Java yang menggunakan MySQL sebagai database. Dibangun dengan **NetBeans** dan didukung oleh **Java Swing**, aplikasi ini memungkinkan pengguna untuk melakukan operasi **CRUD** (Create, Read, Update, Delete) pada data produk dengan antarmuka yang user-friendly.

## ✨ Fitur Utama
- **CRUD Produk** – Tambah, lihat, perbarui, dan hapus data produk dengan mudah.
- **Terintegrasi dengan MySQL** – Data produk disimpan dan dikelola melalui database MySQL.
- **Antarmuka Grafis (GUI)** – Menggunakan Java Swing untuk pengalaman pengguna yang lebih interaktif.
- **Dukungan NetBeans** – Dikembangkan dalam lingkungan NetBeans, memudahkan pengelolaan proyek.

Aplikasi ini cocok bagi pemula yang ingin memahami bagaimana Java berinteraksi dengan MySQL dalam proyek berbasis desktop.

---

## 📌 Cara Instalasi & Penggunaan

### **1. Unduh dan Ekstrak Proyek**
- Unduh file **ZIP** dari repositori ini.
- Ekstrak file ZIP ke dalam folder lokal.

### **2. Buka Proyek di NetBeans**
- Jalankan **NetBeans**.
- Pilih **Open Project** dan arahkan ke folder proyek yang telah diekstrak.
- Tunggu hingga NetBeans selesai memuat proyek.

  <details>
  <summary>Screenshot NetBeans</summary>
  <img src="https://github.com/user-attachments/assets/a52388d0-d1cb-4469-86f8-dffc98a039fb"/>
  </details>

### **3. Instal & Jalankan XAMPP**
- Jika belum memiliki **XAMPP**, unduh dan instal dari [situs resmi XAMPP](https://www.apachefriends.org/download.html).
- Buka **XAMPP Control Panel**.
- Klik tombol **Start** pada **Apache** dan **MySQL**.

  <details>
  <summary>Screenshot XAMPP</summary>
  <img src="https://github.com/user-attachments/assets/2cecc0ca-d783-488a-aac9-992bfc77150b"/>
  </details>

### **4. Konfigurasi Database**
- Buka browser dan akses **`http://localhost/phpmyadmin/`**.
- Buat database baru dengan nama **`product`**.
- Klik **Import**, lalu pilih file **`product.sql`** dari folder proyek.
- Klik **Go** untuk memproses impor database.

  <details>
  <summary>Screenshot phpMyAdmin</summary>
  <img src="https://github.com/user-attachments/assets/a4c5cf2b-dff6-477a-9470-061b3a4a85e8"/>
  </details>

### **5. Tambahkan MySQL Connector ke Proyek**
- Unduh **MySQL Connector JAR** dari [situs resmi MySQL](https://downloads.mysql.com/archives/c-j/).
- Di NetBeans, klik kanan pada proyek → **Properties** → **Libraries**.
- Klik **Add JAR/Folder**, lalu pilih file **MySQL Connector JAR** yang telah diunduh.
- Klik **OK** untuk menyimpan perubahan.

  <details>
  <summary>Screenshot MySQL Connector</summary>
  <img src="https://github.com/user-attachments/assets/f9a9b704-aec2-4e89-b33d-29a0b8775b9c"/>
  </details>

### **6. Jalankan Aplikasi**
Setelah semua langkah di atas selesai, proyek siap dijalankan melalui NetBeans. Cukup klik **Run Project** dan aplikasi akan berjalan!

---

## 📚 Teknologi yang Digunakan
- **Java** – Bahasa pemrograman utama untuk pengembangan aplikasi.
- **MySQL** – Database untuk menyimpan data produk.
- **NetBeans** – IDE yang digunakan untuk pengembangan aplikasi.
- **Java Swing** – Framework GUI untuk antarmuka pengguna.
- **XAMPP** – Server lokal untuk menjalankan MySQL dan Apache.

## 🤝 Kontribusi
Kontribusi sangat diterima! Jika ingin meningkatkan proyek ini, silakan fork repositori, buat perubahan, dan kirim pull request.

---

Terima kasih telah menggunakan aplikasi ini! Jika ada pertanyaan atau kendala, jangan ragu untuk menghubungi saya.

