# MTsN 4 Banyuwangi — Website Profil Modern

Static website responsive dengan design system hijau madrasah, animasi scroll reveal, counter, hero video, halaman profil/visi-misi/berita/agenda/ekstrakurikuler/fasilitas/galeri/prestasi/kontak.

## Menjalankan
Bisa dibuka langsung `index.html`, atau jalankan server statis:

```bash
python3 -m http.server 8080
```

Lalu buka `http://localhost:8080`.

## Data
Konten didasarkan pada portal resmi MTsN 4 Banyuwangi dan sumber data pendidikan publik yang ditemukan saat riset. Statistik homepage 1331 siswa, 62 guru & staff, 253 berita & prestasi, 269 galeri mengikuti angka yang tampil pada portal resmi saat riset. Data lain yang belum cukup kuat sengaja diberi catatan/placeholder.

## Catatan
- Hero video memakai URL yang diberikan pengguna.
- Foto/logo memakai aset publik dari domain storage yang dirujuk portal resmi.
- Sebelum produksi, sinkronkan agenda, ekstrakurikuler lengkap, fasilitas lengkap, kontak resmi, dan data personel dengan admin madrasah.
- Tidak ada backend/CMS pada paket ini; `data/content.js` disiapkan sebagai titik awal untuk migrasi ke CMS/API.
