# warung-madura

## Prasyarat

Pastikan Anda telah menginstal perangkat lunak berikut:

- [Node.js](https://nodejs.org/) versi 14 atau lebih baru
- [npm](https://www.npmjs.com/) versi 6 atau lebih baru

## Langkah-langkah Menjalankan Program

1. **Klon Repository**

   Klon repository ini ke komputer lokal Anda dengan perintah berikut:

   ```bash
   git clone https://github.com/Ayub-Budi/warung-madura.git
   ```
   Gantilah `username` dan `repository` dengan nama pengguna GitHub Anda dan nama repository.

2. **Masuk ke Direktori Proyek**

   Arahkan terminal Anda ke direktori proyek:

   ```bash
   cd repository
   ```

3. **Buat File .env**

   Buat file `.env` di root direktori proyek Anda dan tambahkan variabel lingkungan berikut:

   ```env
   VITE_BASE_URL="URL"
   ```
   Gantilah `URL` dengan URL yang sesuai untuk basis API Anda atau konfigurasi lainnya.

4. **Install Dependencies**

   Install semua dependencies yang diperlukan dengan menjalankan perintah berikut:

   ```bash
   npm install
   ```

5. **Jalankan Mode Pengembangan**

   Untuk menjalankan aplikasi dalam mode pengembangan, gunakan perintah berikut:

   ```bash
   npm run dev
   ```
   Aplikasi akan berjalan di `http://localhost:5173/` atau port lain yang ditentukan oleh sistem Anda. Anda dapat mengaksesnya melalui browser web.

6. **Build Aplikasi**

   Jika Anda ingin membangun aplikasi untuk produksi, jalankan perintah berikut:

   ```bash
   npm run build
   ```
   Ini akan membuat bundle produksi yang dioptimalkan di folder `dist`.

7. **Menjalankan Build Produksi**

   Untuk menjalankan build produksi yang telah dibuat, gunakan perintah berikut:

   ```bash
   npm run serve
   ```
   Ini akan menjalankan aplikasi yang sudah dibuild dan dapat diakses melalui browser di `http://localhost:5173/` atau port lain yang ditentukan.
