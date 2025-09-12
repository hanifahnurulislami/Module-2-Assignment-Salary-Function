# Milestone Assignment 1: Policy Management System for an Insurance Company

## Deskripsi Proyek
Proyek ini adalah sebuah sistem sederhana berbasis **Object-Oriented Programming (OOP)** yang dibangun menggunakan Python. Tujuannya adalah untuk mensimulasikan proses-proses dasar dalam sebuah perusahaan asuransi, seperti manajemen pemegang polis, produk asuransi, dan transaksi pembayaran.

Sistem ini terdiri dari beberapa kelas yang saling berinteraksi, mencakup fungsionalitas seperti:
* Mendaftarkan dan mengelola pemegang polis.
* Mendefinisikan dan memperbarui produk-produk asuransi.
* Memproses pembayaran, mengirim pengingat, dan menerapkan penalti.
* Mendemonstrasikan fungsionalitas sistem dengan contoh data.

---

## Struktur Proyek
Proyek ini dibagi menjadi beberapa file Python:

* `policyholder.py`: Berisi kelas **`Policyholder`** untuk mengelola data dan status pemegang polis (mendaftar, menangguhkan, mengaktifkan kembali).
* `product.py`: Berisi kelas **`Product`** untuk mendefinisikan produk asuransi dan metode untuk memperbarui atau menangguhkan produk.
* `payment.py`: Berisi kelas **`Payment`** yang bertanggung jawab untuk mengelola transaksi pembayaran, termasuk memproses, mengirim pengingat, dan menerapkan penalti.
* `policy_management.ipynb`: File Jupyter Notebook yang berfungsi sebagai *driver* utama. File ini mengimpor kelas-kelas di atas, membuat objek, dan mendemonstrasikan alur kerja sistem.

---

## Cara Menjalankan Proyek
Ikuti langkah-langkah berikut untuk menjalankan proyek ini di lingkungan lokal Anda.

### 1. Persyaratan
Pastikan Anda sudah menginstal Python. Proyek ini juga memerlukan library eksternal `prettytable` untuk menampilkan data dalam format tabel.

Anda bisa menginstalnya menggunakan pip:
```bash
pip install prettytable
````

### 2\. Menjalankan Kode

1.  Buka file `policy_management.ipynb` menggunakan Jupyter Notebook atau JupyterLab.
2.  Jalankan setiap sel kode secara berurutan, dari atas ke bawah.

Output dari kode akan menampilkan tabel yang berisi detail pemegang polis, produk yang mereka miliki, dan status pembayaran mereka.

-----

## Fitur-Fitur Utama

  * **Kelas Terpisah**: Setiap entitas utama (Policyholder, Product, Payment) diwakili oleh kelasnya sendiri, yang mempromosikan modularitas dan keterbacaan kode.
  * **Enkapsulasi**: Atribut objek (misalnya, `name`, `amount`, `status`) dikelola melalui metode yang ada di dalam kelasnya, seperti `process_payment()` atau `suspend()`, yang menunjukkan prinsip enkapsulasi.
  * **Demonstrasi Fungsional**: Kode di `policy_management.ipynb` memberikan contoh nyata tentang bagaimana setiap metode dan objek berinteraksi untuk mencapai hasil yang diinginkan.

<!-- end list -->
