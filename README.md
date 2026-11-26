# DAM UTS - Data Acquisition & Management

## Identitas Mahasiswa
- **Nama:** Herkulano Yorgi Novriandri Simuk
- **NIM:** 2501010203
- **Kelas:** F
- **Program Studi:** Informatika

## Deskripsi
Repositori ini merupakan proyek UTS mata kuliah Data Acquisition & Management. Proyek ini berisi proses pengumpulan, penyimpanan, pemeriksaan, dan pengolahan data yang diperoleh dari beberapa sumber menggunakan metode akuisisi data.

## Tujuan Proyek
- Melakukan pengumpulan data dari berbagai sumber.
- Mempraktikkan metode akuisisi data melalui API, download, dan scraping.
- Mengelola data mentah dan data hasil pengolahan.
- Melakukan dokumentasi proses akuisisi data.

## Struktur Folder
```text
dam_uts-fix/
├── data/
│   ├── processed/
│   │   ├── cuaca_museum_process.csv
│   │   ├── pariwisata_bali_scraping.csv
│   │   └── statistik_pariwisata_bali_2025_clean.csv
│   └── raw/
│       ├── api/
│       │   └── cuaca_museum_raw.json
│       ├── download/
│       │   └── file_data_excel
│       └── scraping/
│           └── file_hasil_scraping
├── readmi/
└── README.md
```

## Metode Akuisisi Data

### 1. API
Pengumpulan data menggunakan Application Programming Interface (API) untuk memperoleh data dalam format JSON.

### 2. Download
Pengumpulan data dilakukan dengan mengunduh file dari sumber data yang tersedia dalam format Excel atau file lainnya.

### 3. Web Scraping
Pengumpulan data dilakukan dengan mengambil informasi dari halaman website menggunakan metode scraping.

## Pengolahan Data
Data yang telah dikumpulkan disimpan pada folder `data/raw`. Data yang telah melalui proses pemeriksaan dan pengolahan disimpan pada folder `data/processed`.

## Teknologi yang Digunakan
- Python
- Google Colab
- Pandas
- Requests
- BeautifulSoup
- API
- Excel
- CSV
- JSON

## Hasil Proyek
Repositori ini menjadi dokumentasi praktik akuisisi data melalui metode API, download, dan web scraping, serta pengelolaan data mentah dan data hasil pengolahan.

## Etika Data
Pengumpulan data dilakukan dengan menggunakan sumber yang dapat diakses secara publik. Sumber data dicatat untuk menjaga transparansi dan keterlacakan proses akuisisi. Penggunaan data tetap memperhatikan ketentuan dari sumber data.

## Penutup
Proyek ini dibuat untuk memenuhi tugas UTS Data Acquisition & Management dan sebagai praktik dalam memahami proses pengumpulan serta pengelolaan data secara terstruktur menggunakan Python.
