# 📦 Sistem Order Pembelian (OP Dashboard)

Dashboard **Order Pembelian (OP)** berbasis web yang menampilkan data langsung dari **Google Spreadsheet** menggunakan **PapaParse** dan menampilkannya dalam bentuk tabel interaktif dengan **DataTables**.  
Dilengkapi modal detail yang menampilkan informasi lengkap per order, termasuk link Google Form dinamis untuk melengkapi proses peminjaman/pemakaian barang.

---

## ✨ Fitur Utama
- 🔗 **Integrasi Google Spreadsheet** – Data diambil otomatis dari link CSV Google Sheets.
- 📊 **Tabel Interaktif** – Menggunakan [DataTables](https://datatables.net/) untuk sort, search, dan pagination.
- 📄 **Modal Detail** – Lihat detail order pembelian dalam modal yang rapi.
- 📝 **Link Form Dinamis** – Link Google Form dibangun otomatis berdasarkan data di spreadsheet.
- 🎨 **Tampilan Modern** – Menggunakan Bootstrap 5 dengan tema clean dan responsif.

---

## 🛠️ Teknologi yang Digunakan
- [Bootstrap 5](https://getbootstrap.com/) – styling & layout.
- [jQuery 3.7.0](https://jquery.com/) – DOM manipulation.
- [DataTables](https://datatables.net/) – tabel interaktif.
- [PapaParse](https://www.papaparse.com/) – parser CSV untuk membaca data dari Google Sheets.

---

## 📂 Struktur Proyek
```bash
.
├── index.html       # File utama (dashboard)
└── README.md        # Dokumentasi proyek
