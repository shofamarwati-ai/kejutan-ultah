# Website Ulang Tahun

## Isi folder
- `index.html` — halaman website.
- `assets/foto-masa-kecil.png` — foto kenangan.
- `assets/monokrom.mp3` — letakkan file audio yang kamu punya hak untuk menggunakannya di sini.

## Yang perlu diedit sebelum dipublikasikan
1. Buka `index.html` dengan editor teks.
2. Cari `const NOMOR_WA_KAKAK = "6281234567890";` lalu ganti dengan nomor WhatsApp tujuan (format internasional, tanpa `+`).
3. Ubah isi surat di bagian `EDIT ISI SURAT DI BAGIAN INI`.
4. Jika ingin mengganti nama di halaman depan, ubah tulisan `Birthday Girl!`.

## Menambahkan musik
Salin file audio MP3 yang kamu miliki/hak gunakan ke folder `assets`, lalu beri nama persis `monokrom.mp3`.
Website akan mencoba memutar musik otomatis. Browser modern sering memblokir autoplay yang bersuara sebelum pengunjung berinteraksi. Jika diblokir, pengunjung cukup menekan tombol `♫ Ketuk untuk musik`.
Autoplay bersuara tidak bisa dijamin oleh website karena kebijakan browser. Gunakan file audio yang kamu miliki atau berhak gunakan; jangan mengunggah salinan lagu berhak cipta tanpa izin.

## Publikasi di GitHub Pages
1. Buat repository GitHub baru.
2. Upload seluruh isi folder ini (file `index.html`, folder `assets`, dan `README.md`) ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu proses selesai; GitHub akan menampilkan alamat website di halaman Pages.

Pastikan `index.html` berada di root repository, bukan di dalam folder tambahan.
