# 📦 SISAPI — Sistem Informasi Pergudangan
**CV Yudistira Feedmill**

SISAPI adalah aplikasi web manajemen gudang modern berbasis *Single-Page Application (SPA)* single-file HTML yang dirancang untuk mengelola keluar/masuk barang (Surat Jalan), pemantauan stok real-time, pencatatan absensi shift admin, hingga pelaporan dan pencetakan dokumen yang terintegrasi dengan Google Apps Script dan Google Sheets.

---

## 🚀 Fitur Utama SISAPI

1. **Autentikasi & Multi-Akun Fleksibel**
   - Mendukung akses akun untuk **Full Admin** (Sufyan, Hasfhi, dll.) serta akun **Viewer / Lihat Saja** untuk pengawasan.
2. **Absensi Shift Admin Gudang**
   - Pencatatan kehadiran shift kerja otomatis dengan waktu live WIB, lengkap dengan filter laporan harian, mingguan, bulanan, serta fitur unduh rekap absensi CSV.
3. **Pencatatan Keluar & Masuk (Mutasi Inbound/Outbound)**
   - Integrasi otomatis mutasi stok gudang, pilihan armada, plat nomor, sopir, hingga pengecekan ketersediaan stok secara langsung.
4. **Cetak Surat Jalan Otomatis (Barcode & QR Code)**
   - Fitur cetak dokumen Surat Jalan / Bukti Masuk dengan lebar proporsional A4, dilengkapi **Barcode 1D (Code128)** untuk nomor SJ dan **QR Code Dinamis** yang berisi detail data transaksi lengkap.
5. **Stok Gudang Real-Time & Kontrol Manual**
   - Pemantauan posisi stok bahan baku dan pakan jadi secara real-time, dilengkapi fitur *Stock Opname* penyesuaian fisik dan penambahan master barang baru.
6. **Laporan & Riwayat Terintegrasi**
   - Filter laporan lengkap berdasarkan Harian (dengan opsi semua tanggal), Mingguan (7 hari terakhir), dan Bulanan, serta tombol ekspor ke Excel/CSV.
7. **Floating Calculator Gudang (Kalkulator Melayang)**
   - Kalkulator popup melayang yang dilengkapi fitur konversi cepat satuan Sak ke Kilogram ($1 \text{ Sak} = 50 \text{ Kg}$).
8. **Dark Mode & PWA Ready**
   - Mengusung **Mode Gelap (Dark Mode)** sebagai tampilan default utama yang elegan dan ramah mata, serta mendukung instalasi aplikasi (*Progressive Web App*).

---

## 🛠️ Teknologi yang Digunakan

- **Frontend:** HTML5, Tailwind CSS (CDN), JavaScript (ES6+).
- **Icons & Fonts:** FontAwesome 6.5.1, Google Fonts (Inter & JetBrains Mono).
- **Libraries:** JsBarcode (untuk Barcode 1D), QR Server API (untuk QR Code).
- **Backend & Database:** Google Apps Script (`SCRIPT_URL`) & Google Sheets.

---

## 📋 Struktur Berkas Repository

- `index.html` — Berkas utama aplikasi (SPA mencakup seluruh tampilan antarmuka dan logika sistem).
- `manifest.json` — Konfigurasi PWA / aplikasi web siap install.
- `icon.png` — Logo ikon aplikasi dan favicon sistem.

---
*© 2026 CV Yudistira Feedmill. Developed for PT Media Tulisan Manusia.*
