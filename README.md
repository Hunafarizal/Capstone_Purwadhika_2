# Capstone Project PART 2 (DATA ANALYSIS) - Tangan Kedua Tim Marketing Transjakarta



## Context
Capstone ini ditujukan untuk membantu Tim Marketing Transjakarta menentukan strategi promosi dan pemasaran mereka yang paling efisien berdasarkan data yang ada

## Problem Statement

1. Menentukan Bank mana yang akan kita coba untuk menjalin kerjasama berdasarkan hasil analisis dari informasi kartu pembayaran tersebut
2. Definisikan target promosi yang akan dilakukan dari Bank tersebut dengan Menganalisa usia dan gender para pengguna Bank tersebut agar dapat kita tentukan strategi seperti apa untuk marketing nya
3. Menganalisa pola perjalanan customer. yaitu Jam dan Hari apa rata-rata aktif nya dan juga halte mana yang paling sering dikunjungi dengan tujuan agar kita dapat lebih menganalisa lebih lanjut strategi waktu dan lokasi promosi

## Data
Menggunakan dataset `Transjakarta.csv` bulan April 2023. [Download di sini](https://drive.google.com/drive/folders/1S04hk5uHfHYe6J1S6fVqDunuja1Lk1Lo)

**Deskripsi Kolom**:

| Nama Kolom        | Deskripsi                                                                                         |
|-------------------|--------------------------------------------------------------------------------------------------|
| transID           | ID transaksi yang unik untuk setiap transaksi.                                                    |
| payCardID         | Identifikasi utama dari pelanggan. Kartu yang digunakan pelanggan sebagai tiket untuk masuk dan keluar. |
| payCardBank       | Nama bank penerbit kartu pembayaran milik pelanggan.                                             |
| payCardName       | Nama pelanggan yang ada di kartu.                                                                 |
| payCardSex        | Jenis kelamin pelanggan yang ada di kartu.                                                        |
| payCardBirthDate  | Tahun kelahiran pelanggan.                                                                        |
| corridorID        | ID Koridor / ID Rute sebagai kunci untuk pengelompokan rute.                                     |
| corridorName      | Nama Koridor / Nama Rute berisi Mulai dan Selesai untuk setiap rute.                              |
| direction         | Arah rute. 0 untuk Pergi, 1 untuk Pulang.                                                         |
| tapInStops        | ID halte tempat pelanggan melakukan Tap Masuk.                                                     |
| tapInStopsName    | Nama halte tempat pelanggan melakukan Tap Masuk.                                                   |
| tapInStopsLat     | Garis lintang dari halte tempat pelanggan melakukan Tap Masuk.                                    |
| tapInStopsLon     | Garis bujur dari halte tempat pelanggan melakukan Tap Masuk.                                       |
| stopStartSeq      | Posisi halte awal dalam rute perjalanan pelanggan pada saat melakukan Tap Masuk.                   |
| tapInTime         | Waktu pelanggan melakukan Tap Masuk yang mencakup tanggal dan jam.                                 |
| tapOutStops       | ID halte tempat pelanggan melakukan Tap Keluar.                                                    |
| tapOutStopsName   | Nama halte tempat pelanggan melakukan Tap Keluar.                                                  |
| tapOutStopsLat    | Garis lintang dari halte tempat pelanggan melakukan Tap Keluar.                                     |
| tapOutStopsLon    | Garis bujur dari halte tempat pelanggan melakukan Tap Keluar.                                       |
| stopEndSeq        | Posisi halte akhir dalam rute perjalanan pelanggan pada saat melakukan Tap Keluar.                 |
| tapOutTime        | Waktu pelanggan melakukan Tap Keluar.                                                              |

(BELUM TERMASUK KOLOM TAMBAHAN YANG AKAN DI INPUT PADA TAHAP DATA ANALYSIS)


## Analysis dan Kesimpulan

Refer ke file Capstone2.ipynb


[**Dashboard**](https://public.tableau.com/app/profile/)
