# 📚 Setup Guide - GitHub Profile README

Panduan lengkap untuk mengaktifkan semua fitur di README profile GitHub Anda.

---

## 🚀 Quick Start

### 1. **Upload ke GitHub**

```bash
# Pastikan Anda berada di direktori repository
cd hasanmahfudh11211

# Initialize git (jika belum)
git init

# Add semua file
git add .

# Commit
git commit -m "✨ Update awesome GitHub profile README"

# Add remote (ganti dengan URL repository Anda)
git remote add origin https://github.com/hasanmahfudh11211/hasanmahfudh11211.git

# Push ke GitHub
git push -u origin main
```

---

## 🐍 Mengaktifkan Snake Animation

Snake animation memerlukan GitHub Actions workflow yang sudah dibuat di `.github/workflows/snake.yml`.

### Langkah-langkah:

1. **Push file workflow ke GitHub** (sudah termasuk saat push di atas)

2. **Aktifkan GitHub Actions:**
   - Buka repository di GitHub
   - Klik tab **"Actions"**
   - Jika diminta, klik **"I understand my workflows, go ahead and enable them"**

3. **Jalankan workflow manual (opsional):**
   - Di tab Actions, klik workflow **"Generate Snake Animation"**
   - Klik **"Run workflow"** > **"Run workflow"**
   - Tunggu beberapa menit sampai selesai

4. **Verifikasi:**
   - Setelah workflow selesai, cek branch **"output"**
   - Seharusnya ada file `github-contribution-grid-snake.svg`
   - Snake animation akan muncul di README Anda!

### Troubleshooting Snake Animation:

Jika snake tidak muncul:
- Pastikan workflow berhasil dijalankan (cek tab Actions)
- Pastikan branch "output" sudah dibuat
- Tunggu beberapa menit untuk cache refresh
- Coba hard refresh browser (Ctrl + F5)

---

## 📊 GitHub Stats - Troubleshooting

Jika GitHub stats tidak muncul:

### Solusi 1: Tunggu Beberapa Menit
API GitHub kadang lambat atau rate limited. Tunggu 5-10 menit lalu refresh.

### Solusi 2: Hard Refresh Browser
```
Windows: Ctrl + F5
Mac: Cmd + Shift + R
```

### Solusi 3: Clear Cache
Hapus cache browser atau buka di Incognito/Private mode.

### Solusi 4: Cek API Status
Kunjungi: https://github-readme-stats.vercel.app/api?username=hasanmahfudh11211

Jika muncul error, tunggu beberapa saat karena API sedang overload.

---

## ⚙️ Konfigurasi Opsional

### 1. **Wakatime Stats** (Opsional)

Untuk menampilkan coding time stats:

1. Daftar di [Wakatime](https://wakatime.com/)
2. Install Wakatime plugin di IDE Anda
3. Dapatkan API key dari dashboard Wakatime
4. Stats akan otomatis muncul setelah beberapa hari coding

**Jika tidak menggunakan Wakatime**, Anda bisa hapus section ini di README (baris 367-373).

### 2. **Update Informasi Personal**

Edit file `readme.md` untuk update:

- **Lokasi:** Baris 34 - Ganti "Pekalongan, Central Java"
- **Email:** Baris 391 - Ganti "layar89000@gmail.com"
- **Instagram:** Baris 397 - Ganti "yahahahuseinnn"
- **LinkedIn:** Baris 400 - Ganti "hasanmahfudh"
- **Jumlah Repositories:** Baris 18 - Update angka sesuai jumlah repo Anda

### 3. **Update Project List**

Edit section "Featured Projects" (baris 161-226):

- Ganti nama repository sesuai project Anda
- Update deskripsi di tabel Project Portfolio (baris 228-241)

---

## 🎨 Customization

### Mengubah Warna Tema

Warna utama yang digunakan:
- **Primary:** `#ff6e96` (Pink/Red)
- **Secondary:** `#00d9ff` (Cyan/Blue)
- **Theme:** `radical`

Untuk mengubah tema, ganti parameter `theme=radical` dengan:
- `tokyonight`
- `dracula`
- `gruvbox`
- `onedark`
- `cobalt`
- `synthwave`
- `highcontrast`
- `dark`

### Mengubah Warna Contribution Calendar

Edit baris 330:
```markdown
<img src="https://ghchart.rshah.org/00d9ff/hasanmahfudh11211" />
```

Ganti `00d9ff` dengan kode warna hex lain:
- `ff6e96` - Pink
- `00ff00` - Green
- `ffa500` - Orange
- `9b59b6` - Purple

---

## 📝 Maintenance

### Update Rutin yang Disarankan:

1. **Setiap Bulan:**
   - Update jumlah commits di "Highlights" (baris 155)
   - Update jumlah repositories (baris 18)
   - Update project status jika ada yang selesai

2. **Setiap 3 Bulan:**
   - Review dan update skills percentage (baris 342-361)
   - Update learning badges (baris 453-456)
   - Update 2025 goals checklist (baris 460-464)

3. **Setiap 6 Bulan:**
   - Update "Last Updated" date (baris 498)
   - Review semua konten untuk akurasi

---

## 🔍 Monitoring

### Cek Kesehatan README:

1. **GitHub Actions Status:**
   - Kunjungi: `https://github.com/hasanmahfudh11211/hasanmahfudh11211/actions`
   - Pastikan workflow "Generate Snake Animation" berjalan sukses

2. **Stats API Status:**
   - GitHub Stats: `https://github-readme-stats.vercel.app/api?username=hasanmahfudh11211`
   - Streak Stats: `https://streak-stats.demolab.com?user=hasanmahfudh11211`

3. **Profile Views:**
   - Cek badge "Profile Views" untuk melihat berapa orang yang mengunjungi profile Anda

---

## 🆘 FAQ

### Q: Snake animation tidak muncul?
**A:** Pastikan workflow sudah jalan di tab Actions. Tunggu 5-10 menit setelah workflow selesai.

### Q: GitHub stats menunjukkan error?
**A:** API mungkin rate limited. Tunggu beberapa jam atau gunakan Incognito mode.

### Q: Bagaimana cara menambah project baru?
**A:** Edit section "Featured Projects" dan "Project Portfolio" di README.md.

### Q: Bisa ganti warna tema?
**A:** Ya! Ganti parameter `theme=radical` dengan tema lain (lihat section Customization).

### Q: Profile views tidak update?
**A:** Badge profile views dari Komarev kadang delay. Tunggu beberapa jam.

---

## 📞 Support

Jika ada masalah atau pertanyaan:

1. Cek dokumentasi GitHub Actions: https://docs.github.com/en/actions
2. Cek dokumentasi GitHub README Stats: https://github.com/anuraghazra/github-readme-stats
3. Cek dokumentasi Snake Action: https://github.com/Platane/snk

---

## ✨ Tips & Tricks

1. **Gunakan Shields.io** untuk membuat custom badges
2. **Update README secara berkala** agar tetap fresh
3. **Tambahkan project baru** saat Anda membuat repository baru
4. **Gunakan emoji** untuk membuat README lebih menarik
5. **Keep it simple** - Jangan terlalu banyak animasi yang bisa memperlambat loading

---

**🎉 Selamat! README profile GitHub Anda sekarang sudah siap dan terlihat profesional!**

*Last Updated: December 2025*
