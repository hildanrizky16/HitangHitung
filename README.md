# HitangHitung - Kalkulator HPP UMKM F&B

Aplikasi web berbasis kalkulator HPP (Harga Pokok Penjualan) interaktif yang dirancang khusus untuk membantu UMKM kuliner (F&B) di Indonesia. Aplikasi ini memudahkan pelaku usaha dalam menghitung biaya bahan baku, kemasan, operasional, hingga menentukan harga jual yang ideal (baik offline maupun online/Ojol).

## Fitur Utama
- **Penghitungan Bahan Baku & Kemasan:** Mengonversi harga grosir menjadi biaya per porsi secara otomatis.
- **Biaya Operasional (Overhead):** Membagi beban listrik, gaji, dan sewa bulanan ke dalam satuan per porsi.
- **Simulasi Harga Jual & Margin:** Menghitung harga jual offline (Dapur) dan online (Gofood/Grabfood/Shopeefood) berdasarkan target margin.
- **Penyimpanan Lokal (Local Storage):** Simpan dan muat ulang resep HPP tanpa memerlukan database atau server.
- **Preset Resep:** Tersedia contoh HPP siap pakai (Kopi Susu, Ayam Geprek, Brownies).
- **Mode Gelap (Dark Mode):** Tampilan UI/UX yang nyaman dan menyesuaikan preferensi sistem.
- **Cetak Laporan (Print to PDF):** Layout khusus untuk mencetak ringkasan HPP ke format PDF.

## Teknologi yang Digunakan
- **HTML5 & Vanilla JavaScript:** Logika kalkulasi murni tanpa framework tambahan.
- **Tailwind CSS (via CDN):** Styling tampilan yang modern, responsif, dan rapi.
- **Chart.js:** Visualisasi grafik porsi komposisi biaya.
- **FontAwesome:** Penggunaan ikon antarmuka.

## Cara Menjalankan Secara Lokal
Proyek ini sepenuhnya bersifat statis (Client-side). Tidak ada proses instalasi atau *build* yang rumit.
1. *Clone* atau unduh *repository* ini.
2. Buka folder proyek.
3. Klik ganda pada file `index.html` untuk membukanya langsung di *browser* Anda (Chrome, Safari, Firefox, dsb).

## Cara Deploy (Hosting Gratis)
Karena website ini statis, Anda bisa mengunggahnya (deploy) dengan sangat mudah melalui beberapa platform berikut secara gratis:
- **Netlify Drop:** Cukup *drag and drop* folder proyek ke [app.netlify.com/drop](https://app.netlify.com/drop).
- **GitHub Pages:** Aktifkan GitHub Pages melalui tab *Settings* > *Pages* di repository GitHub Anda, lalu pilih branch `main` pada root folder `/`.
- **Vercel:** Import repository ini ke [Vercel](https://vercel.com/) dan deploy dalam hitungan detik.

## Lisensi
[MIT License](https://opensource.org/licenses/MIT) - Bebas digunakan dan dimodifikasi untuk kebutuhan personal maupun komersial.
