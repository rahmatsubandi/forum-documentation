# Salam!

Selamat datang di panduan instalasi survei - ANRI

&copy; Rahmat Subandi - 2021

<hr>

# Source Code

Berkas Source Code pada seluruh aplikasi ini tersedia di Repo GitHub khusus yang telah saya buat. Untuk mengaksesnya memerlukan izin dari saya sendiri.

[Link Source Code](https://github.com/rahmatsubandi/forum/)

> Pastikan akun GitHub anda mendapatkan izin dari pemilik repo.

<hr>

# Memulai Instalasi

## Tahap Pertama

> Pastikan anda telah mempunyai XAMPP dan telah menyalakan/menjalankan server lokalnya.
>
> ![xampp](/images/xampp.png)

1. Unduh kode

   Silahkan download file yang berada di repo GitHub saya di branch/cabang yang bernama [cms](https://github.com/rahmatsubandi/forum/)

   ![Download](/images/download_code.png)

2. Membuat folder baru di htdocs

   Setelah file berhasil di download, pindahkan ke dalam derektori/folder htdocs

   ![Htdocs](/images/htdocs.png)

   Sebagai contoh ketika selesai mendownload saya membuat folder yang bernama <b>e-survei</b> di dalam folder htdocs.

3. Mengekstrak file

   - Setelah membuat folder didalam folder htdocs buka file yang berbentuk ZIP

   ![ZIP](/images/zip.png)

   - Lalu klik folder <b>forum-cms</b> maka akan berisikan:

   ![Isi ZIP](/images/isi-zip.png)

   - Pilih semua file-nya <b>(ctrl+a)</b> atau bisa klik '<b>Extract To</b>' dan pilih tujuan pada direktori/folder yang sudah di buat di htdocs

   ![Isi ZIP yang sudah di Extract](/images/isi-zip-extract.png)

4. Selesai.

## Tahap Kedua

> Pastikan anda telah menyelesaikan Tahap Pertama dengan benar! Dan Xampp sudah di jalankan.

1. Membuat Database

   Buka Browser anda, lalu pergi ke http://127.0.0.1/phpmyadmin/index.php untuk membuat database

   - Klik New untuk membuat database baru
     ![Klik New](/images/klik-new.png)
   - Lalu buat database (Sebagai contoh saya membuatnya dengan nama <b>e-survei-anri</b>)
     ![Create DB New](/images/create-db.png)
   - Lalu tekan tombol <b>create</b>
   - Setelah selesai/berhasil maka akan ada sebuah pemberitahuan dan halaman akan otomatis menuju ke
     ![Create DB New Success](/images/redirect-success.png)

2. Memulai Instalasi dengan Installer

   Setelah berhasil membuat database, ketikan http://localhost/e-survei/install.php dibrowser, maka tampilanya akan seperti:
   ![Input URL](/images/input-url.png)

   - Pada bagian pertama terdapat pilihan bahasa, biarkan saja dengan defaultnya, yaitu English. Klik tombol <b>'Save and continue'</b>

   - Lalu pada bagian ini installer akan mengecek persyaratan apa saja yang dibutuhkan, jika semua persyaratan memenuhi, seluruh tabel akan berwarna hijau, seperti gambar dibawah ini:
     ![Verify requirements](/images/verify-req.png)
     Jika semua-nya hijau Klik tombol <b>'Continue'</b>

   - Tahap selanjutnya yaitu persiapan database
     ![Database Setup](/images/db-setup.png)

     - Pada bagian Inputan <b>Database Name</b> isikan dengan nama database yang sudah dibuat pada tahap pertama yaitu <b>e-survei-anri</b>.
       Untuk bagian <b>Database Username</b> dan <b>Database Password</b> biarkan saja defaultnya. Ini merupakan default konfigurasi database di localhost, kecuali menginstall di server maka memerlukan isian yang sesuai dan mengatur bagian <b>ADVANCED OPTIONS</b>.
       ![Database Setup Anri](/images/db-setup-anri.png)
     - Lalu klik tombol test connection
     - Jika konfigurasi berhasil, seperti nama database yang sesuai, database username, dan database password maka tampilanya/akan ada notifikasi seperti gambar dibawah ini:
       ![Database Setup Anri Success](/images/db-setup-anri-success.png)
     - Selanjutnya klik tombol <b>Save and continue</b>

   - Tunggu proses instalasi otomatis selesai, jika sudah selesai akan seperti ini:
     ![Installasi](/images/installing.png)
     Klik tombol <b>Continue</b>

   - Proses selanjutnya adalah membuat akun untuk Super Admin, seperti membuat email, username(email dan username disini akan dipakai untuk login), password, dan memilih zona waktu.
     ![Create Admin](/images/create-admin.png)
     Sebagai contoh, saya mengisinya dengan:

     - Email : superadmin@anri.com
     - Username : superadmin
     - Password : password
     - Timezone : Asia/Jakarta +07:00

   - Klik tombol <b>Create & continue</b>

   - Lalu jika installasi seluruhan berhasil maka akan seperti:
     ![Finished](/images/finished.png)
     Setelah itu, klik tombol <b>Go to Survei ANRI</b>

   - Maka tampilan setelah mengklik tombol <b>Go to Survei ANRI</b> akan seperti:
     ![login](/images/login.png)

## Login

Pada bagian ini silahkan masuk dengan email/username dan password yang sudah dibuat saat installasi aplikasi. Sebagai contoh akun yang sudah saya buat seperti:

- Email : superadmin@anri.com
- Username : superadmin
- Password : password

## Halaman Dashboard

Dibawah ini adalah halaman utama dari dashboard
![Dashboard](/images/dashboard.png)

## Peringatan!

> Setelah masuk pada bagian dashboard ada baiknya untuk menghapus atau mengubah nama dari file install.php menjadi installan.php atau apapun, bahkan jika perlu dihapus saja.

Sebagai contoh jika bingung:

1. Buka folder project yang berada di direktori htdocs
2. Masuk kedalam folder e-survei (Jika nama folder anda tidak sama, silahkan cari saja. Intinya masuk kedalam folder project yang berisikan kode yang di ekstrak di awalan tahap)
3. Cari file install.php

   ![change-install-file](/images/change-install-file.png)

4. Lalu ubah namanya dari install.php ke installan.php <b>Atau anda bisa menghapusnya saja file install.php ini</b>
5. Selesai. Sekarang anda bisa mencoba atau memakai aplikasi E-survei ANRI ini dengan aman, dan nyaman.

# Panduan Penggunaan
