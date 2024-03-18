## Pemograman Berbasis Framework
Nama : IRMA YULIYANTI
NIM  : 220202086
Kelas : TI-2D <br>

![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/30c4180d-6f0b-439f-ae37-8a3e38745f68)

# 1. Pengertian Framework dan CodeIgniter <br>

# Apa yang dimaksud dengan Framework? <br>
Framework adalah sebuah abstraksi pembuatan perangkat lunak dimana didalamnya menyediakan fungsi-fungsi umum yang dapat digunakan. Framework memiliki software yang terdiri dari kerangka kerja (yang didalamnya menyediakan standar & aturan pembuatan perangkat lunak sesuai dengan bahasanya), reusability (fungsi-fungsi yang dapat digunakan secara berulang), framework juga bisa berisi program, compiler, library, tool, sets, api, komponen, dll (digunakan untuk mempermudah perangkat lunak), semua bahasa pemogramam populer memliki framework.

# Alasan menggunakan Framework
1.	Mempersingkat waktu pengembangan.
2.	Memiliki struktur aplikasi yang terorganisir.
3.	Memiliki tools & libraries yang bisa digunakan.
4.	Fleksibilitas (dapat dengan mudah terkoneksi dengan database yang berbeda, bisa menggunakan aplikasi pihak ke-3, dll).
5.	Memiliki fitur security.
6.	Teamwork (mempermudah pekerjaan saat bekerja secara tim).

# Kekurangan dari Framework
1.	Eksekusi yang lebih lambat.
2.	Butuh waktu belajar.
3.	Solusi umum untuk menyelesaikan masalah yang spesifik.
4.	Keterbatasan kendali.
5.	Masalah dependency (yaitu masalah pada setiap framework yang dibuat dengan menggunakan banyak komponen yang diambil dari orang lain sehingga saling terkait/bergantung satu sama lain).

# Apa yang dimaksud dengan CodeIgniter <br>
CodeIgniter adalah akerangka pengembangan aplikasi atau sebuah toolkit untuk membangun situs web menggunakan bahasa PHP. Tujuannya adalah untuk memungkinkan mengembangkan project jauh lebih cepat daripada kita menulis kode dari awal, dengan menyediakan kumpulan library yang kaya untuk tugas-tugas umum, serta antarmuka sederhana, dan struktur logis untuk mengakses library ini.

# Alasan mengapa menggunakan CodeIgniter
1.	Small footprint (framework yang kecil ukurannya tidak sampai lebih dari 10 mega).
2.	Memiliki peforma yang baik.
3.	Memiliki framework yang hampir tidak memerlukan konfigurasi (zero configuration).
4.	Tidak mengharuskan kita menggunakan baris perintah (command line).
5.	Tidak mengharuskan kita mematuhi aturan coding yang ketat.
6.	Tidak tertarik dengan library monolitik berskala besar seperti PEAR.
7.	Tidak ingin dipaksa untuk mempelajari bahasa templating (templating engine) (meskipun parser templat tersedia secara opsional jika kita menginginkannya).
8.	Menghindari kerumitan, lebih memilih solusi sederhana.
9.	Memiliki dokumentasi yang jelas dan menyeluruh.
10.	Menggunakan pattern MVC(Model-View-Controller) <br>
    MVC adalah sebuah pola arsitektur pada perancangan perangkat lunak berorientasi objek yang memsisahkan antara tampilan, data, dan proses. <br>
    ![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/3a5e6b4e-c805-4e25-8d22-3fe3f502f03a)

# Persyaratan Server
PHP dan Ekstensi yang Diperlukan <br>
1. PHP dan Ekstensi yang Diperlukan
2. Ekstensi PHP Opsional
3. Basis Data yang Didukung
   
PHP dan Ekstensi yang Diperlukan <br>
Diperlukan PHP versi 7.4 atau lebih baru, dengan ekstensi PHP berikut diaktifkan:
1. internasional
2. mbstring
3. json

# Ekstensi PHP Opsional
Ekstensi PHP berikut harus diaktifkan di server Anda:
1. mysqlnd (jika Anda menggunakan MySQL)
2. curl (jika Anda menggunakan CURLRequest )
3. imagick (jika Anda menggunakan kelas Gambar ImageMagickHandler)
4. gd (jika Anda menggunakan kelas Gambar GDHandler)
5. simplexml (jika Anda memformat XML) <br>

Ekstensi PHP berikut diperlukan saat Anda menggunakan server Cache:
1. memcache (jika Anda menggunakan kelas Cache MemcachedHandler dengan Memcache)
2. memcached (jika Anda menggunakan kelas Cache MemcachedHandler dengan Memcached)
3. redis (jika Anda menggunakan kelas Cache RedisHandler) <br>

Ekstensi PHP berikut diperlukan saat Anda menggunakan PHPUnit:
1. dom (jika Anda menggunakan kelas TestResponse )
2. libxml (jika Anda menggunakan kelas TestResponse )
3. xdebug (jika Anda menggunakan CIUnitTestCase::assertHeaderEmitted())
   
# Basis Data yang Didukung <br>
Basis data diperlukan untuk sebagian besar pemrograman aplikasi web. Basis data yang didukung saat ini adalah:
1. MySQL melalui MySQLidriver (hanya versi 5.1 ke atas)
2. PostgreSQL melalui Postgredriver (hanya versi 7.4 dan lebih tinggi)
3. SQLite3 melalui SQLite3driver
4. Microsoft SQL Server melalui SQLSRVdriver (hanya versi 2005 dan lebih tinggi)
5. Oracle Database melalui OCI8driver (hanya versi 12.1 dan lebih tinggi)

# Sejarah CodeIgniter <br>
CodeIgniter awalnya dikembangkan oleh **EllisLab**. Selama bertahun-tahun, dikembangkan dan dikelola oleh **EllisLab**, Tim Pengembangan Expression Engine, dan sekelompok anggota komunitas yang disebut Tim Reaktor. Pada tahun 2014, CodeIgniter diakuisisi oleh Institut Teknologi British Columbia dan kemudian secara resmi diumumkan sebagai project yang dikelola komunitas. Pada tahun 2019, CodeIgniter Foundation dibentuk untuk menyediakan grup pengelola abadi yang terpisah dari entitas lain untuk membantu memastikan masa depan framework tersebut.

# 2. Instalansi CodeIgniter <br>
CodeIgniter memiliki dua metode instalasi yang didukung: download manual, atau menggunakan Composer. <br>
Berikut dengan instal CI menggunakan Composer : 
1. Pastikan Anda susdah mengisntal composer. <br>
![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/22e0fc3f-7fb6-45ac-93bb-d1110c638277)

2. Masukkan perintah download CI4. <br>
![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/a498bdf0-9dc5-4a7e-b8a9-9ac9288aa724)

3. Masukkan perintah cd nama file, masukkan php spark serve untuk menjalankan server. <br>
![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/17bcf074-a62f-40cb-bba4-a52c7e2f288e)

4. CI4 sudah terinstal. <br>
![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/884a829c-453e-4d40-9ed6-d9723736927f)

5. CI4 sudah bisa diakses. <br>
![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/309fe299-943e-48c9-94ed-f5be11ebdade)

# 3. Bangun Aplikasi Pertama <br>
# Menetapkan Aturan Perutean <br>
Perutean mengaitkan URI dengan metode pengontrol. Pengontrol hanyalah sebuah kelas yang membantu mendelegasikan pekerjaan. Kami akan membuat pengontrol nanti. Mari kita siapkan aturan perutean. Buka file rute yang terletak di app/Config/Routes.php. <br>
<?php

use CodeIgniter\Router\RouteCollection;

/**
 * @var RouteCollection $routes
 */
$routes->get('/', 'Home::index'); 











