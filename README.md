# Analisis Spasial Potensi Rainwater Harvesting - Aceh Barat

Proyek ini adalah analisis spasial untuk memetakan potensi **Rainwater Harvesting (Pemanenan Air Hujan)** pada kawasan permukiman di Kabupaten Aceh Barat. Analisis ini menggunakan data curah hujan dari NASA POWER dan data spasial permukiman.

## 1. Tujuan Analisis
* Menghitung potensi volume air hujan berdasarkan luas atap bangunan dan rata-rata curah hujan tahunan.
* Menyediakan visualisasi peta yang memudahkan identifikasi kawasan dengan potensi RWH tertinggi.

## 2. Struktur Folder
```text
├── analisis_pemanenan_air_hujan.R  # Skrip utama analisis
├── README.md                       # Dokumentasi proyek
└── outputRWH/                      # Folder hasil komputasi
    ├── peta_potensi_air_hujan.png  # Peta hasil analisis
    └── sessionInfo.txt             # Catatan versi R dan paket

## 3. Visualisasi Hasil
[
  ![Peta Potensi Air Hujan](outputRWH/peta_potensi_air_hujan.png)
](outputRWH/peta_potensi_air_hujan.png)
