# Jagoan Gitar Nusantara

Game ritme bergaya Guitar Hero dengan nuansa Indonesia, dalam satu file HTML tanpa dependensi. Buka `index.html` di browser dan main.

## Fitur

- 6 lagu orisinal dengan gaya Indonesia: koplo, keroncong, gamelan, melayu, ska, dan rock. Semua suara dibuat langsung di browser dengan WebAudio, tanpa file audio.
- 4 tingkat kesulitan: Mudah (3 jalur), Sedang (4), Sulit (5), Ahli (5).
- Penggeser "Kecepatan nada" (60-140%) dan "Tempo lagu" (70-110%) di menu. Tempo hanya berlaku untuk lagu bawaan.
- Mode tanpa gagal, kalibrasi offset audio, dan skor terbaik per lagu dan tingkat, semuanya disimpan di browser.
- "Lagu sendiri": impor file audio milikmu (MP3, M4A, WAV, OGG, sampai 6 file, masing-masing maksimal 80 MB dan 12 menit). Game menganalisis ketukan dan menyusun jalur nadanya otomatis. Rak "Lagu saya" hanya berlaku selama halaman terbuka.

## Kontrol

| Aksi | Papan ketik | Layar sentuh |
| --- | --- | --- |
| Jalur 1-5 | `A` `S` `D` `F` `G` atau `1`-`5` | ketuk jalurnya |
| Star power | `Space` | tombol Star |
| Jeda | `Esc` atau `P` | tombol Jeda |

## Menjalankan

Tidak perlu build. Buka `index.html` langsung, atau sajikan lewat server statis mana pun:

```sh
python3 -m http.server 8000
```

Untuk menayangkan lewat GitHub Pages: Settings, Pages, pilih branch `main` dan folder `/ (root)`.

## Catatan

- Font (Bungee, Plus Jakarta Sans) dimuat dari Google Fonts. Tanpa internet, game tetap jalan dengan font bawaan sistem.
- Lagu dari Spotify atau Apple Music tidak bisa disambungkan langsung. Lagu streaming berDRM, dan Spotify tidak lagi menyediakan analisis ketukan untuk aplikasi baru. Pakai file milikmu lewat "Lagu sendiri".
- Semua lagu bawaan adalah komposisi orisinal. Tidak ada lagu berhak cipta di repositori ini.
- Lisensi belum dipilih. Tambahkan berkas `LICENSE` sesuai keinginanmu sebelum repositori dibuka untuk umum.
