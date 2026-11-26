# DAM UTS - Data Acquisition & Management

## Identitas Mahasiswa
| Informasi | Keterangan |
|---|---|
| Nama | Herkulano Yorgi Novriandri Simuk |
| NIM | 2501010203 |
| Kelas | F |
| Program Studi | Informatika |

## Deskripsi Proyek
Proyek ini merupakan tugas UTS mata kuliah Data Acquisition & Management yang berfokus pada pengumpulan, pengelolaan, pemeriksaan, dan pengolahan data dari berbagai sumber menggunakan metode API, download, dan web scraping.

## Goal (Tujuan)
1. Mempraktikkan proses akuisisi data dari berbagai sumber.
2. Memahami metode pengumpulan data menggunakan API, download, dan web scraping.
3. Mengelola data mentah (raw data) dan data hasil pengolahan (processed data).
4. Melakukan pemeriksaan dan pembersihan dataset.
5. Mendokumentasikan sumber serta proses pengumpulan data.

## Sumber Data

### 1. Data Cuaca dan Museum
- **Metode:** API
- **Format:** JSON
- **File:** `cuaca_museum_raw.json`
- **URL sumber:** Dokumentasi atau endpoint API yang digunakan dalam notebook.

### 2. Data Pariwisata Bali
- **Metode:** Web Scraping
- **Format:** CSV
- **File:** `pariwisata_bali_scraping.csv`
- **URL sumber:** Website yang digunakan pada proses scraping dan dicatat di notebook.

### 3. Statistik Pariwisata Bali Tahun 2025
- **Metode:** Download
- **Instansi:** Dinas Pariwisata Provinsi Bali
- **Format data:** Excel
- **URL sumber:** https://disparda.baliprov.go.id/
- **Halaman sumber:** [Dinas Pariwisata Provinsi Bali](https://disparda.baliprov.go.id/)

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

### API
Pengumpulan data dilakukan melalui API untuk memperoleh data dalam format JSON.

### Download
Data dikumpulkan dengan mengunduh file dari sumber yang tersedia dalam format Excel atau format lainnya.

### Web Scraping
Pengumpulan data dilakukan dengan mengambil informasi dari halaman website menggunakan Python.

## Pengolahan Data
Data mentah disimpan pada folder `data/raw`, sedangkan data yang telah melalui proses pemeriksaan dan pengolahan disimpan pada folder `data/processed`.

Tahapan pengolahan meliputi:
- Pemeriksaan struktur dataset.
- Pemeriksaan data kosong.
- Pemeriksaan data duplikat.
- Pembersihan data.
- Penyimpanan hasil pengolahan.

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
Proyek ini menghasilkan kumpulan data yang diperoleh melalui metode API, download, dan web scraping. Data dikelola dalam bentuk data mentah dan data hasil pengolahan yang disimpan secara terstruktur pada repositori GitHub.

## Etika Data
Pengumpulan data dilakukan dengan memperhatikan sumber data, keterlacakan sumber, ketentuan akses, dan penggunaan data untuk keperluan akademik.

## Penutup
Proyek ini disusun untuk memenuhi tugas UTS mata kuliah Data Acquisition & Management Program Studi Informatika. Proyek ini menjadi sarana pembelajaran dalam memahami proses akuisisi, pengelolaan, pemeriksaan, dan dokumentasi data.
