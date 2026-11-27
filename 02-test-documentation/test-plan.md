# Test Plan

## 1. Introduction

Dokumen ini berisi perencanaan pengujian fungsional pada Gapura App. Test Plan digunakan sebagai pedoman pelaksanaan pengujian, mulai dari penentuan tujuan, ruang lingkup, metode, teknik, lingkungan, hingga kriteria penyelesaian pengujian.

Pengujian dilakukan untuk mengevaluasi fungsi aplikasi menggunakan pendekatan Black Box Testing, baik secara manual maupun otomatis menggunakan Selenium.

## 2. Testing Objectives

Tujuan pengujian ini adalah:

1. Memastikan fungsi aplikasi berjalan sesuai dengan hasil yang diharapkan.
2. Mengidentifikasi kesalahan atau defect pada fitur yang diuji.
3. Membandingkan hasil aktual dengan hasil yang diharapkan.
4. Membandingkan pelaksanaan pengujian manual dan otomatis menggunakan Selenium.
5. Mendokumentasikan hasil pengujian sebagai dasar evaluasi kualitas fungsional aplikasi.

## 3. Testing Object

Nama Aplikasi: Gapura App

Website: https://gapuraapp.com/umkm

Jenis Pengujian: Pengujian Fungsional

Objek pengujian mencakup fitur yang dapat diakses melalui website, baik oleh pengunjung maupun pemilik UMKM.

## 4. Testing Methodology

Metode pengujian yang digunakan adalah **Black Box Testing**, yaitu pengujian yang berfokus pada fungsi aplikasi berdasarkan input dan output tanpa memeriksa struktur kode program internal.

## 5. Testing Techniques

Teknik pengujian yang digunakan:

- **Equivalence Partitioning (EP):** Membagi data input ke dalam kelompok-kelompok yang memiliki karakteristik serupa untuk mengurangi jumlah kasus pengujian.
- **Boundary Value Analysis (BVA):** Menguji nilai pada batas minimum, maksimum, dan nilai di sekitar batas tersebut.

## 6. Testing Environment

| Component | Description |
|---|---|
| Operating System | Windows |
| Browser | Google Chrome |
| Device | Laptop/Desktop |
| Internet Connection | Available connection |
| Testing Website | https://gapuraapp.com/umkm |
| Automation Tool | Selenium WebDriver |
| Programming Language | Java |

## 7. Test Items

Fitur yang menjadi kandidat pengujian berdasarkan hasil eksplorasi aplikasi:

### A. Public Features
- Navigasi website.
- Menampilkan daftar UMKM.
- Pencarian UMKM.
- Filter kategori UMKM.
- Menampilkan detail toko dan produk.
- Tombol pemesanan yang mengarahkan pengguna ke WhatsApp.

### B. Owner Features
- Login pemilik toko.
- Pembuatan toko.
- Menampilkan dashboard.
- Mengubah dan melengkapi profil toko.
- Validasi input pada formulir.
- Penambahan produk.
- Pengelolaan produk, apabila fitur tersedia.

Daftar fitur dan skenario pengujian akan ditetapkan lebih lanjut berdasarkan hasil eksplorasi dan verifikasi akses.

## 8. Test Schedule

Jadwal pelaksanaan pengujian mengacu pada dokumen:

`01-project-planning/testing-schedule.md`

Pelaksanaan disesuaikan dengan pembagian tugas anggota kelompok dan durasi proyek yang tersedia.

## 9. Entry Criteria

Pengujian dapat dimulai apabila:

- Objek pengujian telah ditentukan dan divalidasi.
- Fitur yang menjadi target pengujian dapat diakses.
- Test scenario dan test case telah disiapkan.
- Lingkungan pengujian telah tersedia.
- Data pengujian yang diperlukan telah disiapkan.

## 10. Exit Criteria

Pengujian dinyatakan selesai apabila:

- Seluruh test case yang direncanakan telah dieksekusi atau memiliki keterangan status.
- Hasil pengujian manual dan otomatis telah didokumentasikan.
- Defect yang ditemukan telah dicatat dan dianalisis.
- Perbandingan hasil pengujian telah disusun.
- Laporan akhir pengujian telah dipersiapkan.

## 11. Risks

Risiko yang dapat memengaruhi pelaksanaan pengujian:

- Website tidak dapat diakses atau mengalami gangguan.
- Beberapa fitur memerlukan akun untuk dapat diuji.
- Akses pengujian terbatas.
- Terjadi perubahan tampilan atau fungsi website selama periode pengujian.
- Koneksi internet tidak stabil.
- Terdapat kendala dalam konfigurasi atau eksekusi Selenium.

## 12. Test Deliverables

Dokumen dan hasil yang dihasilkan selama proyek:

1. Test Plan.
2. Test Scenario.
3. Test Case.
4. Test Result.
5. Test Evidence.
6. Bug Report dan Defect Log.
7. Analisis perbandingan pengujian manual dan Selenium.
8. Final Testing Report.
