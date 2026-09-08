# Notifications Parameter

Parameter ini membolehkan anda untuk **mengubah teks notifikasi email/mesej** yang pelanggan anda akan dapat mengikut kesesuaian anda.&#x20;

Sebagai contoh, anda ingin membuat teks seperti :

> **Order #SA123**\
> \
> **Shipping Information**\
> **Abu Ahmad**

Anda perlu menggunakan parameter seperti berikut :

> **Order {{ name }}**\
> \
> **Shipping Information**\
> **{{ customer.first\_name }} {{ customer.last\_name }}**

Untuk maklumat lanjut, dibawah adalah parameter yang anda boleh gunakan didalam **sistem Commerce**.

Ini adalah **parameter yang anda boleh gunakan untuk ruangan&#x20;**<mark style="color:red;">**Subject**</mark>**&#x20;di template notifikasi** anda:

Parameter ini hanya boleh digunakan untuk notifikasi **Files ready for download, Order status changed, Checkout abandoned, Order review & Order packed:**

| <p><strong>Parameter:</strong> {{ store.name }}<br><strong>Penerangan</strong>: Nama store anda</p><p><strong>Contoh</strong>: Hartamas</p>                             |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ store.email }}<br><strong>Penerangan</strong>: Email store anda</p><p><strong>Contoh</strong>: <hello@shoppego.com></p>               |
| <p><strong>Parameter:</strong> {{ store.url }}<br><strong>Penerangan</strong>: Link website anda</p><p><strong>Contoh</strong>: <https://hartamas.myshoppegram.com></p> |
| <p><strong>Parameter:</strong> {{ store.currency\_format }}<br><strong>Penerangan</strong>: Currency format yang anda gunakan</p><p><strong>Contoh:</strong> MYR</p>    |

Parameter ini hanya boleh digunakan untuk notifikasi **Orded shipped**, **Order status changed, Checkout abandoned, Order ready for pickup, Order review & Order packed:**

| <p><strong>Parameter:</strong> {{ customer.first\_name }}<br><strong>Penerangan</strong>: First name pelanggan</p><p><strong>Contoh</strong>: Abu</p>       |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ customer.last\_name }}<br><strong>Penerangan</strong>: Last name pelanggan</p><p><strong>Contoh</strong>: Ahmad</p>       |
| <p><strong>Parameter:</strong> {{ customer.name }}<br><strong>Penerangan</strong>: Nama penuh pelanggan</p><p><strong>Contoh</strong>: Abu Ahmad</p>        |
| <p><strong>Parameter:</strong> {{ customer.email }}<br><strong>Penerangan</strong>: Email pelanggan</p><p><strong>Contoh</strong>: <abuahmad@gmail.com></p> |
| <p><strong>Parameter:</strong> {{ customer.phone }}<br><strong>Penerangan</strong>: Nombor telefon pelanggan</p><p><strong>Contoh</strong>: 60123456789</p> |

***

Ini adalah **parameter yang anda boleh gunakan pada** **ruangan&#x20;**<mark style="color:red;">**Body**</mark>**&#x20;di template notikasi** anda:

| <p><strong>Parameter:</strong> {{ name }}<br><strong>Penerangan</strong>: Order number</p><p><strong>Contoh</strong>: #SA123</p>                                                                                                                           |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter</strong>: {{ store.url }}</p><p><strong>Penerangan</strong>: Link website anda</p><p><strong>Contoh</strong>: <https://hartamas.myshoppegram.com></p>                                                                                 |
| <p><strong>Parameter</strong>: {{ store.name }}</p><p><strong>Penerangan</strong>: Nama store anda</p><p><strong>Contoh</strong>: Hartamas</p>                                                                                                             |
| <p><strong>Parameter</strong>: {{ store.email }}</p><p><strong>Penerangan</strong>: Email store anda</p><p><strong>Contoh</strong>: <hello@shoppego.com></p>                                                                                               |
| <p><strong>Parameter</strong>: {{ store.currency\_format }}</p><p><strong>Penerangan</strong>: Currency format yang anda gunakan</p><p><strong>Contoh:</strong> MYR</p>                                                                                    |
| <p><strong>Parameter</strong>: {{ gateway\_details }}</p><p><strong>Penerangan</strong>: Arahan mengenai payment gateway</p><p><strong>Contoh</strong>: Payment can be made by direct bank transfer the amount to our bank details stated below.</p>       |
| <p><strong>Parameter</strong>: {{ gateway\_name }}</p><p><strong>Penerangan</strong>: Nama payment gateway/payment method yang digunakan semasa checkout</p><p><strong>Contoh</strong>: Securepay</p>                                                      |
| <p><strong>Parameter</strong>: {{ gateway\_type }}</p><p><strong>Penerangan</strong>: Jenis payment gateway yang digunakan</p><p><strong>Contoh</strong>: Untuk COD dan Bank deposit = manual</p><p>               Untuk payment gateway = alternative</p> |
| <p><strong>Parameter</strong>: {{ customer.first\_name }}</p><p><strong>Penerangan</strong>: First name pelanggan</p><p><strong>Contoh</strong>: Abu</p>                                                                                                   |
| <p><strong>Parameter</strong>: {{ customer.last\_name }}</p><p><strong>Penerangan</strong>: Last name pelanggan</p><p><strong>Contoh</strong>: Ahmad</p>                                                                                                   |
| <p><strong>Parameter</strong>: {{ customer.name }}</p><p><strong>Penerangan</strong>: Nama penuh pelanggan</p><p><strong>Contoh</strong>: Abu Ahmad</p>                                                                                                    |
| <p><strong>Parameter</strong>: {{ customer.email }}</p><p><strong>Penerangan</strong>: Email pelanggan</p><p><strong>Contoh</strong>: <abuahmad@gmail.com></p>                                                                                             |
| <p><strong>Parameter</strong>: {{ customer.phone }}</p><p><strong>Penerangan</strong>: Nombor telefon pelanggan</p><p><strong>Contoh</strong>: 60123456789</p>                                                                                             |
| <p><strong>Parameter</strong>: {{ shipping\_address.first\_name }}</p><p><strong>Penerangan</strong>: Maklumat first name yang dimasukkan pada bahagian shipping</p><p><strong>Contoh</strong>: Nur</p>                                                    |
| <p><strong>Parameter</strong>: {{ shipping\_address.last\_name }}</p><p><strong>Penerangan</strong>: Maklumat last name yang dimasukkan pada bahagian shipping</p><p><strong>Contoh</strong>: Rahimah</p>                                                  |
| <p><strong>Parameter</strong>: {{ shipping\_address.address }}</p><p><strong>Penerangan</strong>: Maklumat alamat yang dimasukkan pada bahagian Address</p><p><strong>Contoh</strong>: Blok B 01-02-03</p>                                                 |
| <p><strong>Parameter</strong>: {{ shipping\_address.address2 }} </p><p><strong>Penerangan</strong>: Maklumat alamat yang dimasukkan pada bahagian Address line kedua (Jika Ada)</p><p><strong>Contoh</strong>: Jalan Permata Permai</p>                    |
| <p><strong>Parameter</strong>: {{ shipping\_address.city }}</p><p><strong>Penerangan</strong>: Maklumat bandar yang dimasukkan pada bahagian City</p><p><strong>Contoh</strong>: Cyberjaya</p>                                                             |
| <p><strong>Parameter</strong>: {{ shipping\_address.state }}</p><p><strong>Penerangan</strong>: Maklumat daerah yang dimasukkan pada bahagian State</p><p><strong>Contoh</strong>: Selangor</p>                                                            |
| <p><strong>Parameter</strong>: {{ shipping\_address.zip }}</p><p><strong>Penerangan</strong>: Maklumat postal kod yang dimasukkan pada Postcode/Zip</p><p><strong>Contoh</strong>: 63000</p>                                                               |
| <p><strong>Parameter</strong>: {{ current\_year }}</p><p><strong>Penerangan</strong>: Tahun terkini</p><p><strong>Contoh</strong>: 2024</p>                                                                                                                |

Parameter ini hanya boleh digunakan untuk notifikasi **Order ready for pickup**:

| <p><strong>Parameter</strong>: {{ pickup\_address.company }}<br><strong>Penerangan</strong> : Nama syarikat anda untuk proses pickup<br><strong>Contoh</strong>: Hartamas</p>                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter</strong>: {{ pickup\_address.name }}<br><strong>Penerangan</strong> : Nama anda untuk proses pickup<br><strong>Contoh</strong>: Ali</p>                                                                                                          |
| <p><strong>Parameter</strong>: {{ pickup\_address.phone }}<br><strong>Penerangan</strong> : Nombor telefon syarikat anda untuk proses pickup<br><strong>Contoh</strong>: 60123456789</p>                                                                              |
| <p><strong>Parameter</strong>: {{ pickup\_address.email }}<br><strong>Penerangan</strong> : Alamat e-mel syarikat anda untuk proses pickup<br><strong>Contoh</strong>: <hello@shoppegram.com></p>                                                                     |
| <p><strong>Parameter</strong>: {{ pickup\_address.address }}<br><strong>Penerangan</strong> : Alamat syarikat anda untuk proses pickup<br><strong>Contoh</strong>: Blok B 01-02-03</p>                                                                                |
| <p><strong>Parameter</strong>: {{ pickup\_address.address2 }}<br><strong>Penerangan</strong> : Alamat syarikat anda untuk proses pickup<br><strong>Contoh</strong>: Jalan Permata Permai</p>                                                                          |
| <p><strong>Parameter</strong>: {{ pickup\_address.zip }}<br><strong>Penerangan</strong>: Maklumat postal kod yang dimasukkan pada Postcode/Zip<br><strong>Contoh</strong>: 12300</p>                                                                                  |
| <p><strong>Parameter</strong>: {{ pickup\_address.city }}<br><strong>Penerangan</strong>: Maklumat bandar yang dimasukkan pada bahagian City<br><strong>Contoh</strong>: Pasir Gudang</p>                                                                             |
| <p><strong>Parameter</strong>: {{ pickup\_address.state }}<br><strong>Penerangan</strong>: Maklumat negeri yang dimasukkan pada bahagian State<br><strong>Contoh</strong>: Johor Bahru</p>                                                                            |
| <p><strong>Parameter</strong>: {{ pickup\_address.country }}<br><strong>Penerangan</strong>: Maklumat negara yang dimasukkan pada bahagian Country<br><strong>Contoh</strong>: Malaysia</p>                                                                           |
| <p><strong>Parameter</strong>: {{ pickup\_address.instruction }}<br><strong>Penerangan</strong>: Arahan yang akan diberikan kepada pelanggan<br><strong>Contoh</strong>: Pastikan anda hubungi kami dalam masa 30 minit sebelum datang untuk pickup parcel anda. </p> |

Parameter ini hanya boleh digunakan untuk notifikasi **Order shipped, Order status changed, Checkout abandoned, Order ready for pickup, Order review & Order packed**:

| <p><strong>Parameter:</strong> {{ total\_price }}<br><strong>Penerangan</strong>: Jumlah harga order pelanggan</p><p><strong>Contoh</strong>: 180.00</p>                                                                   |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter</strong>: {{ total\_discount }}</p><p><strong>Penerangan</strong>: Jumlah diskaun yang pelanggan gunakan dalam order mereka(Jika ada)</p><p><strong>Contoh</strong>: 99.00</p>                        |
| <p><strong>Parameter</strong>: {{ shipping\_price }}</p><p><strong>Penerangan</strong>: Jumlah harga shipping yang pelanggan dikenakan(Jika ada)</p><p><strong>Contoh</strong>: 8.00</p>                                   |
| <p><strong>Parameter</strong>: {{ shipping\_method }}</p><p><strong>Penerangan</strong>: Nama shipping yang pelanggan telah pilih sewaktu di halaman checkout(Jika ada)</p><p><strong>Contoh</strong>: Normal shipping</p> |

Parameter ini hanya boleh digunakan untuk notifikasi **Order packed:**

| <p><strong>Parameter:</strong> {{ requires\_shipping }}<br><strong>Penerangan</strong>: Jika order itu memmpunyai shipping atau tidak</p><p><strong>Contoh</strong>: True(Untuk mempunyai shipping dan False(Untuk tidak mempunyai shipping)</p> |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

Parameter ini hanya boleh digunakan untuk notifikasi **Checkout abandoned &** **Order review:**

| <p><strong>Parameter:</strong> {{ currency }}<br><strong>Penerangan</strong>: Currency format yang anda gunakan</p><p><strong>Contoh:</strong> MYR</p> |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ |

Parameter ini hanya boleh digunakan untuk notifikasi **Order confirmation & File read for download:**

| <p><strong>Parameter:</strong> {{ files\[].name }}<br><strong>Penerangan</strong>: Nama file anda</p><p><strong>Contoh</strong>: Ebook Percuma</p>                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ files\[].url }}<br><strong>Penerangan</strong>: Link akses ke file anda</p><p><strong>Contoh</strong>: <https://shoppego.com></p> |

Parameter ini hanya boleh digunakan untuk notifikasi **Orded shipped**, **Order status changed, Checkout abandoned, Order ready for pickup, Order review & Order packed:**

| <p><strong>Parameter:</strong> {{ items\[].product.name }}<br><strong>Penerangan</strong>: Nama produk yang dibeli oleh pelanggan</p><p><strong>Contoh</strong>: T-shirt</p>    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ items\[].name }}<br><strong>Penerangan</strong>: Nama variant produk yang dibeli oleh pelanggan</p><p><strong>Contoh</strong>: Putih</p>      |
| <p><strong>Parameter:</strong> {{ items\[].price }}<br><strong>Penerangan</strong>: Harga produk anda</p><p><strong>Contoh</strong>: 50.00</p>                                  |
| <p><strong>Parameter:</strong> {{ items\[].quantity }}<br><strong>Penerangan</strong>: Kuantiti produk yang dibeli oleh pelanggan</p><p><strong>Contoh</strong>: 2</p>          |
| <p><strong>Parameter:</strong> {{ items\[].subtotal }}<br><strong>Penerangan</strong>: Jumlah harga produk yang dibeli oleh pelanggan</p><p><strong>Contoh</strong>: 100.00</p> |

Parameter ini hanya boleh digunakan untuk notifikasi **Order shipped:**

| <p><strong>Parameter:</strong> {{ tracking\_url }}<br><strong>Penerangan</strong>: URL tracking bagi courier yang anda pilih untuk proses order pelanggan</p><p><strong>Contoh</strong>: <https://www.ninjavan.co/en-my/tracking></p> |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ tracking\_number }}<br><strong>Penerangan</strong>: Nombor tracking pelanggan tersebut yang anda sudah masukkan sewaktu proses Add tracking</p><p><strong>Contoh</strong>: MY000000010NJVN</p>      |
| <p><strong>Parameter:</strong> {{ tracking\_company }}<br><strong>Penerangan</strong>: Nama syarikat/shipping carrier yang anda gunakan sewaktu proses Add tracking</p><p><strong>Contoh</strong>: Ninjavan</p>                       |
