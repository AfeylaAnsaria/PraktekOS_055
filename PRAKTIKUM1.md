**1.LANGKAH INSTALASI UBUNTU:**

1.  **Persiapan Awal**

-   Download Ubuntu ISO dari ubuntu.com

-   Buka VMware Fusion

-   Klik "New" untuk membuat VM baru.

2.  **Buat Konvigurasi VM**

```{=html}
<!-- -->
```
a.  Buka virtualBox dan Klik New

b.  Beri nama VM

c.  Mengatur spesifikasi sesuai perintah:

-   CPU: 2 core

-   RAM: 4096 MB

-   HDD: 25 GB

3.  **Proses Instalasi**

-   Pilih "Install Ubuntu"

-   Pilih Bahasa, Lokasi, dan kt=yboard layout

-   Pilih "something else" untuk partisi manual:

a.  Partisi / (root): 20 GB -ext4

b.  Partisi / Storage: 5 GB -ext4

c.  Partisi swap: 1.5 GB

-   Untuk mengatur User

a.  Setting hostname: PrakOS_nrp

b.  Buat Username dan pw

```{=html}
<!-- -->
```
4.  **Verifikasi Instalasi**

-   Buka terminal dan siap dijalankan

**\*Kesimpulan:** Ubuntu adlah salah satu distribusi Linux dengan
melakukan konfigurasi VM yang memungkinkan menjalankan banyak system
operasi, dan memiliki interface instalasi yg user-friendly dibandingkan
distro linux yang lain.

**2. Perbedaan Debian 12 (Bookworm) dengan Debbian 11 (Bullsye)**

+-------------------+----------------------+--------------------------+
| **Aspek**         | **Debian 12          | **Debian 11 (Bullsye)**  |
|                   | (Bookworm)**         |                          |
+===================+======================+==========================+
| **Versi Kernel**  | Linux kernel 6.1 LTS | Linux Kernel 5.10 LTS    |
+-------------------+----------------------+--------------------------+
| **Kebutuhan       | RAM minim: 512MB     | RAM minim: 512MB         |
| sistem**          |                      |                          |
|                   | Ruang disk minim:    | Ruang disk minim: 2GB    |
|                   | 2GB                  |                          |
|                   |                      | Prosesor 1 GHz           |
|                   | Prosesor 1 GHz       |                          |
+-------------------+----------------------+--------------------------+
| **Systemed**      | Systemed 252         | Systemed 247             |
+-------------------+----------------------+--------------------------+
| **Perbedaan       | Phyton: 3.9          | Phyton: 3.11             |
| Package**         |                      |                          |
|                   | LibreOffice: 7.0     | LibreOffice: 7.4         |
|                   |                      |                          |
|                   | GNOME: 3.38          | GNOME: 43                |
|                   |                      |                          |
|                   | KDE Plasma: 5.20     | KDE Plasma: 5.27         |
+-------------------+----------------------+--------------------------+
| **Systemd**       | Version 252          | Version 247              |
+-------------------+----------------------+--------------------------+
| **OpenSSL**       | 3.0                  | 1.1.1                    |
+-------------------+----------------------+--------------------------+
| **Apache**        | 2.4.57               | 2.4.54                   |
+-------------------+----------------------+--------------------------+

**\*Kesimpulan:** Debian 12 membawa pembaruan signifikan di sisi kernel,
kebutuhan system, keamanan, tapi tetap mempertahankan kebuthan system yg
ringan sepertei sebelumya.

**3. Cek Environment CPU-Z**

  -----------------------------------------------------------------------
  **Perangkat**                     **Rincian**
  --------------------------------- -------------------------------------
  **CPU name**                      AMD Ryzen 5 7540U

  **RAM**                           16GB

  **Jumlah corre**                  6 cores

  **grafis**                        AMD Radeon™ 740M Graphics

  **Base clock**                    3.2 GHz
  -----------------------------------------------------------------------

**\*Kesimpulan:** dengan aplikasi CPU-Z pengguna dapat mengecek
spesifikasi hardware secara akurat, termasuk clock kecepatan CPU, dan
lain-lain. Aplikasi ini juga dapat memastikan kompatibilitas komponen
pada system.

4.  **Cara Lain**

-   Menampilkan **LSCPU**

-   Melalui Task Manager

-   Menggunakan **CMD**

**\*Kesimpulan:** selain **CPU-Z** spesifikasi hardware dapat dicek
melalui LSCPU,task manager, CMD, Dan lain sebagainya. Sehingga tidak
perlu install aplikasi tambahan, akses cepat dan mudah.
