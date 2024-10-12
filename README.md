# Sekilas Tentang
FlatPress adalah sistem manajemen konten (CMS) blog gratis berbasis file yang ringan dan sederhana, hanya menggunakan PHP tanpa memerlukan database. Diluncurkan sejak 2006, FlatPress telah teruji dengan baik dan menawarkan kemudahan dalam pengaturan, pencadangan, dan penyesuaian dengan dukungan tema berbasis Smarty disertai sistem plugin.

# Instalasi
## Kebutuhan Sistem

- A web server that supports PHP 7.1–8.3
- The PHP intl extension
- A rewrite engine (mod_rewrite) untuk PrettyURLs plugin
- GDlib untuk membuat image thumbnails

## Proses instalasi : 
1. Kunjungi github FlatPress lalu cari link untuk download
![](./images/1.png)
2. Download file zip yang disediakan di website resmi FlatPress
![](./images/2.png)
3. Kunjungi rumahweb dan beli paket hosting serta domain
![](./images/3.png)
4. Login panel dan masukkan file zip serta extract di folder public_html
![](./images/4.png)
5. Buat database untuk website yang akan di hosting
![](./images/5.png)
6. Buat user dan pastikan seluruh privileged dimiliki oleh user tersebut, jadikan admin dari database yang sudah dibuat sebelumnya
![](./images/6.png)
7. Kunjungi domain yang telah dibuat dan ikuti langkah setup pada FlatPress
![](./images/7.png)
8. FlatPress sudah dapat diakses menggunakan domain yang sudah dibuat
![](./images/8.png)

# Konfigurasi
- Admin dapat melakukan konfigurasi dalam lingkup general (admin, blog, dan website)
![](./images/k1.png)
- Admin dapat melakukan konfigurasi dalam lingkup internasional (waktu, bahasa, dan karakter)
![](./images/k2.png)
- Admin dapat melakukan konfigurasi widgets atau susunan tampilan website
![](./images/k3.png)
- Admin dapat melakukan konfigurasi plugin untuk mendukung penggunaan FlatPress
![](./images/k4.png)
- Admin dapat melakukan konfigurasi tema pada tampilan utama FlatPress
![](./images/k5.png)

# Maintenance
- Admin dapat membangun ulang index website
![](./images/m1.png)
- Admin dapat membersihkan cache template dan tema
![](./images/m2.png)
- Admin dapat melakukan restore pada file permissions
![](./images/m3.png)
- Admin dapat mengecek informasi terkait PHP yang digunakan untuk memastikan apabila terjadi kesalahan teknis maupun hal lainnya
![](./images/m4.png)
- Admin dapat melakukan update pada website dan meluncurkan pengumuman bahwasanya telah dilakukan update pada website
![](./images/m5.png)

# Cara Pemakaian
- Setelah menuju alamat web, kita akan melihat tampilan halaman utama yang memuat informasi mengenai postingan blog yang tersedia 
![](./images/p1.png)
- Kita juga dapat melihat komentar-komentar yang ditinggalkan pengguna lain, atau menambahkan komentar baru sebagai user
![](./images/p2.png)
![](./images/p3.png)
- Login untuk admin
![](./images/p4.png)
- Setelah melakukan login admin, kita akan masuk ke halaman utama Admin Area. Di sini kita dapat mengelola/menggunakan berbagai fitur yang tersedia
![](./images/p5.png)
- Berikut adalah halaman “Entries” admin, admin dapat melihat dan mengedit postingan-postingan blog yang sudah diunggah
![](./images/p6.png)
- Admin dapat mengunggah postingan ke dalam blog untuk ditampilkan kepada publik
![](./images/p7.png)
- Berikut adalah tampilan halaman “Uploader”, di sini admin dapat mengunggah beberapa file (seperti png atau pdf) untuk disimpan ke dalam Media Manager (tidak ditampilkan secara publik)
![](./images/p8.png)
- Tampilan Media Manager
![](./images/p9.png)
- Berikut adalah tampilan utama website blog sebagai admin, kita dapat melakukan edit/delete pada postingan secara langsung
![](./images/p10.png)
- Admin juga dapat menambahkan komentar untuk postingan
![](./images/p11.png)
- Selain menu-menu yang berhubungan dengan fungsi utama website sebagai media blogging, FlatPress juga menyediakan menu untuk meningkatkan performa website, seperti menu untuk mengelola widgets, menu untuk mengelola plugin, menu untuk mengubah tampilan/tema website, serta menu untuk melakukan konfigurasi website
![](./images/p12.png)

# Pembahasan
FlatPress merupakan platform blogging berbasis flat-file yang memiliki beberapa kelebihan dan kekurangan. Kelebihannya meliputi kesederhanaan instalasi, hanya membutuhkan satu langkah, serta penggunaan BBCode yang memudahkan penulisan markup di atas HTML mentah. Desain tema bawaannya cukup modern dan responsif untuk perangkat seluler. Selain itu, fitur unggahan gambar lengkap dengan galeri dan lightbox sehingga membuat pengelolaan media visual menjadi mudah. Terdapat plugin seperti captcha dan Akismet untuk moderasi komentar. Dokumentasinya pun cukup baik untuk pengguna maupun pengembang, serta dukungan komunitas yang aktif. Kecepatan aplikasi dan kompatibilitasnya dengan PHP 5.6 hingga 7.4 pada berbagai server web juga menjadi nilai tambah.

Namun, kekurangan FlatPress terletak pada keamanan yang agak longgar menurut standar modern, seperti perlunya membatasi akses manual ke folder tertentu, serta keterbatasan dalam pengelolaan username dan password dari panel kontrol. Sistem penambahan fitur seperti tag yang hanya bisa diakses melalui plugin tambahan juga bisa dianggap sebagai kekurangan dibandingkan dengan platform serupa.

Jika dibandingkan dengan platform flat-file lain seperti Grav atau PicoCMS, FlatPress lebih sederhana dalam hal fitur dan fleksibilitas. Sedangkan Grav menawarkan lebih banyak kemampuan kustomisasi dan tema yang lebih variatif, serta memiliki keamanan yang lebih baik. Selain itu, PicoCMS juga lebih ringan dan bahkan lebih sederhana, tetapi mungkin kurang intuitif bagi pengguna yang baru mengenal flat-file CMS. FlatPress unggul dalam kemudahan penggunaan dan dukungan komunitas, tetapi bisa dianggap kurang lengkap bagi pengguna yang mencari fitur canggih dan keamanan yang lebih kuat.

# Referensi
- https://www.flatpress.org/
- https://wiki.flatpress.org/doc:techfaq#what_is_required_to_run_flatpress
- https://felix.plesoianu.ro/blog/flatpress-review.html
- https://picocms.org/about/
- https://getgrav.org/about
