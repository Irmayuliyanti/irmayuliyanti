## Pemograman Berbasis Framework
Nama       : IRMA YULIYANTI <br>
NIM        : 220202086 <br>
Kelas      : TI-2D <br>

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
# Halaman Statis <br>
# A. Menetapkan Aturan Perutean <br>
Perutean mengaitkan URI dengan metode pengontrol untuk membantu pekerjaan. Buka file rute yang terletak di app/Config/Routes.php. Berikut kodenya: <br>
```
<?php

use CodeIgniter\Router\RouteCollection;

/**
 * @var RouteCollection $routes
 */
$routes->get('/', 'Home::index');
```

Arahan ini mengatakan bahwa setiap permintaan masuk tanpa konten apa pun yang ditentukan harus ditangani oleh index()metode di dalam Homepengontrol. Tambahkan baris berikut, setelah arahan rute untuk '/'. <br>

```
use App\Controllers\Pages;

$routes->get('pages', [Pages::class, 'index']);
$routes->get('(:segment)', [Pages::class, 'view']);
```

CodeIgniter membaca aturan routingnya dari atas ke bawah dan merutekan permintaan ke aturan pertama yang cocok. Setiap aturan adalah ekspresi reguler (sisi kiri) yang dipetakan ke pengontrol dan nama metode (sisi kanan). Ketika sebuah permintaan masuk, CodeIgniter mencari kecocokan pertama, dan memanggil pengontrol dan metode yang sesuai, mungkin dengan argumen. <br>

# Ayo Buat Pengendali Pertama kita <br>
# B. Buat Pengontrol Halaman <br>
Buat file di app/Controllers/Pages.php dengan kode berikut. <br>
```
<?php

namespace App\Controllers;

class Pages extends BaseController
{
    public function index()
    {
        return view('welcome_message');
    }

    public function view($page = 'home')
    {
        // ...
    }
}
```

Dengan view()metode yang menerima satu argumen bernama $page. Ia juga memiliki index()metode, sama dengan pengontrol default yang ditemukan di app/Controllers/Home.php ; metode itu menampilkan halaman selamat datang CodeIgniter. Kelas Pages memperluas BaseControllerkelas yang memperluas CodeIgniter\Controllerkelas berarti kelas Pages baru dapat mengakses metode dan properti yang ditentukan dalam CodeIgniter\Controllerkelas ( system/Controller.php ) yang akan menjadi pusat dari setiap permintaan pada aplikasi web. Seperti kelas PHP lainnya, Anda menyebutnya di dalam pengontrol Anda sebagai $this. <br>

# C. Buat Tampilan <br>
Buat header di app/Views/templates/header.php dan tambahkan kode berikut: <br>
```
<!doctype html>
<html>
<head>
    <title>CodeIgniter Tutorial</title>
</head>
<body>

    <h1><?= esc($title) ?></h1>
```

Header berisi kode HTML dasar yang ingin Anda tampilkan sebelum memuat tampilan utama, bersama dengan judul. Ini juga akan menampilkan $titlevariabel, yang akan kita definisikan nanti di pengontrol. Sekarang, buat footer di app/Views/templates/footer.php yang menyertakan kode berikut: <br>
```
    <em>&copy; 2022</em>
</body>
</html>
```

# Menambahkan Logika ke Controller <br>
# D. Buat home.php dan about.php <br>
Sebelumnya Anda menyiapkan pengontrol dengan suatu view()metode. Metode ini menerima satu parameter, yaitu nama halaman yang akan dimuat. Badan halaman statis akan ditempatkan di direktori app/Views/pages. Di direktori itu, buat dua file bernama home.php dan about.php . Di dalam file tersebut, ketikkan beberapa teks - apa pun yang Anda suka - dan simpan. Jika Anda ingin tampil tidak orisinal, cobalah “Hello World!”.

# E. Halaman Lengkap::view() Metode
Untuk memuat halaman tersebut, Anda harus memeriksa apakah halaman yang diminta benar-benar ada. Ini akan menjadi isi metode view()pada Pagespengontrol yang dibuat di atas: <br>
```
<?php

namespace App\Controllers;

use CodeIgniter\Exceptions\PageNotFoundException; // Add this line

class Pages extends BaseController
{
    // ...

    public function view($page = 'home')
    {
        if (! is_file(APPPATH . 'Views/pages/' . $page . '.php')) {
            // Whoops, we don't have a page for that!
            throw new PageNotFoundException($page);
        }

        $data['title'] = ucfirst($page); // Capitalize the first letter

        return view('templates/header', $data)
            . view('pages/' . $page)
            . view('templates/footer');
    }
}
```

Dan tambahkan setelah baris untuk mengimpor kelas.use CodeIgniter\Exceptions\PageNotFoundException;namespacePageNotFoundException. <br>
Sekarang, ketika halaman yang diminta memang ada, halaman tersebut dimuat, termasuk header dan footer, dan dikembalikan ke pengguna. Jika pengontrol mengembalikan string, string tersebut akan ditampilkan kepada pengguna. <br>

# F. Menjalankan Aplikasi <br>
Anda tidak dapat menjalankan aplikasi menggunakan server bawaan PHP, karena aplikasi tersebut tidak akan memproses aturan .htaccess yang disediakan di public dengan benar, sehingga menghilangkan kebutuhan untuk menentukan “ index.php/ ” sebagai bagian dari URL. CodeIgniter memiliki perintahnya, di root proyek Anda:
```
php spark serve
```

Kode artinya akan memulai server web, dapat diakses pada port 8080. Jika Anda mengatur field lokasi di browser Anda ke localhost:8080.Anda akan melihat sesuatu seperti berikut: <br>
<img width="960" alt="image" src="https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/ae6ac170-420e-41d2-b572-918f8a516f36">

# Bagian Berita <br>
# A. Buat Database untuk Digunakan <br>
Anda perlu membuat database ci4tutorialyang dapat digunakan untuk tutorial ini, dan kemudian mengkonfigurasi CodeIgniter untuk menggunakannya. <br>
Menggunakan klien database Anda, sambungkan ke database Anda dan jalankan perintah SQL di bawah ini (MySQL): <br>
```
CREATE TABLE news (
    id INT UNSIGNED NOT NULL AUTO_INCREMENT,
    title VARCHAR(128) NOT NULL,
    slug VARCHAR(128) NOT NULL,
    body TEXT NOT NULL,
    PRIMARY KEY (id),
    UNIQUE slug (slug)
);
```

Juga, tambahkan beberapa catatan benih. Catatan benih mungkin seperti: <br>
```
INSERT INTO news VALUES
(1,'Elvis sighted','elvis-sighted','Elvis was sighted at the Podunk internet cafe. It looked like he was writing a CodeIgniter app.'),
(2,'Say it isn\'t so!','say-it-isnt-so','Scientists conclude that some programmers have a sense of humor.'),
(3,'Caffeination, Yes!','caffeination-yes','World\'s largest coffee shop open onsite nested coffee shop for staff only.');
```

# B. Hubungkan ke Basis Data Anda <br>
File konfigurasi lokal, .env , yang Anda buat saat menginstal CodeIgniter, harus memiliki pengaturan properti database yang tidak diberi komentar dan disetel dengan tepat untuk database yang ingin Anda gunakan. Pastikan Anda telah mengkonfigurasi database Anda dengan benar seperti yang dijelaskan dalam Konfigurasi Database: <br>
```
database.default.hostname = localhost
database.default.database = ci4tutorial
database.default.username = root
database.default.password = root
database.default.DBDriver = MySQLi
```

# Menyiapkan Model Anda <br>
Daripada menulis operasi database langsung di pengontrol, kueri harus ditempatkan dalam model, sehingga dapat digunakan kembali dengan mudah nanti. Model adalah tempat Anda mengambil, menyisipkan, dan memperbarui informasi dalam database atau penyimpanan data lainnya. Mereka menyediakan akses ke data Anda. Anda dapat membaca lebih lanjut tentang hal ini di Menggunakan Model CodeIgniter. <br>

# C. Buat Model Berita
Buka direktori app/Models dan buat file baru bernama NewsModel.php dan tambahkan kode berikut. <br>
```
<?php

namespace App\Models;

use CodeIgniter\Model;

class NewsModel extends Model
{
    protected $table = 'news';
}
```

Kode ini terlihat mirip dengan kode pengontrol yang digunakan sebelumnya. Ini menciptakan model baru dengan memperluas CodeIgniter\Modeldan memuat perpustakaan database. Ini akan membuat kelas database tersedia melalui $this->db objek. <br>

# Tambahkan Metode NewsModel::getNews() <br>
Tambahkan kode berikut ke model Anda. <br>
Tambahkan kode berikut ke model Anda.
```
    public function getNews($slug = false)
    {
        if ($slug === false) {
            return $this->findAll();
        }

        return $this->where(['slug' => $slug])->first();
    }
```

Dengan kode ini dapat melakukan dua kueri berbeda, bisa mendapatkan semua catatan berita, atau mendapatkan item berita melalui siputnya. <br>

# Tampilkan Berita <br>
Model harus dikaitkan dengan tampilan yang akan menampilkan item berita kepada pengguna. Ini bisa dilakukan di Pagespengontrol yang kami buat sebelumnya, tetapi demi kejelasan, Newspengontrol baru telah ditentukan. <br>
# D. Menambahkan Aturan Perutean <br>
Ubah file app/Config/Routes.php Anda , sehingga terlihat seperti berikut: <br>
```
<?php

// ...

use App\Controllers\News; // Add this line
use App\Controllers\Pages;

$routes->get('news', [News::class, 'index']);           // Add this line
$routes->get('news/(:segment)', [News::class, 'show']); // Add this line

$routes->get('pages', [Pages::class, 'index']);
$routes->get('(:segment)', [Pages::class, 'view']);
```

Hal ini memastikan permintaan mencapai Newspengontrol alih-alih langsung ke Pagespengontrol. Baris kedua $routes->get()merutekan URI dengan slug ke show()metode di Newspengontrol. <br>

# E. Buat Pengontrol Berita <br>
Buat pengontrol baru di app/Controllers/News.php. <br>
```
<?php

namespace App\Controllers;

use App\Models\NewsModel;

class News extends BaseController
{
    public function index()
    {
        $model = model(NewsModel::class);

        $data['news'] = $model->getNews();
    }

    public function show($slug = null)
    {
        $model = model(NewsModel::class);

        $data['news'] = $model->getNews($slug);
    }
}
```

# F. Berita Lengkap::index() Metode
Sekarang data diambil oleh pengontrol melalui model kami, tetapi belum ada yang ditampilkan. Hal berikutnya yang harus dilakukan adalah meneruskan data ini ke tampilan. Ubah index()metodenya menjadi seperti ini: <br>
```
<?php

namespace App\Controllers;

use App\Models\NewsModel;

class News extends BaseController
{
    public function index()
    {
        $model = model(NewsModel::class);

        $data = [
            'news'  => $model->getNews(),
            'title' => 'News archive',
        ];

        return view('templates/header', $data)
            . view('news/index')
            . view('templates/footer');
    }

    // ...
}
```

Kode di atas mengambil semua catatan berita dari model dan menugaskannya ke variabel. Nilai judul juga ditetapkan ke $data['title'] elemen dan semua data diteruskan ke tampilan. Anda sekarang perlu membuat tampilan untuk merender item berita. <br>

# G. Buat File Tampilan berita/indeks <br>
Buat app/Views/news/index.php dan tambahkan potongan kode berikutnya.<br>
```

<h2><?= esc($title) ?></h2>

<?php if (! empty($news) && is_array($news)): ?>

    <?php foreach ($news as $news_item): ?>

        <h3><?= esc($news_item['title']) ?></h3>

        <div class="main">
            <?= esc($news_item['body']) ?>
        </div>
        <p><a href="/news/<?= esc($news_item['slug'], 'url') ?>">View article</a></p>

    <?php endforeach ?>

<?php else: ?>

    <h3>No News</h3>

    <p>Unable to find any news for you.</p>

<?php endif ?>
```

# H. Berita Lengkap::show() Metode <br>
Model yang dibuat sebelumnya dibuat sedemikian rupa sehingga dapat dengan mudah digunakan untuk fungsi ini. Anda hanya perlu menambahkan beberapa kode ke controller dan membuat tampilan baru. Kembali ke Newspengontrol dan perbarui show()metode dengan yang berikut: <br>
```
<?php

namespace App\Controllers;

use App\Models\NewsModel;
use CodeIgniter\Exceptions\PageNotFoundException;

class News extends BaseController
{
    // ...

    public function show($slug = null)
    {
        $model = model(NewsModel::class);

        $data['news'] = $model->getNews($slug);

        if (empty($data['news'])) {
            throw new PageNotFoundException('Cannot find the news item: ' . $slug);
        }

        $data['title'] = $data['news']['title'];

        return view('templates/header', $data)
            . view('news/view')
            . view('templates/footer');
    }
}
```

# I. Buat berita/lihat Lihat File <br>
Satu-satunya hal yang perlu dilakukan adalah membuat tampilan terkait di app/Views/news/view.php . Letakkan kode berikut di file ini. <br>
```
<h2><?= esc($news['title']) ?></h2>
<p><?= esc($news['body']) ?></p>
```

Arahkan browser Anda ke halaman “berita”, yaitu localhost:8080/news. <br>
![image](https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/012d0396-cad9-40b4-9674-c343133c22ec)

# Buat Item Berita <br>
# A. Aktifkan Filter CSRF <br>
Sebelum membuat formulir, aktifkan perlindungan CSRF. Buka file app/Config/Filters.php dan perbarui $methodsproperti seperti berikut: <br>
```
<?php

namespace Config;

use CodeIgniter\Config\BaseConfig;

class Filters extends BaseConfig
{
    // ...

    public $methods = [
        'post' => ['csrf'],
    ];

    // ...
}
```

Ini mengkonfigurasi filter CSRF untuk diaktifkan untuk semua permintaan POST . Anda dapat membaca lebih lanjut tentang perlindungan CSRF di perpustakaan Keamanan.<br>

# B. Menambahkan Aturan Perutean <br>
Sebelum mulai menambahkan item berita ke dalam aplikasi CodeIgniter harus menambahkan aturan tambahan ke file app/Config/Routes.php. Pastikan file berisi yang berikut ini: <br>
```
<?php

// ...

use App\Controllers\News;
use App\Controllers\Pages;

$routes->get('news', [News::class, 'index']);
$routes->get('news/new', [News::class, 'new']); // Add this line
$routes->post('news', [News::class, 'create']); // Add this line
$routes->get('news/(:segment)', [News::class, 'show']);

$routes->get('pages', [Pages::class, 'index']);
$routes->get('(:segment)', [Pages::class, 'view']);
```

Untuk 'news/(:segment)'memastikan bahwa formulir untuk membuat item berita ditampilkan. Baris ini $routes->post()mendefinisikan router untuk permintaan POST. <br>

# Buat Formulir<br>
# C. Buat berita/buat Lihat File <br>
Untuk memasukkan data ke dalam database perlu membuat formulir yang dapat memasukkan informasi yang akan disimpan. Buat tampilan baru di app/Views/news/create.php: <br>
```
<h2><?= esc($title) ?></h2>

<?= session()->getFlashdata('error') ?>
<?= validation_list_errors() ?>

<form action="/news" method="post">
    <?= csrf_field() ?>

    <label for="title">Title</label>
    <input type="input" name="title" value="<?= set_value('title') ?>">
    <br>

    <label for="body">Text</label>
    <textarea name="body" cols="45" rows="4"><?= set_value('body') ?></textarea>
    <br>

    <input type="submit" name="submit" value="Create news item">
</form>
```

Fungsi ini session() digunakan untuk mendapatkan objek Sesi, dan session()->getFlashdata('error') digunakan untuk menampilkan kesalahan terkait perlindungan CSRF kepada pengguna. <br>
Fungsi validation_list_errors() yang disediakan oleh Form Helper digunakan untuk melaporkan kesalahan terkait validasi form. <br>
Fungsi ini csrf_field() membuat masukan tersembunyi dengan token CSRF yang membantu melindungi dari beberapa serangan umum. <br>
Fungsi set_value() yang disediakan oleh Form Helper digunakan untuk menampilkan data masukan lama ketika terjadi kesalahan. <br>

# Pengendali Berita <br>
# D. Tambahkan Berita::baru() untuk Menampilkan Formulir <br>
Pertama, buatlah metode untuk menampilkan form HTML yang telah Anda buat. <br>
```
<?php

namespace App\Controllers;

use App\Models\NewsModel;
use CodeIgniter\Exceptions\PageNotFoundException;

class News extends BaseController
{
    // ...

    public function new()
    {
        helper('form');

        return view('templates/header', ['title' => 'Create a news item'])
            . view('news/create')
            . view('templates/footer');
    }
}
```

Kami memuat pembantu Formulir dengan fungsinya helper(). Sebagian besar fungsi pembantu memerlukan pembantu untuk dimuat sebelum digunakan.  <br>

# E. Tambahkan Berita::create() untuk Membuat Item Berita
Selanjutnya, buat metode untuk membuat item berita dari data yang dikirimkan. Anda akan melakukan tiga hal di sini:
1. memeriksa apakah data yang dikirimkan lolos aturan validasi.
2. menyimpan item berita ke database.
3. mengembalikan halaman sukses. <br>
Berikut kodenya: <br>
```
<?php

namespace App\Controllers;

use App\Models\NewsModel;
use CodeIgniter\Exceptions\PageNotFoundException;

class News extends BaseController
{
    // ...

    public function create()
    {
        helper('form');

        $data = $this->request->getPost(['title', 'body']);

        // Checks whether the submitted data passed the validation rules.
        if (! $this->validateData($data, [
            'title' => 'required|max_length[255]|min_length[3]',
            'body'  => 'required|max_length[5000]|min_length[10]',
        ])) {
            // The validation fails, so returns the form.
            return $this->new();
        }

        // Gets the validated data.
        $post = $this->validator->getValidated();

        $model = model(NewsModel::class);

        $model->save([
            'title' => $post['title'],
            'slug'  => url_title($post['title'], '-', true),
            'body'  => $post['body'],
        ]);

        return view('templates/header', ['title' => 'Create a news item'])
            . view('news/success')
            . view('templates/footer');
    }
}
```

Kode di atas menambahkan banyak fungsi.

# F. Kembalikan Halaman Sukses <br>
Setelah ini, file tampilan dimuat dan dikembalikan untuk menampilkan pesan sukses. Buat tampilan di app/Views/news/success.php dan tulis pesan sukses. Ini bisa sesederhana: <br>
```
<p>News item created successfully.</p>
```

# G. Pembaruan Model Berita <br>
Metode save() yang digunakan menentukan apakah informasi harus dimasukkan atau apakah baris sudah ada dan harus diperbarui, berdasarkan keberadaan kunci utama. Namun secara default metode insert dan update pada Model tidak akan benar-benar menyimpan data apapun karena tidak mengetahui field apa yang aman untuk diupdate. Edit NewsModel untuk memberikannya daftar bidang yang dapat diperbarui di $allowedFields properti, berikut kodenya: <br>
```
<?php

namespace App\Models;

use CodeIgniter\Model;

class NewsModel extends Model
{
    protected $table = 'news';

    protected $allowedFields = ['title', 'slug', 'body'];
}
```

Perhatikan bahwa kita mengabaikan id? Itu karena Anda hampir tidak perlu melakukan hal itu, karena bidang yang bertambah secara otomatis dalam database. Ini membantu melindungi dari Kerentanan Penugasan Massal. Jika model Anda menangani stempel waktu Anda, Anda juga akan mengabaikannya. <br>

# H. Buat Item Berita <br>
Sekarang arahkan browser Anda ke lingkungan pengembangan lokal tempat Anda menginstal CodeIgniter dan tambahkan /news/new ke URL. Tambahkan beberapa berita dan periksa halaman berbeda yang Anda buat. <br>
<img width="541" alt="image" src="https://github.com/Irmayuliyanti/irmayuliyanti/assets/134593991/2e213467-1390-4bfd-a81a-64d24da8ae76">











