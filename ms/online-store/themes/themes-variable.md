# Themes Variable

## Variables in Shoppego Themes

Ini adalah rujukan lengkap untuk semua pembolehubah yang boleh digunakan dalam pembangunan theme di Shoppego.

Senarai ini membantu developer faham data yang tersedia dalam sistem, cara panggil setiap variable, dan bila ia sesuai digunakan.

Rujukan ini sangat berguna bila nak bina theme custom, ubah layout template, atau nak tarik data dari kedai, produk, kategori, menu dan setting tema.

### On this page

1. [Filters](themes-variable.md#filters)
2. [Home structure variables](themes-variable.md#home-structure-variables)
3. [Product structure variables](themes-variable.md#product-structure-variables)
4. [Products structure variables](themes-variable.md#products-structure-variables)
5. [Cart structure variables](themes-variable.md#cart-structure-variables)
6. [Page structure variables](themes-variable.md#page-structure-variables)
7. [404 structure variables](themes-variable.md#id-404-structure-variables)
8. [Parameters](themes-variable.md#parameters)

### Filters

| Parameter                | Description                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------------ |
| product\_image\_size     | Memberikan URL gambar produk mengikut saiz yang ditetapkan (contoh: small, medium, large). |
| money                    | Memformat nombor kepada format mata wang kedai (contoh: RM120.00)                          |
| money\_without\_currency | Memformat nombor sebagai harga tanpa memaparkan simbol mata wang (contoh: 120.00)          |
| placeholder\_svg\_tag    | Menjana imej SVG sebagai placeholder (digunakan bila tiada gambar produk tersedia)         |
| truncate                 | Memendekkan teks biasa kepada jumlah aksara tertentu dan menambah … di hujungnya           |
| truncate\_html           | Sama seperti truncate tetapi mengekalkan tag HTML sambil memendekkan teks                  |
| json                     | Menukar nilai atau array kepada format string JSON                                         |
| json\_decode             | Menukar string JSON kembali kepada array/objek untuk digunakan dalam Twig                  |

#### Pembolehubah Struktur Home

Dalam struktur Home, cik boleh guna parameter daripada:

1. [Parameter Store](themes-variable.md#store-parameter)
2. [Parameter Am](themes-variable.md#general-parameter)
3. [Parameter Cart](themes-variable.md#cart-parameter)
4. [Parameter Settings](themes-variable.md#settings-parameter)
5. [Parameter Menus](themes-variable.md#menus-parameter)
6. [Parameter Page](themes-variable.md#page-parameter)
7. [Parameter Products](themes-variable.md#products-parameter)
8. [Parameter Categories](themes-variable.md#categories-parameter)

### Pembolehubah Struktur Product

Dalam struktur Produk, anda boleh gunakan parameter daripada:

1. [Parameter Store](themes-variable.md#store-parameter)
2. [Parameter Am](themes-variable.md#general-parameter)
3. [Parameter Cart](themes-variable.md#cart-parameter)
4. [Parameter Settings](themes-variable.md#settings-parameter)
5. [Parameter Menus](themes-variable.md#menus-parameter)
6. [Parameter Page](themes-variable.md#page-parameter)
7. [Parameter Products](themes-variable.md#products-parameter)
8. [Parameter Product](themes-variable.md#product-parameter)
9. [Parameter Product related](themes-variable.md#product-related-parameter)
10. [Parameter Product Wholesale](themes-variable.md#product-wholesale-parameter)
11. [Parameter Product Wholesale](themes-variable.md#product-bundle-parameter)
12. [Parameter Categories](themes-variable.md#categories-parameter)

### Pembolehubah Struktur Products

Dalam struktur Produk (Products), anda boleh guna parameter daripada:

1. [Parameter Store](themes-variable.md#store-parameter)
2. [Parameter Am](themes-variable.md#general-parameter)
3. [Parameter Cart](themes-variable.md#cart-parameter)
4. [Parameter Settings](themes-variable.md#settings-parameter)
5. [Parameter Menus](themes-variable.md#menus-parameter)
6. [Parameter Page](themes-variable.md#page-parameter)
7. [Parameter Products](themes-variable.md#products-parameter)
8. [Parameter Categories](themes-variable.md#categories-parameter)

### Pembolehubah Struktur Cart

Dalam struktur Cart, anda boleh guna parameter daripada:

1. [Parameter Store](themes-variable.md#store-parameter)
2. [Parameter Am](themes-variable.md#general-parameter)
3. [Parameter Cart](themes-variable.md#cart-parameter)
4. [Parameter Cart bundle products](themes-variable.md#parameter-cart-bundle-products)
5. [Parameter Settings](themes-variable.md#settings-parameter)
6. [Parameter Menus](themes-variable.md#menus-parameter)

### Pembolehubah Struktur Page

Dalam struktur Page, anda boleh guna parameter daripada:

1. [Parameter Store](themes-variable.md#store-parameter)
2. [Parameter Am](themes-variable.md#general-parameter)
3. [Parameter Cart](themes-variable.md#cart-parameter)
4. [Parameter Settings](themes-variable.md#settings-parameter)
5. [Parameter Menus](themes-variable.md#menus-parameter)
6. [Parameter Page](themes-variable.md#page-parameter)
7. [Parameter Page/{slug}](themes-variable.md#parameter-page-slug)

### Pembolehubah Struktur 404

Dalam struktur 404, anda boleh guna parameter daripada:

1. [Store parameter](themes-variable.md#store-parameter)
2. [Parameter Am](themes-variable.md#general-parameter)
3. [Parameter Cart](themes-variable.md#cart-parameter)
4. [Parameter Settings](themes-variable.md#settings-parameter)
5. [Parameter Menus](themes-variable.md#menus-parameter)
6. [Parameter Categories](themes-variable.md#categories-parameter)

### Parameter

#### Parameter Store

| Parameter                         | Penerangan                                                                                                                                                                |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| store.name                        | <p>Nama kedai yang dipaparkan.<br>Contoh: "My Boutique Store".</p>                                                                                                        |
| store.description                 | <p>Ringkasan pendek atau tagline untuk kedai anda.<br>Digunakan untuk SEO dan paparan metadata.<br>Contoh: "Kedai dipercayai untuk shawl dan skarf handmade."</p>         |
| store.currency\_format            | <p>Tetapan cara harga dipaparkan di seluruh kedai, termasuk posisi simbol mata wang.<br>Contoh: "$ {amount}" atau "{amount} MYR".</p>                                     |
| store.timezone                    | <p>Tetapan zon masa untuk paparan masa tempatan (contohnya pada pesanan atau laporan).<br>Contoh: "Asia/Kuala\_Lumpur".</p>                                               |
| store.checkout\_enabled           | <p>Menentukan sama ada proses checkout online diaktifkan atau tidak.<br>Jika false, pelanggan boleh lihat produk tetapi tidak boleh buat pembayaran.<br>Contoh: true.</p> |
| store.checkout\_minimum\_purchase | <p>Tetapan jumlah minimum pembelian sebelum pelanggan boleh checkout.<br>Contoh: 50 (bermaksud minimum RM50).</p>                                                         |
| store.category\_featured          | <p>Senarai ID atau slug kategori yang akan dipaparkan di bahagian “Featured Categories” di halaman utama.<br>Contoh: \["shawls", "hijabs", "accessories"].</p>            |
| store.currency.code               | <p>Kod mata wang ISO untuk kedai, digunakan untuk harga, pembayaran, dan format.<br>Contoh: "MYR" untuk Ringgit Malaysia atau "USD" untuk Dollar US.</p>                  |

#### Parameter Am

| Parameter   | Penerangan                                                                                                                                                                                                                          |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| css         | <p>Mengandungi senarai atau string CSS yang akan dimuatkan dalam template.<br>Contoh: \["/assets/css/theme.css", "/assets/css/custom.css"].</p>                                                                                     |
| js          | <p>Mengandungi senarai atau string fail JavaScript yang akan disertakan, biasanya sebelum tag .<br>Contoh: \["/assets/js/main.js"].</p>                                                                                             |
| head        | <p>HTML custom atau meta tags untuk disuntik ke dalam bahagian halaman.<br>Selalu digunakan untuk SEO, analitik, atau integrasi pihak ketiga.</p>                                                                                   |
| head\_tag   | Membenarkan penyuntikan tag tambahan secara dinamik — contohnya dari backend atau sistem plugin.                                                                                                                                    |
| body\_tag   | Membenarkan penyuntikan tag tambahan secara dinamik — contohnya dari backend atau sistem plugin.                                                                                                                                    |
| csrf\_token | <p>Token keselamatan untuk melindungi borang daripada serangan CSRF (Cross-Site Request Forgery).<br>Wajib dimasukkan dalam borang yang mengubah data.<br>Contoh:<br>\<input name="\_token" type="hidden" value="1asdfe27e..."></p> |
| customer    | <p>Menentukan sama ada pelanggan sedang log masuk atau tidak.<br>Jika false, bermaksud pelanggan belum log masuk ke laman anda.<br>Contoh: true.</p>                                                                                |
| title       | <p>Tajuk halaman semasa seperti yang dipaparkan pada tab pelayar dan tag.<br>Contoh: "New Arrivals – My Boutique Store".</p>                                                                                                        |
| description | <p>Penerangan ringkas atau meta description untuk halaman semasa.<br>Selalu digunakan untuk SEO dan paparan pratonton di media sosial.<br>Contoh: "Terokai koleksi shawl terbaru yang direka dengan penuh elegan."</p>              |

#### Parameter Cart

| Parameter                             | Penerangan                                                                                                                                                            |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| cart.items\[]                         | Senarai semua item dalam troli. Senarai penuh barang yang pelanggan dah masukkan ke dalam troli. Setiap item mewakili produk dengan variasi tertentu atau set bundle. |
| cart.items\[].id                      | ID unik untuk item dalam troli. ID ni digunakan kalau nak ubah kuantiti atau buang item dari troli.                                                                   |
| cart.items\[].is\_bundle              | Tunjuk sama ada item tu sebahagian daripada bundle produk atau produk tunggal.                                                                                        |
| cart.items\[].price                   | Harga untuk satu unit item selepas diskaun (kalau ada). Contoh: 49.90.                                                                                                |
| cart.items\[].compare\_at\_price      | Harga asal sebelum diskaun atau promosi. Contoh: 59.90. Biasanya digunakan untuk paparkan harga asal yang dipotong.                                                   |
| cart.items\[].total                   | Jumlah harga untuk item tu berdasarkan harga × kuantiti.                                                                                                              |
| cart.items\[].quantity                | Kuantiti produk yang pelanggan pilih dalam troli.                                                                                                                     |
| cart.items\[].options                 | Senarai pilihan produk yang dipilih seperti warna, saiz, atau variasi lain.                                                                                           |
| cart.items\[].options\[].id           | ID unik untuk setiap pilihan produk. Contoh: "opt\_32".                                                                                                               |
| cart.items\[].options\[].name         | Nama pilihan yang dipaparkan kepada pelanggan. Contoh: "Warna".                                                                                                       |
| cart.items\[].options\[].value        | Nilai pilihan yang dipilih pelanggan. Contoh: "Emerald Green".                                                                                                        |
| cart.items\[].product                 | Semua maklumat berkaitan produk untuk item tersebut dalam troli.                                                                                                      |
| cart.items\[].product.id              | ID unik produk tersebut.                                                                                                                                              |
| cart.items\[].product.name            | Nama produk. Contoh: "Elegant Satin Shawl".                                                                                                                           |
| cart.items\[].product.description     | Penerangan ringkas mengenai produk.                                                                                                                                   |
| cart.items\[].product.url             | Link ke halaman produk, supaya pelanggan boleh klik dan terus pergi ke page produk. Contoh: "/products/elegant-satin-shawl".                                          |
| cart.items\[].product.images          | Senarai link imej untuk produk tersebut.                                                                                                                              |
| cart.items\[].product.featured\_image | Imej utama untuk produk yang akan dipaparkan dalam troli.                                                                                                             |
| cart.items\[].product.available       | Menunjukkan sama ada produk dalam troli masih tersedia untuk dibeli (true jika ia masih ada stok dan boleh dibeli).                                                   |
| cart.item\_count                      | Jumlah keseluruhan item berdasarkan kuantiti. Contoh: kalau ada 2 untuk produk A dan 1 untuk produk B, jumlah = 2 item.                                               |
| cart.total\_price                     | Jumlah harga keseluruhan selepas pengiraan diskaun (kalau ada).                                                                                                       |
| cart.total\_compare\_at\_price        | Jumlah harga asal untuk semua barang sebelum diskaun. Sesuai untuk tunjuk jumlah penjimatan pelanggan.                                                                |
| cart.note                             | Nota tambahan daripada pelanggan, contohnya arahan penghantaran atau mesej hadiah.                                                                                    |

#### Parameter Cart Bundle Products

| Parameter                                                   | Penerangan                                                                             |
| ----------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| cart.items\[].bundle\_products\[]                           | Senarai produk yang termasuk dalam bundle di dalam item troli.                         |
| cart.items\[].bundle\_products\[].id                        | ID unik untuk produk bundle dalam troli.                                               |
| cart.items\[].bundle\_products\[].name                      | Nama produk yang termasuk dalam bundle.                                                |
| cart.items\[].bundle\_products\[].price                     | Harga jualan untuk produk bundle ini.                                                  |
| cart.items\[].bundle\_products\[].compare\_at\_price        | Harga asal atau harga lebih tinggi sebelum diskaun untuk produk bundle.                |
| cart.items\[].bundle\_products\[].total                     | Jumlah harga untuk produk bundle berdasarkan kuantiti (harga × kuantiti).              |
| cart.items\[].bundle\_products\[].total\_compare\_at\_price | Jumlah harga asal sebelum diskaun untuk produk bundle (compare\_at\_price × kuantiti). |
| cart.items\[].bundle\_products\[].options                   | Pilihan produk yang dipilih untuk produk bundle ini (contoh: warna, saiz).             |
| cart.items\[].bundle\_products\[].options.id                | ID unik bagi pilihan yang dipilih.                                                     |
| cart.items\[].bundle\_products\[].options.name              | Nama pilihan tersebut (contoh: "Warna", "Saiz").                                       |
| cart.items\[].bundle\_products\[].options.value             | Nilai pilihan yang dipilih (contoh: "Hitam", "M").                                     |
| cart.items\[].bundle\_products\[].quantity                  | Jumlah unit produk bundle ini yang dimasukkan dalam troli.                             |
| cart.items\[].bundle\_products\[].based\_quantity           | Kuantiti asas atau tetap bagi produk ini yang datang bersama bundle (jika ada).        |
| cart.items\[].bundle\_products\[].product                   | Maklumat produk terperinci untuk produk bundle ini.                                    |
| cart.items\[].bundle\_products\[].product.id                | ID unik produk tersebut.                                                               |
| cart.items\[].bundle\_products\[].product.name              | Nama produk.                                                                           |
| cart.items\[].bundle\_products\[].product.description       | Deskripsi ringkas produk.                                                              |
| cart.items\[].bundle\_products\[].product.url               | Pautan URL ke halaman produk.                                                          |
| cart.items\[].bundle\_products\[].product.images\[]         | Senarai semua gambar untuk produk ini.                                                 |
| cart.items\[].bundle\_products\[].product.featured\_image   | Gambar utama produk yang dipaparkan.                                                   |
| cart.items\[].bundle\_products\[].product.available         | Menunjukkan sama ada produk ini masih ada stok dan boleh dibeli atau tidak.            |

#### Parameter Settings

1. [Hartamas](themes-type/hartamas.md#variables)
2. [Solaris](themes-type/solaris.md#variables)
3. [Tampin](themes-type/tampin.md#variables)
4. [Bota](themes-type/bota.md#variables)

#### Parameter Menus

| Parameter                            | Penerangan                                                                                                                                                                             |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| menus                                | <p>Mengandungi semua menu navigasi yang dibuat untuk tema (contohnya: menu utama, menu footer, atau menu pautan sosial).<br>Setiap menu dikelaskan mengikut handle atau nama menu.</p> |
| menus."menu\_name".title             | <p>Tajuk paparan untuk menu tersebut.<br>Contoh: "Menu Utama" atau "Menu Footer".</p>                                                                                                  |
| menus."menu\_name".handle            | <p>Handle unik yang digunakan untuk merujuk menu ini dalam template.<br>Contoh: "main\_menu".</p>                                                                                      |
| menus."menu\_name".links\[]          | <p>Senarai semua pautan atau item menu di bawah menu tersebut.<br>Setiap item juga boleh mempunyai sub-pautan bersarang.</p>                                                           |
| menus."menu\_name".links\[].title    | <p>Label atau nama pautan menu yang dipaparkan kepada pengguna.<br>Contoh: "Home", "Shop", "Hubungi Kami".</p>                                                                         |
| menus."menu\_name".links\[].url      | <p>URL destinasi yang dituju oleh item menu.<br>Contoh: "/products", "/contact", atau pautan luar.</p>                                                                                 |
| menus."menu\_name".links\[].active   | <p>Menunjukkan sama ada pautan tersebut adalah halaman semasa yang sedang dilihat pengguna (true jika halaman itu sedang dibuka).<br>Digunakan untuk highlight menu “aktif”.</p>       |
| menus."menu\_name".links\[].links\[] | <p>Mengandungi sub-pautan atau item menu anak (dropdown).<br>Menggunakan struktur yang sama seperti links\[] — membolehkan navigasi bertingkat/multi-level.</p>                        |

#### Parameter Page

| Parameter      | Penerangan                                                                                                                                                                                          |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| page           | <p>Mengandungi maklumat tentang halaman yang sedang dipaparkan di website anda.<br>Digunakan untuk memaparkan halaman statik seperti “Tentang Kami”, “Dasar Privasi”, atau halaman custom lain.</p> |
| page.name      | <p>Nama paparan atau tajuk halaman tersebut.<br>Contoh: "Tentang Kami" atau "Terma & Syarat".</p>                                                                                                   |
| page.permalink | <p>Pengenal unik (slug) untuk halaman, biasanya digunakan dalam URL.<br>Contoh: "tentang-kami" atau "hubungi-kami".</p>                                                                             |
| page.url       | <p>Laluan URL penuh ke halaman.<br>Contoh: "/pages/tentang-kami".</p>                                                                                                                               |
| page.template  | <p>Fail template yang digunakan untuk memaparkan halaman ini.<br>Contoh: "page", "home"</p>                                                                                                         |

#### Parameter Page/{slug}

| Parameter                    | Description                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------- |
| page.id                      | Pengenalan unik untuk halaman tersebut.                                                                   |
| page.name                    | Nama dalaman atau “handle” untuk halaman (digunakan oleh sistem).                                         |
| page.image                   | Gambar utama (SEO image) yang dikaitkan dengan halaman, jika ada.                                         |
| page.permalink               | Slug atau pautan tetap (permalink) yang ditetapkan untuk halaman. Contoh: "about-us".                     |
| page.url                     | URL penuh untuk halaman tersebut. Contoh: "<https://namakedai.com/pages/about-us>".                       |
| page.template                | Fail template yang digunakan untuk paparkan halaman ini. Contoh: "page", "contact", atau template custom. |
| page.title                   | Tajuk paparan halaman, biasanya ditunjukkan di bahagian atas halaman dan pada tab pelayar.                |
| page.body                    | Kandungan utama halaman dalam format HTML.                                                                |
| page.metafields              | Medan data custom yang dilampirkan pada halaman (biasanya untuk fungsi lanjutan atau integrasi).          |
| page.metafields.builder      | Metafield khas yang digunakan oleh sistem pembina halaman visual.                                         |
| page.metafields.builder.json | Data JSON berstruktur yang dijana oleh page builder (mewakili susun atur & blok kandungan).               |
| page.metafields.builder.css  | CSS custom yang dijana oleh builder untuk halaman ini.                                                    |
| page.metafields.builder.js   | JavaScript custom yang dijana oleh builder untuk halaman ini.                                             |
| page.created\_at             | Tarikh dan masa halaman ini mula-mula dicipta.                                                            |
| page.updated\_at             | Tarikh dan masa halaman ini kali terakhir dikemas kini.                                                   |

#### Parameter Products

| Parameter                                           | Penerangan                                                                                                                                         |
| --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| products\[]                                         | Senarai semua produk yang dipaparkan pada halaman semasa (contohnya dalam template “Semua Produk” atau “Kedai”). Setiap item mewakili satu produk. |
| products\[].id                                      | ID unik untuk produk tersebut.                                                                                                                     |
| products\[].name                                    | Nama atau tajuk produk. Contoh: "Satin Premium Shawl".                                                                                             |
| products\[].description                             | Penerangan produk.                                                                                                                                 |
| products\[].price                                   | Harga asas produk (untuk produk yang ada satu varian sahaja).                                                                                      |
| products\[].compare\_at\_price\_min                 | Harga asal paling rendah (sebelum diskaun) dalam semua varian. Digunakan untuk paparan perbandingan diskaun.                                       |
| products\[].compare\_at\_price\_max                 | Harga asal paling tinggi (sebelum diskaun) dalam semua varian.                                                                                     |
| products\[].url                                     | URL penuh ke halaman produk. Contoh: "<https://namakedai.com/products/satin-premium-shawl>".                                                       |
| products\[].images\[]                               | Senarai link gambar untuk produk tersebut.                                                                                                         |
| products\[].is\_bundle                              | Tunjukkan jika produk adalah bundle (gabungan beberapa produk dijual sekali).                                                                      |
| products\[].featured\_image                         | Gambar utama atau default untuk produk.                                                                                                            |
| products\[].available                               | Sama ada produk masih ada stok dan boleh dibeli.                                                                                                   |
| products\[].price\_varies                           | Tunjuk jika produk ada banyak varian dengan harga yang berbeza.                                                                                    |
| products\[].selected\_or\_first\_available\_variant | Butiran varian yang sedang dipilih, atau ambil varian pertama yang tersedia.                                                                       |
| products\[].variants\[]                             | Senarai semua varian produk (contoh saiz, warna). Setiap varian ada harga, stok dan gambar sendiri.                                                |
| products\[].variants\[].id                          | ID unik untuk varian produk.                                                                                                                       |
| products\[].variants\[].name                        | Nama varian (biasanya gabungan pilihan). Contoh: "Dusty Pink / M".                                                                                 |
| products\[].variants\[].price                       | Harga jualan untuk varian tersebut.                                                                                                                |
| products\[].variants\[].compare\_at\_price          | Harga asal varian sebelum diskaun.                                                                                                                 |
| products\[].variants\[].available                   | Tunjuk jika varian ni boleh dibeli (ada stok).                                                                                                     |
| products\[].variants\[].inventory\_quantity         | Jumlah stok untuk varian tersebut.                                                                                                                 |
| products\[].variants\[].manage\_stock               | Tunjuk jika varian ini guna sistem kawal stok.                                                                                                     |
| products\[].variants\[].image                       | Gambar khas untuk varian tersebut.                                                                                                                 |
| products\[].variants\[].options                     | Gabungan nilai pilihan varian (contoh: "Warna": "Hitam", "Saiz": "M").                                                                             |
| products\[].metafields                              | Medan data khas untuk produk (digunakan untuk info tambahan atau integrasi).                                                                       |
| products\[].has\_options                            | Tunjuk jika produk ada pilihan yang boleh dipilih (contoh saiz, warna).                                                                            |
| products\[].reviews\[]                              | Senarai ulasan pengguna untuk produk.                                                                                                              |
| products\[].reviews\[].customer.name                | Nama pelanggan yang beri ulasan.                                                                                                                   |
| products\[].reviews\[].variant                      | Varian produk yang dipilih masa pelanggan tulis ulasan (contoh Saiz M, Hitam).                                                                     |
| products\[].reviews\[].description                  | Komen atau maklum balas bertulis daripada pelanggan.                                                                                               |
| products\[].reviews\[].rating                       | Rating yang diberikan pelanggan (contoh 1–5 bintang).                                                                                              |
| products\[].reviews\[].created\_at                  | Tarikh dan masa ulasan dihantar.                                                                                                                   |
| products\[].has\_only\_default\_variant             | Tunjuk jika produk hanya ada satu varian default (tiada pilihan).                                                                                  |
| products\[].has\_predefined\_options                | Tunjuk jika produk ada set pilihan yang telah ditetapkan.                                                                                          |
| products\[].options\[]                              | Senarai pilihan produk yang tersedia (contoh: saiz, warna).                                                                                        |
| products\[].options\[].id                           | ID unik untuk pilihan produk.                                                                                                                      |
| products\[].options\[].name                         | Nama pilihan. Contoh: "Saiz", "Warna".                                                                                                             |
| products\[].options\[].type                         | Jenis pilihan (contoh: dropdown, radio, swatch, date, datetime, input, textarea).                                                                  |
| products\[].options\[].required                     | Tentukan jika pilihan mesti dipilih sebelum tambah ke troli. Contoh: true.                                                                         |
| products\[].options\[].values\[]                    | Senarai semua nilai yang ada untuk pilihan tersebut. Contoh: "S", "M", "L".                                                                        |
| products\[].options\[].values\[].name               | Nama untuk setiap nilai pilihan. Contoh: "Emerald Green".                                                                                          |
| products\[].options\[].values\[].metadata           | Metadata tambahan untuk nilai pilihan.                                                                                                             |
| products\[].paginate                                | Mengandungi data pagination untuk senarai produk.                                                                                                  |
| products\[].paginate.next                           | URL untuk halaman seterusnya (jika ada).                                                                                                           |
| products\[].paginate.previous                       | URL untuk halaman sebelumnya (jika ada).                                                                                                           |
| products\[].q                                       | Query carian atau penapis yang digunakan pada paparan produk.                                                                                      |

#### Parameter Product

| Parameter                                          | Penerangan                                                                                                       |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| product\[]                                         | Senarai produk yang dipaparkan di halaman semasa.                                                                |
| product\[].id                                      | Pengecam unik bagi produk tersebut.                                                                              |
| product\[].name                                    | Nama atau tajuk produk. Contoh: "Satin Premium Shawl".                                                           |
| product\[].description                             | Deskripsi produk.                                                                                                |
| product\[].price                                   | Harga asas atau harga permulaan produk (untuk produk yang hanya ada satu variasi).                               |
| product\[].compare\_at\_price\_min                 | Harga asal paling rendah (sebelum diskaun) daripada semua variasi. Digunakan untuk paparan perbandingan diskaun. |
| product\[].compare\_at\_price\_max                 | Harga asal paling tinggi (sebelum diskaun) daripada semua variasi.                                               |
| product\[].url                                     | URL penuh ke halaman produk. Contoh: “<https://namakedai.com/products/satin-premium-shawl”>.                     |
| product\[].images\[]                               | Senarai semua URL gambar untuk produk tersebut.                                                                  |
| product\[].is\_bundle                              | Menunjukkan sama ada produk ini ialah bundle (gabungan beberapa produk dijual bersama).                          |
| product\[].featured\_image                         | Gambar utama atau default yang dipaparkan untuk produk.                                                          |
| product\[].available                               | Sama ada produk ini tersedia untuk pembelian (true kalau stok masih ada).                                        |
| product\[].price\_varies                           | Menunjukkan jika produk mempunyai banyak variasi dengan harga berbeza.                                           |
| product\[].selected\_or\_first\_available\_variant | Mengandungi maklumat mengenai variasi terpilih, atau variasi pertama yang tersedia jika tiada yang dipilih.      |
| product\[].variants\[]                             | Senarai semua variasi produk (contoh: saiz, warna). Setiap variasi ada harga, stok dan gambar tersendiri.        |
| product\[].variants\[].id                          | ID unik untuk variasi produk.                                                                                    |
| product\[].variants\[].name                        | Nama variasi (biasanya termasuk pilihan seperti warna/saiz). Contoh: “Dusty Pink / M”.                           |
| product\[].variants\[].price                       | Harga jualan semasa bagi variasi tersebut.                                                                       |
| product\[].variants\[].compare\_at\_price          | Harga asal variasi sebelum diskaun.                                                                              |
| product\[].variants\[].available                   | Menunjukkan sama ada variasi ini tersedia untuk dibeli.                                                          |
| product\[].variants\[].inventory\_quantity         | Jumlah stok semasa untuk variasi ini.                                                                            |
| product\[].variants\[].manage\_stock               | Menunjukkan sama ada tracking stok diaktifkan untuk variasi tersebut.                                            |
| product\[].variants\[].image                       | Gambar yang dikaitkan dengan variasi tersebut.                                                                   |
| product\[].variants\[].options                     | Gabungan nilai pilihan (contoh: “Warna”: “Hitam”, “Saiz”: “M”).                                                  |
| product\[].metafields                              | Maklumat tambahan atau metadata produk (digunakan untuk info tambahan).                                          |
| product\[].has\_options                            | Menunjukkan sama ada produk mempunyai pilihan boleh dipilih (contoh: saiz, warna).                               |
| product\[].reviews\[]                              | Senarai ulasan pelanggan untuk produk tersebut.                                                                  |
| product\[].reviews\[].customer.name                | Nama pelanggan yang memberi ulasan.                                                                              |
| product\[].reviews\[].variant                      | Variasi produk yang dipilih sewaktu pelanggan tinggalkan ulasan (contoh: Saiz M, Warna Hitam).                   |
| product\[].reviews\[].description                  | Maklum balas atau komen bertulis daripada pelanggan mengenai produk.                                             |
| product\[].reviews\[].rating                       | Penilaian atau rating yang diberi pelanggan (contoh: 1–5 bintang).                                               |
| product\[].reviews\[].created\_at                  | Tarikh dan masa ulasan dihantar.                                                                                 |
| product\[].has\_only\_default\_variant             | Menunjukkan jika produk hanya ada satu variasi default (tiada pilihan lain).                                     |
| product\[].has\_predefined\_options                | Menunjukkan jika produk mempunyai set pilihan yang telah ditetapkan.                                             |
| product\[].options\[]                              | Senarai semua pilihan produk yang tersedia (contoh: saiz, warna).                                                |
| product\[].options\[].id                           | ID unik untuk pilihan produk.                                                                                    |
| product\[].options\[].name                         | Nama pilihan. Contoh: “Saiz”, “Warna”.                                                                           |
| product\[].options\[].type                         | Jenis pemilih pilihan (contoh: dropdown, radio, swatch, date, datetime, input, textarea).                        |
| product\[].options\[].required                     | Sama ada pilihan ini wajib dipilih sebelum tambah ke troli. Contoh: true.                                        |
| product\[].options\[].values\[]                    | Senarai nilai pilihan yang tersedia. Contoh: “S”, “M”, “L”.                                                      |
| product\[].options\[].values\[].name               | Nama bagi nilai pilihan tersebut. Contoh: “Emerald Green”.                                                       |
| product\[].options\[].values\[].metadata           | Metadata tambahan untuk nilai pilihan.                                                                           |
| product\[].categories\[]                           | Senarai kategori produk.                                                                                         |
| product\[].categories\[].id                        | ID unik kategori yang produk ini tergolong di dalamnya.                                                          |
| product\[].categories\[].name                      | Nama kategori (contoh: “Kasut”, “Aksesori”).                                                                     |
| product\[].categories\[].permalink                 | Slug URL kategori yang mesra SEO (contoh: /category/shoes).                                                      |

#### Parameter Product related

| Parameter                                                                         | Penerangan                                                                        |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| product\[].related\[]                                                             | Senarai produk berkaitan yang disyorkan bersama produk utama.                     |
| product\[].related\[].id                                                          | ID unik untuk produk berkaitan.                                                   |
| product\[].related\[].name                                                        | Nama produk berkaitan.                                                            |
| product\[].related\[].description                                                 | Deskripsi ringkas untuk produk berkaitan.                                         |
| product\[].related\[].price                                                       | Harga jualan produk berkaitan.                                                    |
| product\[].related\[].compare\_at\_price\_min                                     | Harga asal atau harga compare-at tertinggi jika produk sedang promosi.            |
| product\[].related\[].compare\_at\_price\_max                                     | Harga compare-at maksimum (jika harga berubah ikut variasi).                      |
| product\[].related\[].url                                                         | URL terus ke halaman produk.                                                      |
| product\[].related\[].images                                                      | Senarai gambar produk.                                                            |
| product\[].related\[].featured\_images                                            | Gambar utama produk.                                                              |
| product\[].related\[].available                                                   | Menunjukkan sama ada produk berkaitan ini ada stok.                               |
| product\[].related\[].price\_varies                                               | "True" jika harga produk berubah ikut variasi.                                    |
| product\[].related\[].selected\_or\_first\_available\_variant                     | Variasi pertama yang tersedia (atau variasi terpilih).                            |
| product\[].related\[].selected\_or\_first\_available\_variant.id                  | ID variasi.                                                                       |
| product\[].related\[].selected\_or\_first\_available\_variant.name                | Nama variasi (contoh: Saiz M).                                                    |
| product\[].related\[].selected\_or\_first\_available\_variant.price               | Harga variasi.                                                                    |
| product\[].related\[].selected\_or\_first\_available\_variant.compare\_at\_price  | Harga asal variasi sebelum diskaun.                                               |
| product\[].related\[].selected\_or\_first\_available\_variant.available           | Menunjukkan jika variasi tersebut ada stok.                                       |
| product\[].related\[].selected\_or\_first\_available\_variant.inventory\_quantity | Jumlah stok untuk variasi tersebut.                                               |
| product\[].related\[].selected\_or\_first\_available\_variant.manage\_stock       | Menunjukkan jika stok dipantau.                                                   |
| product\[].related\[].variants\[]                                                 | Senarai semua variasi produk berkaitan.                                           |
| product\[].related\[].variants\[].id                                              | ID variasi.                                                                       |
| product\[].related\[].variants\[].name                                            | Nama variasi.                                                                     |
| product\[].related\[].variants\[].price                                           | Harga variasi.                                                                    |
| product\[].related\[].variants\[].compare\_at\_price                              | Harga asal sebelum diskaun.                                                       |
| product\[].related\[].variants\[].available                                       | Ketersediaan variasi.                                                             |
| product\[].related\[].variants\[].inventory\_quantity                             | Jumlah stok untuk variasi tersebut.                                               |
| product\[].related\[].variants\[].manage\_stock                                   | Menunjukkan jika stok dipantau.                                                   |
| product\[].related\[].variants\[].image                                           | Gambar variasi.                                                                   |
| product\[].related\[].variants\[].options                                         | Pilihan yang terikat pada variasi tersebut (contoh: Warna, Saiz).                 |
| product\[].related\[].metafield\[]                                                | Metafield custom yang berkaitan dengan produk.                                    |
| product\[].related\[].has\_options                                                | Menunjukkan jika produk mempunyai banyak pilihan.                                 |
| product\[].related\[].has\_only\_default\_variant                                 | "True" jika produk hanya ada satu variasi.                                        |
| product\[].related\[].has\_predefined\_options                                    | Menunjukkan jika pilihan ditetapkan oleh penjual.                                 |
| product\[].related\[].options\[]                                                  | Senarai pilihan produk (contoh: saiz, warna).                                     |
| product\[].related\[].options\[].id                                               | ID pilihan produk.                                                                |
| product\[].related\[].options\[].name                                             | Nama pilihan seperti “Saiz” atau “Warna”.                                         |
| product\[].related\[].options\[].type                                             | Jenis pilihan (contoh: dropdown, radio, swatch, date, datetime, input, textarea). |
| product\[].related\[].options\[].required                                         | Menunjukkan sama ada pelanggan perlu memilih pilihan tersebut.                    |
| product\[].related\[].options\[].values\[]                                        | Senarai nilai pilihan yang tersedia.                                              |
| product\[].related\[].options\[].values\[].name                                   | Nama nilai (contoh: “Red”, “Large”).                                              |
| products\[].related\[].options\[].values\[].metadata                              | Metadata tambahan untuk nilai pilihan (jika ada).                                 |

#### Parameter Product wholesale

| Parameter                                         | Penerangan                                                          |
| ------------------------------------------------- | ------------------------------------------------------------------- |
| product\[].wholesale\_prices\[]                   | Senarai peraturan harga borong untuk pembelian kuantiti banyak.     |
| product\[].wholesale\_prices\[].minimum\_quantity | Kuantiti minimum yang diperlukan untuk layak harga borong.          |
| product\[].wholesale\_prices\[].maximum\_quantity | Kuantiti maksimum yang dibenarkan untuk tier harga borong tersebut. |
| product\[].wholesale\_prices\[].unit\_price       | Harga diskaun bagi setiap unit apabila beli secara pukal.           |
| product\[].wholesale\_prices\[].saving\_per\_unit | Jumlah penjimatan bagi setiap unit berbanding harga runcit.         |

#### Parameter Product bundle

| Parameter                                                                                     | Penerangan                                                                       |
| --------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| product\[].bundle\_products\[]                                                                | Senarai produk yang termasuk dalam pakej bundle.                                 |
| product\[].bundle\_products\[].id                                                             | ID produk yang dimasukkan dalam bundle.                                          |
| product\[].bundle\_products\[].name                                                           | Nama produk yang termasuk dalam bundle.                                          |
| product\[].bundle\_products\[].images\[]                                                      | Galeri gambar untuk produk dalam bundle.                                         |
| product\[].bundle\_products\[].featured\_image                                                | Gambar utama yang dipaparkan untuk produk dalam bundle.                          |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[]                     | Varian yang dipilih atau varian pertama yang tersedia untuk produk dalam bundle. |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].id                  | ID varian.                                                                       |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].name                | Nama varian (contoh: Size L / Merah).                                            |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].price               | Harga jualan untuk varian dalam bundle.                                          |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].compare\_at\_price  | Harga asal varian sebelum diskaun.                                               |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].available           | Menunjukkan sama ada varian tersebut boleh dibeli atau tidak.                    |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].inventory\_quantity | Jumlah stok yang ada untuk varian tersebut.                                      |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].fixed\_quantity     | Kuantiti tetap yang disertakan dalam bundle (jika ada).                          |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].manage\_stock       | Menunjukkan sama ada pengurusan stok diaktifkan untuk varian ini.                |
| product\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].image               | Gambar untuk varian tersebut.                                                    |

#### Parameter Categories

| Parameter                                                                       | Penerangan                                                                                                                                                     |
| ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| categories                                                                      | Mengandungi semua kategori produk yang ada dalam store anda. Setiap kategori dikumpulkan bawah nama uniknya sendiri (contoh: "shawl", "bags", "new-arrivals"). |
| categories."category\_name".id                                                  | Pengecam unik untuk kategori tersebut.                                                                                                                         |
| categories."category\_name".name                                                | Nama paparan kategori. Contoh: "Premium Shawl" atau "Accessories".                                                                                             |
| categories."category\_name".permalink                                           | Slug kategori yang digunakan dalam URL. Contoh: "premium-shawl".                                                                                               |
| categories."category\_name".url                                                 | URL penuh untuk halaman kategori. Contoh: "/categories/premium-shawl".                                                                                         |
| categories."category\_name".template                                            | Fail template yang digunakan untuk paparkan halaman kategori (contoh: "collection", "custom-collection").                                                      |
| categories."category\_name".products\[]                                         | Senarai semua produk di bawah kategori ini. Setiap produk ikut struktur sama seperti objek products\[].                                                        |
| categories."category\_name".products\[].id                                      | Pengecam unik produk.                                                                                                                                          |
| categories."category\_name".products\[].name                                    | Nama produk. Contoh: "Satin Luxe Shawl".                                                                                                                       |
| categories."category\_name".products\[].description                             | Deskripsi ringkas produk.                                                                                                                                      |
| categories."category\_name".products\[].price                                   | Harga jualan semasa produk.                                                                                                                                    |
| categories."category\_name".products\[].compare\_at\_price\_min                 | Harga asal paling rendah (sebelum diskaun) antara semua varian produk.                                                                                         |
| categories."category\_name".products\[].compare\_at\_price\_max                 | Harga asal paling tinggi antara varian produk.                                                                                                                 |
| categories."category\_name".products\[].url                                     | Path URL produk. Contoh: "/products/satin-luxe-shawl".                                                                                                         |
| categories."category\_name".products\[].images                                  | Senarai semua URL gambar untuk produk.                                                                                                                         |
| categories."category\_name".products\[].is\_bundle                              | Menunjukkan sama ada produk ni adalah bundle (true) atau produk biasa (false).                                                                                 |
| categories."category\_name".products\[].featured\_image                         | Gambar utama produk yang dipaparkan.                                                                                                                           |
| categories."category\_name".products\[].available                               | Status stok produk — sama ada boleh dibeli atau tidak.                                                                                                         |
| categories."category\_name".products\[].price\_varies                           | Menunjukkan jika produk ada banyak varian dengan harga berbeza.                                                                                                |
| categories."category\_name".products\[].selected\_or\_first\_available\_variant | Mengandungi maklumat varian yang dipilih atau varian pertama yang tersedia.                                                                                    |
| categories."category\_name".products\[].variants\[]                             | Senarai semua varian produk (contoh: size, color).                                                                                                             |
| categories."category\_name".products\[].variants\[].id                          | Pengecam unik varian.                                                                                                                                          |
| categories."category\_name".products\[].variants\[].name                        | Nama varian. Contoh: "Dusty Blue / M".                                                                                                                         |
| categories."category\_name".products\[].variants\[].price                       | Harga jualan varian.                                                                                                                                           |
| categories."category\_name".products\[].variants\[].compare\_at\_price          | Harga asal varian sebelum diskaun.                                                                                                                             |
| categories."category\_name".products\[].variants\[].available                   | Menunjukkan sama ada varian ini dalam stok.                                                                                                                    |
| categories."category\_name".products\[].variants\[].inventory\_quantity         | Jumlah stok untuk varian tersebut.                                                                                                                             |
| categories."category\_name".products\[].variants\[].manage\_stock               | Sama ada pengurusan stok diaktifkan untuk varian ini.                                                                                                          |
| categories."category\_name".products\[].variants\[].image                       | Gambar yang berkaitan dengan varian.                                                                                                                           |
| categories."category\_name".products\[].variants\[].options                     | Pasangan data pilihan varian (contoh: "Color": "Maroon").                                                                                                      |
| categories."category\_name".products\[].metafields                              | Mengandungi data custom atau metadata tambahan untuk produk.                                                                                                   |
| categories."category\_name".products\[].has\_options                            | Menunjukkan sama ada produk mempunyai pilihan untuk dipilih (contoh: size, color).                                                                             |
| categories."category\_name".products\[].has\_only\_default\_variant             | Menunjukkan sama ada produk hanya ada satu varian default.                                                                                                     |
| categories."category\_name".products\[].has\_predefined\_options                | Sama ada produk menggunakan set pilihan yang telah ditetapkan.                                                                                                 |
