# To-Do List with JavaScript

 Aplikasi To-Do List sederhana menggunakan HTML, CSS, dan JavaScript.

 Deskripsi singkat

- Proyek ini adalah aplikasi web statis kecil untuk menambah, menandai selesai, dan menghapus tugas (to-do) di browser.
- Cocok sebagai latihan dasar DOM, event handling, dan manipulasi data di JavaScript.

 ## Struktur proyek

 ```
 index.html    # Halaman utama
 style.css     # Gaya tampilan
 script.js     # Logika aplikasi (add, toggle, remove, dst.)
 ```

 ## Prasyarat

- Browser modern (Chrome, Firefox, Edge, Safari)
- (Opsional) Node.js atau Python jika ingin menjalankan server lokal

 ## Menjalankan proyek (cara cepat)

 1. Buka folder proyek di file explorer.
 2. Klik dua kali `index.html` atau buka file tersebut di browser.

 Catatan: membuka file langsung (`file://`) sudah cukup untuk aplikasi ini. Namun jika Anda menambahkan fitur yang memuat file via fetch/AJAX, jalankan server lokal.

 ## Menjalankan dengan server lokal (disarankan)

 Berikut beberapa opsi untuk menjalankan server lokal dari folder proyek.

 1) Menggunakan Python 3 (jika sudah terpasang):

 ```powershell
 # jalankan dari folder proyek
 python -m http.server 5500
 # lalu buka http://localhost:5500 di browser
 ```

 2) Menggunakan http-server dari Node.js (jika Node/npm terpasang):

 ```powershell
 npm install -g http-server
 http-server -p 5500
 # lalu buka http://localhost:5500
 ```

 3) Menggunakan Live Server di Visual Studio Code

- Buka proyek di VS Code.
- Install ekstensi Live Server.
- Klik kanan `index.html` > Open with Live Server.

 ## Pengembangan & tips

- Jika fitur tidak merespons, buka DevTools (F12) dan periksa Console untuk error.
- Pastikan `script.js` direferensikan di `index.html` (lihat tag <script src="./script.js" defer></script>).
- Untuk persistensi data sederhana, tambahkan LocalStorage di `script.js`.

 ## Debug singkat

- Kesalahan umum: elemen tidak ditemukan (periksa ID/class di HTML vs script).
- Jika menggunakan modul ES atau import, jalankan lewat server lokal, tidak lewat `file://`.

 ## Lisensi

 Proyek ini bebas digunakan dan dimodifikasi untuk keperluan belajar. Tidak ada lisensi khusus ditetapkan.

## Kontribusi

Terima kasih jika Anda ingin berkontribusi! Berikut alur kontribusi yang disarankan untuk proyek ini.

1. Fork repositori ke akun GitHub Anda.
2. Clone fork ke mesin lokal Anda.
3. Buat branch baru untuk fitur atau perbaikan.
4. Lakukan perubahan, jalankan tes/manual check, dan commit perubahan.
5. Push branch ke fork Anda dan buka Pull Request (PR) ke repositori utama.

Contoh perintah (PowerShell):

```powershell
# fork di GitHub -> lalu clone
git clone https://github.com/<username>/To-Do-List-Tutorial.git
cd To-Do-List-Tutorial

# buat branch baru
git checkout -b feat/nama-fitur-atau-fix

# lakukan perubahan di editor, lalu
git add .
git commit -m "Tambah: deskripsi singkat perubahan"

# push ke fork
git push origin feat/nama-fitur-atau-fix

# buka Pull Request dari GitHub UI ke branch main di repositori asli
```

Panduan singkat:
- Buat pesan commit yang singkat dan jelas.
- Usahakan PR berisi perubahan yang kecil dan terfokus.
- Jelaskan tujuan perubahan di deskripsi PR dan sertakan langkah untuk mereproduksi jika perlu.
- Jika PR menyentuh fungsi penting, jalankan pengecekan manual di browser (buka `index.html` atau jalankan server lokal) sebelum submit.

Jika Anda menemukan issue, buat issue baru di tracker repo dengan langkah reproduksi dan screenshot bila perlu.

---

Butuh bantuan tambahan? Saya bisa:

- Tambahkan contoh kode penyimpanan ke LocalStorage pada `script.js`.
- Tambahkan panduan deploy ke GitHub Pages.