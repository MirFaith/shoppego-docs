# Themes Features

Dokumen ini menyenaraikan ciri yang tersedia dalam tema Shoppego.

## Global Layout

Source: `layout.html`, `application.js`, `style.css`

* Menyediakan rangka laman responsif yang dikongsi oleh semua halaman.
* Merangkumi header global, kawasan kandungan utama, cart drawer, modal carian, footer, skrip, metadata, dan ruang analitik.
* Menyokong tajuk halaman dinamik, meta description, favicon, metadata Open Graph, serta metadata imej halaman/produk.
* Menyokong custom meta tags melalui tetapan tema.
* Menyokong font, CSS, JavaScript, dan kandungan daripada page builder apabila data page builder tersedia.
* Menggunakan sistem reka bentuk yang boleh dikonfigurasi untuk warna, tipografi, spacing, dan gaya komponen.
* Menyokong ikon untuk navigasi, carian, pagination, dan butang tindakan.
* Menyokong skrip analitik jika diperlukan.

### Header and Navigation

* Memaparkan logo kedai daripada tetapan tema apabila tersedia.
* Menggunakan nama kedai sebagai fallback apabila logo tidak dikonfigurasi.
* Menyediakan navigasi desktop untuk pautan menu utama.
* Menyokong pautan menu biasa, dropdown tahap pertama, dan flyout menu tahap kedua.
* Bertukar kepada menu hamburger di mobile apabila saiz skrin atau jumlah menu memerlukannya.
* Menyediakan menu mobile dalam bentuk full-screen atau drawer.
* Menyokong submenu bertingkat yang boleh dibuka di mobile.
* Menyediakan butang carian untuk membuka antaramuka carian.
* Menyediakan butang cart untuk membuka cart drawer.
* Memaparkan badge bilangan item cart apabila cart mempunyai item.

### Search

* Menyediakan antaramuka carian dalam bentuk modal atau drawer.
* Menyediakan input carian dengan autofocus apabila dibuka.
* Membenarkan carian dihantar melalui klik butang.
* Membenarkan carian dihantar dengan kekunci Enter.
* Mengarahkan carian ke halaman senarai produk bersama query carian dalam URL.
* Menyokong tutup melalui butang tutup, klik backdrop, atau kekunci Escape.
* Mengunci scroll body semasa overlay carian dibuka.

### Cart Drawer

* Menyediakan cart drawer yang masuk dari sisi skrin.
* Menunjukkan empty cart state bersama tindakan continue shopping.
* Menyenaraikan item cart biasa dengan imej produk, nama produk, varian/options, kuantiti, jumlah baris, dan tindakan remove.
* Menyenaraikan item bundle dengan maklumat produk utama, butiran item bundle, kuantiti bundle, compare-at price, dan penjimatan.
* Menunjukkan jumlah atau subtotal cart.
* Menyediakan tindakan view cart, update cart, dan checkout.
* Boleh dibuka semula secara automatik selepas proses add-to-cart supaya pengguna terus nampak maklum balas cart.
* Mengunci scroll body semasa cart drawer dibuka.

### Footer

* Menyokong menu footer pilihan.
* Menunjukkan tahun copyright secara dinamik.
* Menunjukkan nama kedai.
* Menyokong pautan atribusi platform atau kedai jika diperlukan.

## Homepage

Source: `home.html`

* Memaparkan seksyen landing yang berfokuskan produk.
* Menunjukkan grid produk responsif.
* Menghubungkan setiap kad produk ke halaman butiran produk.
* Menunjukkan imej produk dengan fallback placeholder.
* Menggunakan lazy loading untuk imej produk.
* Menunjukkan nama produk.
* Menunjukkan harga produk.
* Menunjukkan badge atau label sold-out untuk produk yang tidak tersedia.
* Menunjukkan empty state apabila tiada produk tersedia.

## Products Page

Source: `products.html`, `application.js`

* Memaparkan halaman senarai produk dengan grid responsif.
* Menunjukkan tajuk halaman.
* Menyediakan filter kategori atau koleksi.
* Menyediakan pautan All Products.
* Menjana pautan kategori secara dinamik daripada kategori atau koleksi yang tersedia.
* Menandakan kategori atau koleksi yang sedang aktif.
* Menyokong pagination.
* Menyediakan kawalan pagination previous dan next.
* Menunjukkan kesan hover pada imej produk apabila sesuai.
* Menunjukkan nama produk.
* Menunjukkan harga produk.
* Menunjukkan compare-at price apabila ada diskaun.
* Menunjukkan indikator harga berubah apabila harga produk mempunyai variasi.
* Menunjukkan badge atau label sold-out untuk produk yang tidak tersedia.
* Menggunakan lazy loading untuk imej produk.
* Menunjukkan kad produk placeholder atau empty state apabila tiada data produk.
* Menunjukkan teks empty-state yang jelas apabila tiada produk tersedia.

### Products Search Results

* Menyokong penapisan produk berdasarkan query carian daripada URL.
* Mengisi semula input carian dengan query carian semasa.
* Menapis kad produk berdasarkan nama produk atau teks produk yang boleh dicari.
* Menunjukkan mesej hasil ditemui bersama bilangan hasil dan istilah carian.
* Mengendalikan ayat tunggal dan jamak untuk bilangan hasil.
* Menunjukkan no-results state apabila tiada produk sepadan ditemui.
* Menyediakan pautan kembali ke semua produk daripada no-results state.
* Menyembunyikan header senarai biasa apabila no-results state perlu diberi fokus penuh.

## Product Page

Source: `product.html`, `application.js`

* Menyediakan susun atur butiran produk yang responsif.
* Menggunakan layout dua kolum pada skrin besar dan layout bertindan pada skrin kecil.
* Memaparkan semua imej produk dalam carousel atau galeri.
* Memasukkan imej varian dalam galeri apabila tersedia.
* Menyediakan fallback placeholder apabila produk tiada imej.
* Menyediakan kawalan previous dan next apabila terdapat banyak imej.
* Menyediakan navigasi thumbnail untuk imej produk dan imej varian.
* Menyokong interaksi swipe sentuh untuk galeri mobile.
* Mengemas kini galeri apabila pengguna memilih varian atau option yang mempunyai imej berkaitan.
* Menunjukkan breadcrumb kembali ke senarai produk dan kategori apabila tersedia.
* Menunjukkan tajuk produk.
* Menunjukkan harga produk.
* Menunjukkan compare-at price atau harga diskaun apabila tersedia.
* Menunjukkan sold-out state apabila produk tidak tersedia.
* Menunjukkan deskripsi produk sebagai kandungan rich text.
* Menunjukkan produk berkaitan apabila tersedia.
* Kad produk berkaitan merangkumi imej, nama, harga, paparan diskaun, sold-out state, dan kesan hover.

### Standard Product Purchase

* Menyediakan form add-to-cart.
* Menyediakan tindakan buy-now atau express-checkout.
* Menyokong add-to-cart secara asynchronous apabila platform membenarkannya.
* Membuka cart drawer atau memberi maklum balas cart yang jelas selepas add to cart berjaya.
* Mengesahkan pilihan wajib sebelum add to cart.
* Mengesahkan pilihan wajib sebelum buy now.
* Menunjukkan butang sold-out yang disabled untuk produk yang tidak tersedia.
* Menyimpan data varian untuk penyelesaian varian di client-side.
* Menunjukkan alert option apabila pilihan wajib belum dibuat.
* Scroll ke alert apabila diperlukan.
* Mengesahkan custom option yang wajib.
* Menyediakan pemilih kuantiti dengan butang plus dan minus.
* Membenarkan input kuantiti secara nombor.
* Mengehadkan input kuantiti kepada nilai nombor.
* Mengikut had stok untuk varian yang mempunyai managed stock.
* Menyokong kuantiti tanpa had untuk varian tanpa managed stock.
* Mengira semula harga produk apabila varian atau kuantiti berubah.
* Mengira semula compare-at price apabila kuantiti berubah.
* Menunjukkan kuantiti stok tersedia apabila stok diuruskan.

### Variant and Option Features

* Menyokong pemilihan varian terus apabila produk mempunyai banyak varian.
* Menyokong pilihan produk seperti radio, select, dan swatch.
* Menyokong color swatch.
* Menyokong paparan swatch satu warna dan dua warna.
* Menyokong butang option dengan imej pilihan.
* Melumpuhkan option yang sold-out secara visual.
* Menghalang option sold-out daripada dipilih.
* Mengemas kini ketersediaan option berdasarkan pilihan semasa.
* Menyokong selector varian dropdown lama apabila diperlukan.
* Menyokong selector option dropdown lama apabila diperlukan.
* Menyokong jenis medan custom option:
  * Tarikh
  * Datetime
  * Input teks
  * Textarea `maxlength="255"`
* Mengesahkan custom option wajib sebelum add to cart atau buy now.

### Wholesale Pricing

* Memaparkan harga borong atau harga pukal apabila dikonfigurasi.
* Menunjukkan julat kuantiti.
* Menunjukkan harga unit untuk setiap julat.
* Menunjukkan penjimatan bagi setiap unit.
* Mengemas kini harga produk berdasarkan kuantiti dipilih dan tier borong yang sepadan.

### Bundle Product Features

* Menyokong form add-to-cart untuk bundle.
* Menyimpan data varian bundle untuk kemas kini client-side.
* Menyimpan data harga bundle, compare-at price, harga jimat, stok, kuantiti tetap, ketersediaan, dan imej.
* Menunjukkan mesej ringkasan bundle dengan jumlah penjimatan atau mesej promosi fallback.
* Memaparkan baris produk bundle dengan thumbnail, nama produk, harga, selector varian, ketersediaan, dan kawalan kuantiti.
* Menunjukkan dropdown varian apabila produk dalam bundle mempunyai banyak varian.
* Menggunakan input varian tersembunyi apabila produk dalam bundle hanya mempunyai satu varian.
* Menunjukkan mesej out-of-stock untuk setiap varian bundle.
* Mengemas kini thumbnail bundle apabila varian dipilih mempunyai imej.
* Menunjukkan badge kuantiti tetap apabila varian bundle mempunyai kuantiti tetap.
* Menyembunyikan kawalan kuantiti apabila kuantiti tetap digunakan.
* Menyediakan input kuantiti plus, minus, dan nombor untuk item bundle.
* Mengikut had managed stock untuk kuantiti bundle.
* Mengemas kini harga item bundle secara dinamik.
* Mengemas kini compare-at price bundle secara dinamik.
* Mengemas kini jumlah jimat bundle secara dinamik.
* Mengemas kini jumlah harga bundle secara dinamik.
* Mengemas kini jumlah penjimatan bundle secara dinamik.
* Mengesahkan semua pilihan bundle yang wajib sebelum add to cart atau buy now.
* Memberi maklum balas ralat yang jelas apabila penghantaran bundle gagal atau timeout.

## Cart Page

Source: `cart.html`

* Menyediakan halaman cart khusus.
* Memaparkan kandungan cart hanya apabila cart mempunyai item dan checkout diaktifkan.
* Menunjukkan mesej ralat cart apabila tersedia.
* Menyediakan form update cart.
* Menyenaraikan item cart biasa dengan imej, pautan produk, varian/options, input kuantiti, jumlah baris, dan tindakan remove.
* Menyenaraikan item bundle dengan produk utama, teks penjimatan bundle, kuantiti utama, jumlah, dan tindakan remove.
* Menunjukkan pecahan item bundle bersarang.
* Item bundle bersarang merangkumi imej produk, nama produk atau varian, butiran option, kuantiti, compare-at price, jumlah, dan nilai penjimatan.
* Menunjukkan jumlah cart.
* Menunjukkan nota penghantaran atau cukai apabila kos tambahan dikira kemudian semasa checkout.
* Menyediakan tindakan Update Cart.
* Menyediakan tindakan Continue Shopping.
* Menyediakan tindakan Checkout.
* Menunjukkan empty cart state apabila cart tiada item atau checkout tidak tersedia.
* Menyediakan fallback imej produk.

## Custom Page

Source: `page.html`

* Menyokong output page builder apabila kandungan page builder diaktifkan.
* Menyediakan fallback halaman kandungan standard.
* Menunjukkan tajuk halaman.
* Memaparkan body halaman sebagai rich content.
* Mengekalkan minimum tinggi kandungan untuk halaman pendek.
* Menyokong gaya rich text yang mudah dibaca untuk heading, perenggan, senarai, pautan, blockquote, imej, jadual, inline code, dan code block.

## 404 Page

Source: `404.html`

* Menyediakan halaman not-found yang jelas.
* Menunjukkan ikon bertema pilihan.
* Menyediakan ikon fallback inline.
* Menunjukkan heading 404 yang besar.
* Menunjukkan mesej ringkas page-not-found.
* Menyediakan tindakan Back to Home.

## Styling and Theme Behavior

Source: `style.css`

* Menggunakan sistem layout responsif yang konsisten.
* Mengekalkan custom CSS hanya untuk keperluan komponen tema yang khusus.
* Menyediakan gaya dropdown option produk.
* Menyediakan gaya kawalan kuantiti produk.
* Menyediakan gaya placeholder imej atau SVG.
* Menyokong smooth scrolling untuk navigasi anchor.
* Menyediakan gaya carousel untuk galeri produk.
* Menyediakan gaya rich text untuk kandungan WYSIWYG.
* Menyediakan gaya jadual untuk halaman kandungan dan deskripsi produk.
* Menyediakan gaya code block untuk halaman kandungan.

## Javascript Utilities and interactions

Source: `application.js`

* Menyediakan helper untuk membuka dan menutup overlay.
* Menyediakan helper untuk mengunci scroll body.
* Menyediakan helper untuk menggantikan atau memulakan ikon.
* Menyediakan helper redirect carian.
* Menyediakan helper membuka semula cart drawer selepas add-to-cart.
* Mengendalikan buka dan tutup menu mobile.
* Mengendalikan toggle submenu mobile bertingkat.
* Mengendalikan buka, tutup, submit, dan keyboard behavior untuk modal carian.
* Mengendalikan buka dan tutup cart drawer.
* Mengendalikan slide carousel, thumbnail, arrow, dan swipe sentuh.
* Mengendalikan smooth scrolling untuk pautan anchor.
* Mengendalikan pemilihan varian dan option.
* Mengendalikan kemas kini kuantiti produk.
* Mengendalikan kemas kini kuantiti bundle.
* Menyediakan helper parse dan format harga.
* Mengemas kini harga produk secara dinamik.
* Mengemas kini harga borong secara dinamik.
* Mengemas kini harga bundle secara dinamik.
* Mengesahkan pilihan bundle.
* Mengesahkan custom option wajib.
* Memintas tindakan add-to-cart apabila cart asynchronous diperlukan.
* Mengesahkan tindakan buy-now sebelum form dihantar.
