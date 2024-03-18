# Pemograman Berbasis Framework
# Nama : Irma Yuliyanti
# NIM  : 220202086
# Kelas : TI-2D

**Apa yang dimaksud dengan Framework?**
Framework adalah sebuah abstraksi pembuatan perangkat lunak dimana didalamnya menyediakan fungsi-fungsi umum yang dapat digunakan. Framework memiliki software yang terdiri dari kerangka kerja (yang didalamnya menyediakan standar & aturan pembuatan perangkat lunak sesuai dengan bahasanya), reusability (fungsi-fungsi yang dapat digunakan secara berulang), framework juga bisa berisi program, compiler, library, tool, sets, api, komponen, dll (digunakan untuk mempermudah perangkat lunak), semua bahasa pemogramam populer memliki framework.

**Alasan menggunakan Framework:**
1.	Mempersingkat waktu pengembangan.
2.	Memiliki struktur aplikasi yang terorganisir.
3.	Memiliki tools & libraries yang bisa digunakan.
4.	Fleksibilitas (dapat dengan mudah terkoneksi dengan database yang berbeda, bisa menggunakan aplikasi pihak ke-3, dll).
5.	Memiliki fitur security.
6.	Teamwork (mempermudah pekerjaan saat bekerja secara tim).

**Kekurangan dari Framework:**
1.	Eksekusi yang lebih lambat.
2.	Butuh waktu belajar.
3.	Solusi umum untuk menyelesaikan masalah yang spesifik.
4.	Keterbatasan kendali.
5.	Masalah dependency (yaitu masalah pada setiap framework yang dibuat dengan menggunakan banyak komponen yang diambil dari orang lain sehingga saling terkait/bergantung satu sama lain).

**Apa yang dimaksud dengan CodeIgniter?**
CodeIgniter adalah akerangka pengembangan aplikasi atau sebuah toolkit untuk membangun situs web menggunakan bahasa PHP. Tujuannya adalah untuk memungkinkan mengembangkan project jauh lebih cepat daripada kita menulis kode dari awal, dengan menyediakan kumpulan library yang kaya untuk tugas-tugas umum, serta antarmuka sederhana, dan struktur logis untuk mengakses library ini.

**Sejarah CodeIgniter**
CodeIgniter awalnya dikembangkan oleh **EllisLab**. Selama bertahun-tahun, dikembangkan dan dikelola oleh **EllisLab**, Tim Pengembangan Expression Engine, dan sekelompok anggota komunitas yang disebut Tim Reaktor. Pada tahun 2014, CodeIgniter diakuisisi oleh Institut Teknologi British Columbia dan kemudian secara resmi diumumkan sebagai project yang dikelola komunitas. Pada tahun 2019, CodeIgniter Foundation dibentuk untuk menyediakan grup pengelola abadi yang terpisah dari entitas lain untuk membantu memastikan masa depan framework tersebut.

**Alasan mengapa menggunakan CodeIgniter:**
1.	Small footprint (framework yang kecil ukurannya tidak sampai lebih dari 10 mega).
2.	Memiliki peforma yang baik.
3.	Memiliki framework yang hampir tidak memerlukan konfigurasi (zero configuration).
4.	Tidak mengharuskan kita menggunakan baris perintah (command line).
5.	Tidak mengharuskan kita mematuhi aturan coding yang ketat.
6.	Tidak tertarik dengan library monolitik berskala besar seperti PEAR.
7.	Tidak ingin dipaksa untuk mempelajari bahasa templating (templating engine) (meskipun parser templat tersedia secara opsional jika kita menginginkannya).
8.	Menghindari kerumitan, lebih memilih solusi sederhana.
9.	Memiliki dokumentasi yang jelas dan menyeluruh.
10.	Menggunakan pattern MVC(Model-View-Controller)
    MVC adalah sebuah pola arsitektur pada perancangan perangkat lunak berorientasi objek yang memsisahkan antara tampilan, data, dan proses.
   	
**Basis Data yang Didukung***
Basis data diperlukan untuk sebagian besar pemrograman aplikasi web. Basis data yang didukung saat ini adalah:
1. MySQL melalui MySQLidriver (hanya versi 5.1 ke atas)
2. PostgreSQL melalui Postgredriver (hanya versi 7.4 dan lebih tinggi)
3. SQLite3 melalui SQLite3driver
4. Microsoft SQL Server melalui SQLSRVdriver (hanya versi 2005 dan lebih tinggi)
5. Oracle Database melalui OCI8driver (hanya versi 12.1 dan lebih tinggi)

**Instalasi CodeIgniter**
CodeIgniter memiliki dua metode instalasi yang didukung: download manual, atau menggunakan Composer.
**Menggunakan Composer:**
Microsoft Windows [Version 10.0.22621.3155]
(c) Microsoft Corporation. All rights reserved.

C:\Users\ACER>composer create-project codeigniter4/appstarter myCI4app

PS C:\Users\ACER> cd myCI4app
PS C:\Users\ACER\myCI4app> php spark serve

CodeIgniter v4.4.6 Command Line Tool - Server Time: 2024-03-18 02:02:33 UTC+00:00

CodeIgniter development server started on http://localhost:8080







