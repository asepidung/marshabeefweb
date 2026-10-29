# CMM Meat – Website Profil & Pemesanan Daging

Website profil dan katalog resmi untuk **CMM Meat (Local Meat Shop)**, diproduksi oleh **PT. Berkah Marsha Sejahtera** (Depok, Jawa Barat).

Dibuat sebagai bonus eksklusif yang melengkapi sistem aplikasi cetak label pabrik Marsha Beef.

---

## 🌟 Fitur Utama

1. **Desain Modern & Responsif**: Tampilan mewah, bersih, dan dioptimalkan untuk perangkat mobile (smartphone) & desktop.
2. **Katalog Produk Nyata**:
   - **Tenderloin** (Kode 1001) – Has Dalam
   - **Striploin** (Kode 1002) – Has Luar
   - **Striploin Steak Ready** (Kode 1003) – Siap Panggang / Masak
   - **Creastmeat** (Kode 1004) – Daging Olahan Istimewa
3. **Simulasi Label Fisik Interaktif (100×75 mm)**:
   - Menampilkan replika label cetak asli lengkap dengan logo Halal Indonesia, registrasi NKV, tanggal potong, dan instruksi suhu simpan.
   - **Live CODE128 Barcode Generator**: Barcode 23-digit nyata yang di-render secara dinamis dalam format vektor SVG murni tanpa butuh CDN/koneksi internet.
4. **Formulir Pemesanan Cepat ke WhatsApp**:
   - Kalkulator pemesanan interaktif (pilihan produk, suhu Chill/Frozen, jumlah Kg, catatan).
   - Menghasilkan format pesan WhatsApp rapi secara otomatis sekali klik.
5. **Edukasi Cold Chain (Rantai Dingin)**:
   - Membedakan standar simpan **CHILL (0°C)** (hingga 90 hari) dan **FROZEN (-18°C)** (hingga 365 hari).
6. **Keabsahan & Legalitas Terpercaya**:
   - Sertifikasi Halal Indonesia.
   - Nomor Kontrol Veteriner **NKV RPH-3276041-016**.
7. **Performa Super Cepat**:
   - Zero framework overhead (Pure Semantic HTML5 + Modern CSS + Vanilla JS).
   - Ukuran file sangat ringan (< 100 KB total), loading di bawah 100 milidetik.

---

## 🛠️ Cara Mengubah Data & Kontak

### 1. Mengganti Nomor WhatsApp Pemesanan
Buka file `index.html` dan cari bagian script di bagian bawah:
```javascript
// Ganti nomor WhatsApp Anda di sini (format 628xxxxxxxxxx tanpa + atau spasi)
const WA_NUMBER = "6281200000000";
const WA_DISPLAY = "+62 812-0000-0000";
```
Semua tombol pemesanan produk, formulir cepat, dan tombol floating WhatsApp di website akan otomatis terhubung ke nomor tersebut.

### 2. Mengubah Jam Buka / Alamat
Cari bagian teks di dalam `index.html`:
- Alamat: `Jl. Raya Tapos RT. 01/03, Kel. Tapos, Kec. Tapos, Kota Depok, Jawa Barat`
- Jam Buka: `Senin – Sabtu: 07.00 – 17.00 WIB`

---

## 🚀 Panduan Deploy Online (Gratis 100%)

Karena website ini berjenis statis (HTML/CSS/JS murni tanpa PHP/database), Anda bisa menghostingnya secara **gratis selamanya** dengan kecepatan CDN global dan HTTPS (SSL) otomatis:

### Opsi A: Cloudflare Pages (Sangat Direkomendasikan)
1. Buat akun di [pages.cloudflare.com](https://pages.cloudflare.com).
2. Hubungkan ke repository Git Anda, atau cukup drag & drop folder ini ke dashboard Cloudflare Pages.
3. Website langsung aktif dalam hitungan detik. Bisa disambungkan ke domain sendiri (misal `cmmmeat.com` atau `marsha.id`).

### Opsi B: Vercel / Netlify
1. Buka [vercel.com](https://vercel.com) atau [netlify.com](https://netlify.com).
2. Masukkan repository git atau upload folder proyek ini.
3. Deploy instan selesai.

### Opsi C: GitHub Pages
1. Push proyek ini ke repository GitHub Anda (misal `cmm-meat`).
2. Masuk ke **Settings** > **Pages** > pilih branch `main`.
3. Website akan live di alamat `https://username.github.io/cmm-meat/`.

---

## 📁 Struktur Berkas

```text
cmm-meat/
├── index.html       # File utama website lengkap
├── README.md        # Panduan penggunaan & deployment
├── logo.png         # Logo resmi CMM Meat (700x700)
├── ccm.png          # Logo high-resolution CMM Meat (1600x1600)
├── icon.png         # Favicon browser & web icon
└── halal.svg        # Vektor resmi logo Halal Indonesia
```

---

&copy; PT. Berkah Marsha Sejahtera – Seluruh hak cipta dilindungi.
