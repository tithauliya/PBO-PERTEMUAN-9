# Pembuatan Laporan Data Menggunakan JasperReport

Proyek ini merupakan implementasi pembuatan laporan data menggunakan **JasperReport** pada aplikasi **Java JDBC**.  
Aplikasi dikembangkan di **NetBeans IDE** dan terkoneksi ke **PostgreSQL** dengan desain laporan melalui **JasperSoft Studio**.

---

## 🧾 Catatan Penting
Laporan dibuat menggunakan **JasperSoft Studio**, bukan plugin bawaan NetBeans, berdasarkan referensi:
🎥 [https://youtu.be/ODNQN6vZp04?si=Ndvhqd150a1lAHvj](https://youtu.be/ODNQN6vZp04?si=Ndvhqd150a1lAHvj)

Alur laporan:
1. Desain laporan di JasperSoft Studio → simpan `.jrxml`  
2. Compile menjadi `.jasper`  
3. Impor ke NetBeans  
4. Panggil melalui kode Java menggunakan `JasperFillManager` & `JasperViewer`

---

## 🧩 Deskripsi Singkat
Aplikasi menampilkan data dari tabel **tokoroti** dan memiliki fitur:
- CRUD (Tambah, Ubah, Hapus data)
- Menampilkan data roti di JTable
- Cetak laporan menggunakan JasperReport

---

## 🛠️ Teknologi Digunakan
- Java (JDK 17)  
- NetBeans IDE  
- PostgreSQL  
- JasperSoft Studio  
- JasperReports Library  
- iText & Commons Library  

---

## ⚙️ Langkah Pembuatan
1. Buat database dan tabel `tokoroti` di PostgreSQL  
2. Desain laporan di **JasperSoft Studio** dan compile menjadi `.jasper`  
3. Tambahkan file `.jasper` ke folder project (`src/report/`)  
4. Tambahkan library JasperReports & PostgreSQL JDBC ke NetBeans  
5. Panggil laporan di tombol cetak menggunakan `JasperViewer`  
6. Jalankan aplikasi untuk menampilkan dan mencetak data  

---

## ▶️ Hasil Akhir
Aplikasi dapat menampilkan data roti dan mencetak laporan berbentuk JasperReport secara langsung dari Java GUI.

---

## ✍️ Disusun Oleh
**Titha Auliya Khotim**  
NIM: 09010624017  
Program Studi Sistem Informasi  
Fakultas Sains dan Teknologi  
Universitas Islam Negeri Sunan Ampel Surabaya  
Tahun 2025
