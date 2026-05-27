# Analisis Spasial Potensi Rainwater Harvesting - Aceh Barat

Proyek ini adalah analisis spasial untuk memetakan potensi **Rainwater Harvesting (Pemanenan Air Hujan)** pada kawasan permukiman di Kabupaten Aceh Barat. Analisis ini menggunakan data curah hujan dari NASA POWER dan data spasial permukiman untuk mendapatkan estimasi volume air yang bisa dipanen setiap tahunnya.

## 1. Tujuan Analisis
* Menghitung potensi volume air hujan berdasarkan luas atap bangunan dan rata-rata curah hujan tahunan.
* Menyediakan visualisasi peta yang memudahkan identifikasi kawasan dengan potensi RWH tertinggi.
* Menyajikan hasil dalam format statis (.png) untuk laporan dan interaktif (.html) untuk eksplorasi data.

2. Hasil Analisis
Peta Potensi RWH: Visualisasi sebaran potensi pemanenan air hujan per satuan luas atap di seluruh kawasan permukiman Aceh Barat.
Data Pendukung: Menggunakan koefisien runoff sebesar 0.80 dan rata-rata curah hujan tahunan dari data historis.

3. Cara Menjalankan
Buka file analisis_spasial_tmap.R di RStudio Anda.
Pastikan file SHP dan file Excel data hujan sudah ada di dalam folder yang sesuai.
Klik Source untuk menjalankan skrip.
Hasil peta akan otomatis muncul di folder output/.

4. Eksplorasi Peta Interaktif
Anda bisa melihat dan berinteraksi langsung dengan peta melalui link berikut:
Lihat Peta Interaktif Aceh Barat

5. Langkah Mengaktifkan Peta Interaktif (GitHub Pages)
Agar peta interaktif kamu bisa diakses melalui browser, ikuti langkah berikut:
Masuk ke Settings: Di halaman repositori GitHub kamu, klik tab Settings di menu atas.
Buka Menu Pages: Pada menu sebelah kiri, klik opsi Pages.
Konfigurasi Deploy:
Pada bagian Build and deployment, pilih Deploy from a branch.
Di bagian Branch, klik dropdown dan pilih main.
Klik tombol Save.
Tunggu Proses: GitHub butuh waktu 1-2 menit untuk memproses file kamu. Refresh halaman sampai muncul tulisan hijau: "Your site is live at...".
Verifikasi: Klik link tersebut, lalu pastikan di akhir URL kamu menambahkan nama file:
/peta_potensi_rwh_aceh_barat_interaktif.html

Tips: Jika saat diakses muncul pesan 404 Not Found, pastikan nama file di link sama persis dengan nama file yang ada di folder repositori kamu (huruf besar/kecil berpengaruh).

Dibuat untuk kebutuhan tugas analisis spasial menggunakan R.


6. Struktur Folder
```text
├── analisis_spasial_tmap.R  # Skrip utama proses data & visualisasi
├── README.md                # Dokumentasi proyek ini
└── output/                  # Folder hasil olahan
    ├── peta_potensi_rwh_aceh_barat.png          # Peta statis (High Quality)
    └── peta_potensi_rwh_aceh_barat_interaktif.html # Peta interaktif (Zoom & Pan)

3. Hasil Analisis
Peta Potensi RWH: Visualisasi sebaran potensi pemanenan air hujan per satuan luas atap di seluruh kawasan permukiman Aceh Barat.
Data Pendukung: Menggunakan koefisien runoff sebesar 0.80 dan rata-rata curah hujan tahunan dari data historis.

4. Cara Menjalankan
Buka file analisis_spasial_tmap.R di RStudio Anda.
Pastikan file SHP dan file Excel data hujan sudah ada di dalam folder yang sesuai.
Klik Source untuk menjalankan skrip.
Hasil peta akan otomatis muncul di folder output/.

5. Eksplorasi Peta Interaktif
Anda bisa melihat dan berinteraksi langsung dengan peta melalui link berikut:
Lihat Peta Interaktif Aceh Barat

6. Langkah Mengaktifkan Peta Interaktif (GitHub Pages)
Agar peta interaktif kamu bisa diakses melalui browser, ikuti langkah berikut:
Masuk ke Settings: Di halaman repositori GitHub kamu, klik tab Settings di menu atas.
Buka Menu Pages: Pada menu sebelah kiri, klik opsi Pages.
Konfigurasi Deploy:
Pada bagian Build and deployment, pilih Deploy from a branch.
Di bagian Branch, klik dropdown dan pilih main.
Klik tombol Save.
Tunggu Proses: GitHub butuh waktu 1-2 menit untuk memproses file kamu. Refresh halaman sampai muncul tulisan hijau: "Your site is live at...".
Verifikasi: Klik link tersebut, lalu pastikan di akhir URL kamu menambahkan nama file:
/peta_potensi_rwh_aceh_barat_interaktif.html

Tips: Jika saat diakses muncul pesan 404 Not Found, pastikan nama file di link sama persis dengan nama file yang ada di folder repositori kamu (huruf besar/kecil berpengaruh).

Dibuat untuk kebutuhan tugas analisis spasial menggunakan R.
