# DAMAPOLINARISA
# Proyek Akuisisi dan Manajemen Data

## Identitas Mahasiswa

* **Nama:** Jack Apolinarisa
* **NIM:** 2501010333
* **Program Studi:** Informatika
* **Mata Kuliah:** BIFP-243 – Akuisisi dan Manajemen Data
* **Institusi:** INSTIKI (Institut Bisnis dan Teknologi Indonesia)

## 1. Deskripsi Proyek

Proyek ini merupakan tugas praktikum mata kuliah Akuisisi dan Manajemen Data. Praktikum ini menggunakan Python untuk mempersiapkan lingkungan kerja, membuat struktur folder proyek, menyusun dokumentasi, menggunakan Git untuk mengelola perubahan, dan memetakan tahapan Data Science Lifecycle.

Tujuan praktikum ini adalah memahami cara mengelola proyek data secara terstruktur agar data dan kode lebih mudah disimpan, digunakan kembali, serta diperiksa.

## 2. Tools dan Library

Tools dan library yang digunakan dalam praktikum ini adalah:

* **Python:** bahasa pemrograman yang digunakan dalam praktikum.
* **Pandas:** membuat dan mengelola tabel pemetaan Data Science Lifecycle.
* **NumPy:** mendukung operasi numerik.
* **Requests:** mengambil data dari layanan web.
* **BeautifulSoup4:** membantu membaca dan memproses dokumen HTML.
* **Google Colab:** menjalankan kode Python secara online.
* **Git dan GitHub:** mengelola versi kode dan menyimpan repository proyek.

## 3. Struktur Folder Proyek

Struktur folder dibuat menggunakan Python dengan library `pathlib`.

```text
proyek_akuisisi_data/
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
├── notebooks/
├── src/
├── docs/
│   └── lifecycle.csv
├── reports/
└── README.md
```

Keterangan folder:

* `data/raw/`: menyimpan data mentah hasil akuisisi dan tidak ditimpa.
* `data/interim/`: menyimpan data sementara hasil pengolahan awal.
* `data/processed/`: menyimpan data yang sudah dibersihkan dan siap dianalisis.
* `notebooks/`: menyimpan notebook praktikum.
* `src/`: menyimpan kode Python yang dapat digunakan kembali.
* `docs/`: menyimpan dokumentasi dan file `lifecycle.csv`.
* `reports/`: menyimpan laporan hasil praktikum.
* `README.md`: menjelaskan tujuan, struktur, dan cara menjalankan proyek.

## 4. Verifikasi Environment

Pada tahap awal, dilakukan pemeriksaan versi Python, platform yang digunakan, dan library inti seperti Pandas, NumPy, Requests, serta BeautifulSoup4.

Pemeriksaan ini bertujuan memastikan lingkungan kerja sudah siap digunakan. Jika ada library yang belum terpasang, library tersebut dapat dipasang menggunakan perintah `pip install nama-library`.

## 5. Data Science Lifecycle

Data Science Lifecycle terdiri dari enam tahap:

1. **Acquisition:** mengumpulkan data dari berbagai sumber.
2. **Storage:** menyimpan dan mengatur data agar mudah diakses.
3. **Cleaning:** memeriksa data kosong, duplikat, dan kesalahan.
4. **Transformation:** mengubah format atau struktur data sesuai kebutuhan.
5. **Analysis:** menganalisis data untuk mendapatkan informasi.
6. **Delivery:** menyampaikan hasil analisis dalam bentuk laporan atau visualisasi.

Pada praktikum ini, Pandas digunakan untuk membuat tabel yang berisi tahap, aktivitas utama, contoh tools, dan risiko jika tahapan diabaikan. Hasil tabel disimpan dalam format CSV pada folder `docs/` dengan nama `lifecycle.csv`.

## 6. Reproducibility dalam Akuisisi Data

Reproducibility atau keterulangan adalah kemampuan untuk menjalankan kembali suatu proses dan memeriksa bagaimana hasil diperoleh. Hal ini penting dalam akuisisi data karena sumber data dapat berubah, proses pengambilan dapat mengalami kesalahan, dan hasil analisis harus dapat dipertanggungjawabkan. Contohnya adalah pengumpulan data cuaca dari API BMKG. Data cuaca dapat berbeda ketika diambil pada waktu yang berbeda karena kondisi cuaca terus berubah. Agar prosesnya dapat diperiksa kembali, pengambil data perlu mencatat sumber data, waktu pengambilan, parameter permintaan, versi Python, versi library, dan kode yang digunakan. Data mentah sebaiknya disimpan di folder `data/raw/` dan tidak ditimpa, sedangkan data hasil pengolahan ditempatkan di folder terpisah. Git membantu mencatat perubahan kode sehingga proses pengambilan data dapat ditelusuri. Dokumentasi juga memudahkan orang lain memahami langkah yang dilakukan. Dengan cara ini, kesalahan lebih mudah ditemukan dan hasil pengolahan lebih transparan. Walaupun demikian, data dari sumber yang terus berubah belum tentu menghasilkan keluaran identik setiap kali proses dijalankan. Karena itu, menyimpan salinan data mentah beserta metadata pengambilannya sangat penting untuk membantu pengujian dan pemeriksaan hasil.

## 7. Git dan GitHub

Git digunakan untuk mencatat perubahan pada file proyek. Repository GitHub digunakan untuk menyimpan kode dan dokumentasi secara online agar mudah diakses kembali.

Langkah dasar penggunaan Git:

1. Membuat repository lokal dengan `git init`.
2. Menambahkan file menggunakan `git add .`.
3. Membuat commit menggunakan `git commit`.
4. Menghubungkan repository lokal dengan GitHub menggunakan `git remote add origin`.
5. Mengirim file ke GitHub menggunakan `git push`.

URL repository GitHub: **isi dengan tautan repository milik sendiri.**

## 8. Cara Menjalankan Proyek

1. Buka notebook `DAM.APOLINARISA.ipynb` menggunakan Google Colab.
2. Pastikan Python dan library yang diperlukan tersedia.
3. Jalankan sel kode secara berurutan.
4. Periksa hasil verifikasi environment dan struktur folder.
5. Jalankan kode pemetaan Data Science Lifecycle.
6. Pastikan file `docs/lifecycle.csv` berhasil dibuat.

## 9. Kesimpulan

Praktikum ini memberikan pemahaman dasar mengenai persiapan lingkungan Python, pengorganisasian folder proyek, dokumentasi, pengelolaan versi menggunakan Git, dan pemetaan Data Science Lifecycle. Struktur proyek yang teratur dan dokumentasi yang jelas membantu proses pengolahan data menjadi lebih mudah dipahami, diperiksa, dan digunakan kembali.


