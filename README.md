Untuk push (mengunggah) proyek ke GitHub, ikuti langkah-langkah berikut:

1. Buat Repository di GitHub
Buka GitHub.
Klik ikon "+" (pojok kanan atas) → New repository.
Beri nama repository dan klik Create repository.
2. Hubungkan Repository Lokal ke GitHub
Buka Terminal atau Command Prompt, lalu jalankan perintah berikut:

Masuk ke folder proyek (jika belum):

sh
Copy
Edit
cd /path/to/proyek-anda
Inisialisasi Git (jika belum ada):

sh
Copy
Edit
git init
Tambahkan Repository GitHub sebagai Remote:

sh
Copy
Edit
git remote add origin https://github.com/username/nama-repo.git
Ganti username dengan nama akun GitHub dan nama-repo dengan nama repository yang dibuat.

3. Tambahkan dan Commit File
Tambahkan semua file ke Git:
sh
Copy
Edit
git add .
Buat commit dengan pesan:
sh
Copy
Edit
git commit -m "First commit"
4. Push ke GitHub
Gunakan perintah berikut untuk mengunggah kode:

sh
Copy
Edit
git push -u origin main
Jika branch utama menggunakan master, ganti main dengan master.

5. Verifikasi di GitHub
Buka repository GitHub Anda dan pastikan file sudah terunggah.

Jika ada kendala atau repository menggunakan autentikasi SSH, beritahu saya! 😊







