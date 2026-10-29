# CMM Meat – Website Profil & Pemesanan Daging

Website profil dan katalog resmi untuk **CMM Meat (Local Meat Shop)**, diproduksi oleh **PT. Berkah Marsha Sejahtera** (Depok, Jawa Barat).

Dibuat sebagai bonus eksklusif yang melengkapi sistem aplikasi Marsha Beef.

---

## 🌟 Fitur Utama

1. **Desain Modern & Responsif**: Tampilan mewah, bersih, dan dioptimalkan 100% untuk smartphone (mobile) & desktop tanpa horizontal overflow.
2. **Katalog Potongan Pilihan**:
   - **Tenderloin** (Has Dalam) – Potongan terempuk, rendah lemak.
   - **Striploin** (Has Luar) – Favorit steak grill dengan aroma fat-cap gurih.
   - **Striploin Steak Ready** – Porsi rapi siap panggang / masak untuk resto & keluarga.
   - **Creastmeat** – Potongan olahan berkaldu kaya rasa untuk rendang, semur, dan sup.
3. **Peta Anatomi Sapi Interaktif**: Edukasi visual bagian karkas sapi lengkap dengan tingkat keempukan, marbling, dan saran metode masak.
4. **Panduan Kematangan Steak (Steak Doneness Master)**: Visual irisan melintang, target temperatur inti (°C), dan panduan waktu panggang (Rare hingga Well Done).
5. **Party & BBQ Meat Planner**: Kalkulator porsi daging cerdas sesuai jumlah tamu dan jenis hidangan (Steak / Shabu / BBQ Santai).
6. **Formulir Pemesanan Cepat ke WhatsApp**:
   - Kalkulator pemesanan interaktif (pilihan produk, suhu Chill/Frozen, jumlah Kg, catatan).
   - Menghasilkan format pesan WhatsApp rapi secara otomatis sekali klik ke nomor resmi CS.
7. **Panduan Cold Chain & Tips Thawing**:
   - Membedakan standar simpan **CHILL (0°C)** (hingga 90 hari) dan **FROZEN (-18°C)** (hingga 365 hari).
   - 3 metode pencairan daging beku yang higienis tanpa merusak nutrisi.
8. **Keabsahan & Legalitas Terpercaya**:
   - Sertifikasi Halal Indonesia resmi.
   - Nomor Kontrol Veteriner **NKV RPH-3276041-016**.
9. **Performa Super Cepat**:
   - Zero framework overhead (Pure Semantic HTML5 + Modern CSS + Vanilla JS).
   - Ukuran file sangat ringan, loading instan di bawah 100 milidetik, offline-ready.

---

## 🛠️ Cara Mengubah Data & Kontak

### 1. Mengganti Nomor WhatsApp Pemesanan
Buka file `index.html` dan cari bagian script di bagian bawah:
```javascript
// Nomor WhatsApp pemesanan aktif
const WA_NUMBER = "6285891955438";
const WA_DISPLAY = "+62 858-9195-5438";
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

Crafted With ☕ By [idnx](https://saepullrock.tech)  
&copy; PT. Berkah Marsha Sejahtera – Seluruh hak cipta dilindungi.
