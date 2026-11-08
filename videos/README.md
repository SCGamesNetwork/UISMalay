# Video Dokumentasi Resmi (After Movie)

Direktori ini digunakan untuk menyimpan file video dokumentasi resmi UIS × UMMI:

- **Path file video**: `public/videos/after-movie.mp4`
- **Format rekomendasi**: MP4 (Video codec H.264 / AAC Audio)
- **Resolusi rekomendasi**: Full HD 1080p (1920x1080) atau 4K (3840x2160)
- **Konfigurasi status**: Diatur pada `src/data/site-config.ts`

### Cara Mengaktifkan Video:
1. Masukkan file video hasil render ke direktori ini dengan nama `after-movie.mp4`.
2. Pada file `src/data/site-config.ts`, ubah:
   ```typescript
   status: 'ready', // Dari 'coming_soon' menjadi 'ready'
   duration: '03:45', // Ganti dengan durasi aktual video Anda
   ```
3. Website akan otomatis memutar video lokal Anda secara native tanpa bergantung pada YouTube atau layanan eksternal.
