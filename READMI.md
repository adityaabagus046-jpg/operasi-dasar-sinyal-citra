# Eksperimen Operasi Dasar pada Sinyal dan Citra

## Deskripsi Project
[cite_start]Project ini merupakan pemenuhan Tugas Individu untuk mata kuliah Pengolahan Sinyal Digital[cite: 1, 2]. [cite_start]Eksperimen ini bertujuan untuk menerapkan dan menganalisis operasi dasar seperti penjumlahan, penggeseran (shifting), dan amplifikasi pada domain sinyal 1D (diskrit) dan citra 2D[cite: 12, 15]. [cite_start]Fokus utama dari eksperimen ini adalah membuktikan bagaimana operasi dasar matematika tersebut melandasi konsep yang lebih besar dalam DSP, seperti prinsip superposisi dan uji sistem linier[cite: 15, 157].

## Identitas Mahasiswa
* Nama: [aditya bagus nurcahyo]
* NIM: [452024611034]
* [cite_start]Mata Kuliah: Pengolahan Sinyal Digital [cite: 2]

## Library yang Digunakan
[cite_start]Project ini diimplementasikan menggunakan bahasa pemrograman Python dengan pustaka (libraries) berikut[cite: 27]:
* [cite_start]NumPy: Untuk manipulasi array sinyal dan komputasi matriks piksel citra[cite: 28].
* [cite_start]Matplotlib: Untuk visualisasi plot gelombang sinyal, citra hasil operasi, dan grafik histogram[cite: 29].
* [cite_start]OpenCV (cv2): Untuk membaca, memproses, melakukan *resizing, dan mentranslasikan citra 2D[cite: 30].

## Struktur Folder Project
[cite_start]Repositori ini disusun berdasarkan standarisasi berikut[cite: 263]:
```text
operasi-dasar-sinyal-citra/
├── notebook/
│   └── operasi_sinyal_citra.ipynb   # File Jupyter Notebook eksperimen
├── images/
│   └── citra_yang_digunakan.jpg     # File gambar/citra untuk eksperimen
├── report/
│   └── laporan.pdf                  # Laporan analisis akhir (maks. 8 halaman)
├── README.md                        # Dokumentasi utama project
└── requirements.txt                 # Daftar dependency library