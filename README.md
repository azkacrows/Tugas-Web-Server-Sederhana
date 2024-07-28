# Proyek Membangun Web Server Sederhana Menggunakan Apache dan NGINX oleh Dicoding

## Deskripsi Proyek

Proyek ini merupakan bagian dari kursus "Belajar Jaringan Komputer untuk Pemula" yang diselenggarakan oleh Dicoding. Tujuan dari proyek ini adalah untuk memberikan pemahaman tentang cara membangun web server sederhana menggunakan Apache dan NGINX, serta cara mengkonfigurasi kedua server web tersebut. Proyek ini juga mencakup pembuatan aplikasi server sederhana menggunakan Express.js.

## Struktur Proyek

-   `app.js`
-   `konfigurasiApache2`
-   `konfigurasiNGINX`
-   `ports`

### Penjelasan File

#### `app.js`

File `app.js` berisi kode aplikasi server yang dibuat menggunakan Express.js, sebuah framework untuk Node.js. Aplikasi ini bertugas untuk menangani permintaan HTTP dan memberikan respons sesuai dengan logika yang telah diimplementasikan.

#### `konfigurasiApache2`

File `konfigurasiApache2` berisi konfigurasi untuk server Apache2. Konfigurasi ini meliputi pengaturan virtual host, direktori root, dan pengaturan lain yang diperlukan untuk menjalankan aplikasi web di server Apache.

#### `konfigurasiNGINX`

File `konfigurasiNGINX` berisi konfigurasi untuk server NGINX. Konfigurasi ini meliputi pengaturan server block, lokasi root, dan pengaturan lain yang diperlukan untuk menjalankan aplikasi web di server NGINX.

#### `ports`

File `ports` berisi informasi mengenai port yang digunakan oleh server Apache dan NGINX. File ini membantu dalam mengelola dan mengingat port mana yang harus digunakan saat menjalankan server.

## Fitur Utama

1. **Konfigurasi Apache2**: Pengaturan dan konfigurasi dasar untuk menjalankan server web menggunakan Apache2.
2. **Konfigurasi NGINX**: Pengaturan dan konfigurasi dasar untuk menjalankan server web menggunakan NGINX.
3. **Aplikasi Server Menggunakan Express.js**: Implementasi aplikasi server sederhana menggunakan Express.js untuk menangani permintaan dan memberikan respons.
4. **Pengelolaan Port**: Informasi dan pengaturan port yang digunakan oleh server Apache dan NGINX untuk menjalankan aplikasi web.

## Cara Menggunakan

1. **Clone Repository**:

    ```sh
    git clone https://github.com/username/proyek-web-server-sederhana.git
    ```

2. **Install Dependencies**:

    Pindah ke direktori proyek dan install dependencies yang diperlukan dengan perintah berikut:

    ```sh
    cd proyek-web-server-sederhana
    npm install
    ```

3. **Jalankan Aplikasi Server**:

    Jalankan aplikasi server menggunakan perintah berikut:

    ```sh
    node app.js
    ```

4. **Konfigurasi Apache2**:

    - Salin isi dari file `konfigurasiApache2` ke file konfigurasi Apache yang sesuai (misalnya, `/etc/apache2/sites-available/000-default.conf`).
    - Restart server Apache2 dengan perintah:

    ```sh
    sudo systemctl restart apache2
    ```

5. **Konfigurasi NGINX**:

    - Salin isi dari file `konfigurasiNGINX` ke file konfigurasi NGINX yang sesuai (misalnya, `/etc/nginx/sites-available/default`).
    - Restart server NGINX dengan perintah:

    ```sh
    sudo systemctl restart nginx
    ```

**Date**: Dec 14, 2022

**Original Repository**:\
[https://github.com/username/Tugas-web-server-sederhana](https://github.com/azkacrows/Latihan-Bootcamp/tree/main/Dicoding/submission/Web%20server%20sederhana)
