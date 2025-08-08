# Instalasi Nginx

## Video Instalasi: [sida57](https://www.youtube.com/@sida57)
* [Mengunduh Aplikasi Termux 📥](#unduh)
* [Mengaktifkan Sumber Tidak Dikenal ⚙️](#sumber)
* [Mengatur Repository Termux 📦](#repo)
* [Memberikan Izin Penyimpanan 📂](#izin)
* [Memperbarui dan Meningkatkan Paket 🚀](#perbarui)
* [Perintah Dasar Termux 💻](#perintah)

## 1. Mengunduh Aplikasi Termux 📥 <a name=unduh></a>

### Anda harus mengunduh file APK Termux terbaru dari halaman GitHub resmi mereka. Penting untuk mengunduh dari sumber ini karena versi di Google Play Store tidak lagi diperbarui.
* Kunjungi
   ~~~
   https://github.com/termux/termux-app/releases
   ~~~
   
* Unduh file **.apk** versi terbaru yang sesuai untuk perangkat Anda.
   
## 2. Mengaktifkan Sumber Tidak Dikenal ⚙️ <a name=sumber></a>

<img src="/documentation/Screenshot_aplikasi_tidak_dikenal.jpg"/>

### Setelah mengunduh, Anda perlu memberikan izin kepada perangkat Android Anda untuk menginstal aplikasi dari sumber eksternal.
* Pergi ke Pengaturan di perangkat Anda.
* Cari menu Keamanan atau Privasi.
* Cari dan aktifkan opsi Instal aplikasi yang tidak dikenal atau Sumber tidak dikenal.
* Pilih aplikasi tempat Anda mengunduh file APK (misalnya, browser Chrome atau File Manager) dan berikan izin.
  
## 3. Mengatur Repository Termux 📦 <a name=repo></a>

### Setelah instalasi, langkah selanjutnya adalah mengatur repository atau "gudang" paket. Mengganti repository dapat meningkatkan kecepatan unduhan dan memastikan Anda mendapatkan paket terbaru.
 * Buka aplikasi Termux yang telah terinstal.
 * Ketik perintah
   ~~~
   termux-change-repo
   ~~~
   dan tekan Enter.
 * Pilih opsi Single mirror dan tekan OK.
   
   <img src="/documentation/Screenshot_single_mirror.jpg"/>
 * Pilih mirror yang cepat dan andal, seperti linux.domainesia.com, dan tekan OK untuk menyelesaikannya.

   <img src="/documentation/Screenshot_linux.domainesia.jpg"/>

## 4. Memberikan Izin Penyimpanan 📂 <a name=izin></a>

### Agar Termux dapat mengakses file di penyimpanan internal perangkat Anda, Anda harus memberikan izin secara manual.

<img src="/documentation/Screenshot_akses_penyimpanan.jpg"/>

 * Ketik perintah termux-setup-storage dan tekan Enter.
 * Sebuah jendela pop-up akan muncul meminta izin untuk mengakses file. Ketuk Izinkan.
 * Sekarang Anda dapat mengakses folder penyimpanan utama Anda di Termux melalui direktori storage/shared.

## 5. Memperbarui dan Meningkatkan Paket 🚀 <a name=perbarui></a>

### Ini adalah langkah krusial untuk memastikan semua paket Anda terbaru dan menghindari masalah kompatibilitas.
 * Ketik
   ~~~
   pkg update
   ~~~
   <img src="/documentation/Screenshot_update.jpg"/>

   dan tekan Enter. Perintah ini akan memperbarui daftar paket yang tersedia.
 * Setelah selesai, ketik
   ~~~
   pkg upgrade
   ~~~
   <img src="/documentation/Screenshot_upgrade.jpg"/>

   dan tekan Enter. Ini akan meningkatkan semua paket yang terinstal ke versi terbaru.
 * Saat diminta untuk melanjutkan (misalnya, Do you want to continue? [Y/n]), cukup ketik y dan tekan Enter sampai proses selesai.

## Perintah Dasar Termux 💻

### Berikut adalah beberapa perintah penting yang perlu Anda ketahui untuk memulai:
 * pkg update && pkg upgrade: Perintah ini menggabungkan pembaruan daftar paket dan peningkatannya.
 * pkg install <nama_paket>: Digunakan untuk menginstal paket atau aplikasi baru. Contoh: pkg install python.
 * ls: Menampilkan daftar file dan folder di direktori saat ini.
 * cd <nama_folder>: Untuk pindah ke direktori lain. Contoh: cd Documents.
 * pwd: Menampilkan nama direktori kerja saat ini.
 * mkdir <nama_folder>: Membuat folder baru. Contoh: mkdir ProyekBaru.
 * rm <nama_file>: Menghapus file. Contoh: rm file_lama.txt.
 * mv <file_asal> <file_tujuan>: Memindahkan atau mengganti nama file.
 * cp <file_asal> <file_tujuan>: Menyalin file.
 * cat <nama_file>: Menampilkan isi dari sebuah file teks.

