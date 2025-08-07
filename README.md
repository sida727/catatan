# INSTALL TERMUX ANDROID TANPA ROOT
## Vidoe Instalasi: [sida57](https://www.youtube.com/@sida57)
## Poin-poin
* [Unduh termux-app releases terbaru](#unduh)
* [Izinkan instal aplikasi tidak dikenal](#instal)
* [Atur repository](#repo)
* [Izinkan akses penyimpanan](#akses)
* [Update packages](#update)
* [Upgrade packages](#upgrade)
* [Perintah Dasar](#perintah)

---
<br>

### 1. Unduh termux-app releases terbaru <a name=unduh></a>
```
https://github.com/termux/termux-app/releases
```
<br>

### 2. Izinkan instal aplikasi tidak dikenal <a name=instal></a>
<img src="/documentation/Screenshot_aplikasi_tidak_dikenal.jpg"/>
<br>

### 3. Atur repository <a name=repo></a>
```
termux-change-repo
```

* pilih Single mirror <ok>
<img src="/documentation/Screenshot_single_mirror.jpg"/>

* pilih linux.domainesia
<img src="/documentation/Screenshot_linux.domainesia.jpg"/>
<br>

### 4. Izinkan akses penyimpanan <a name=akses></a>
```
termux-setup-storage
```
<img src="/documentation/Screenshot_akses_penyimpanan.jpg"/>
<br>

### 5. Update packages <a name=update></a>
```
pkg update
```
<img src="/documentation/Screenshot_update.jpg"/>
<br>

### 6. Upgrade packages <a name=upgrade></a>
```
pkg upgrade
```
tekan y sampay selesai

<img src="/documentation/Screenshot_upgrade.jpg"/>
<br>

## 6. Perintah Dasar <a name=perintah></a>
Beberapa perintah dasar yang umum digunakan adalah:
 * **pkg update && pkg upgrade:** Memperbarui daftar paket dan meng-upgrade paket yang sudah terpasang.
 * **pkg install <nama_paket>:** Menginstal paket atau aplikasi baru.
 * **ls:** Melihat daftar file dan folder di direktori saat ini.
 * **cd <nama_folder>:** Pindah ke direktori lain.
 * **pwd:** Menampilkan direktori kerja saat ini.
 * **mkdir <nama_folder>:** Membuat folder baru.
 * **rm <nama_file>:** Menghapus file.
 * **mv <file_asal> <file_tujuan>:** Memindahkan atau mengganti nama file.
 * **cp <file_asal> <file_tujuan>:** Menyalin file.
 * **cat <nama_file>:** Menampilkan isi file.
