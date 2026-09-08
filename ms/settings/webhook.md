# Webhook

{% hint style="info" %}

* **Webhook** boleh digunakan untuk anda **hantar mesej secara auto** melalui **Telegram** untuk **anda mendapat notifikasi berkenaan pembelian yang baru** dibuat oleh pelanggan anda.
* Anda juga boleh gunakan webhook ini untuk menghantar maklumat pembelian pelanggan anda kedalam Google Excel anda dan lain-lain lagi.
  {% endhint %}

{% hint style="success" %}
Fungsi Webhook ini hanya terdapat pada langganan plan **Standard**, **Premium** dan **Ultimate** sahaja
{% endhint %}

### Penetapan Webhooks&#x20;

1. Klik pada **Settings (1)** dan skrol kebawah sehingga jumpa bahagian **Webhooks (2)**.

<figure><img src="../../.gitbook/assets/sfExfBgeGdHDI80Z21tz.png" alt=""><figcaption></figcaption></figure>

2. Tekan butang **Add Webhook** untuk tambah webhook anda.

<figure><img src="../../.gitbook/assets/LRqPRQ3SfvyX0EanSi4Y.png" alt=""><figcaption></figcaption></figure>

3. Pilih **Status Webhhok (1)** kemudian masukkan nama yang ingin letak dalam ruangan **Name (2)** dan masukkan link webhook ke dalam ruangan **Callback URL (3).**

<figure><img src="../../.gitbook/assets/hNpGcangUWPtNjJbxSDq.png" alt=""><figcaption></figcaption></figure>

4. Tekan ikon **' || '** untuk hentikan penerimaan data dari webhook anda dan tekan sekali lagi untuk sambung penerimaan data dari webhook. Tekan ikon **tong sampah** untuk buang webhook.

<figure><img src="../../.gitbook/assets/DVCOutMpefEIccjE4NRm.png" alt=""><figcaption></figcaption></figure>

### Data Webhooks

Di Commerce ini, anda boleh menggunakan webhook tersebut untuk tarik data bagi setiap:&#x20;

<table data-header-hidden><thead><tr><th width="245">State</th><th>Descriptions</th></tr></thead><tbody><tr><td><strong>State</strong></td><td><strong>Descriptions</strong></td></tr><tr><td><strong>Order Paid</strong></td><td>Trigger apabila anda mark order anda as <strong>Paid</strong> atau <strong>Order telah berjaya dibayar</strong>.</td></tr><tr><td><strong>Order Shipped</strong></td><td>Trigger apabila anda <strong>masukkan tracking number</strong> pada order pelanggan tersebut</td></tr><tr><td><strong>Checkout Abandoned</strong></td><td>Trigger apabila pelanggan <strong>tidak melengkapkan pembayaran</strong> dalam masa 60 minit</td></tr><tr><td><strong>Checkout Completed</strong></td><td>Trigger apabila pelanggan <strong>berjaya checkout</strong> dan sampai sehingga ke thank you page</td></tr><tr><td><strong>Checkout Updated</strong></td><td>Trigger apabila pelanggan <strong>terima promosi Thank you Page Offer (TYPO)</strong> yang anda tawarkan</td></tr><tr><td><strong>Order Status Processing</strong></td><td>Trigger apabila anda ubah status order pelanggan kepada <strong>Processing</strong></td></tr><tr><td><strong>Order Status Completed</strong></td><td>Trigger apabila anda ubah status order pelanggan kepada <strong>Completed</strong></td></tr><tr><td><strong>Order Updated</strong></td><td>Trigger apabila <strong>order telah di-update</strong> apabila pelanggan menerima tawaran Thank You Page Offer (TYPO)</td></tr><tr><td><strong>Order Ready For Pickup</strong></td><td>Trigger apabila anda mengubah status order pelanggan kepada <strong>Ready for Pickup</strong></td></tr><tr><td><strong>Order Packed</strong></td><td>Trigger apabila anda mengubah status order pelanggan kepada <strong>Order Packed</strong></td></tr><tr><td><strong>Inventory Updated</strong></td><td>Trigger apabila ada berlaku <strong>perubahan pada kuantiti stok</strong> produk anda.</td></tr></tbody></table>

Disini, kami sertakan sekali value-value yang anda boleh tarik.

|                                                                                                                                                                                                                                                               |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter</strong> : {{ checkout }} <br><strong>Deskripsi</strong> : Data checkout <br><strong>Contoh</strong> : \[Collection]</p>                                                                                                                 |
| <p><strong>Parameter</strong> : {{ checkout.id }}<br><strong>Deskripsi</strong> : Id untuk data checkout <br><strong>Contoh</strong> : 1262140</p>                                                                                                            |
| <p><strong>Parameter</strong> : {{ checkout.domain }} <br><strong>Deskripsi</strong> : Domain/Subdomain kedai anda <br><strong>Contoh</strong> : mirfaith.myshoppegram.com</p>                                                                                |
| <p><strong>Parameter</strong> : {{ checkout.url }} <br><strong>Deskripsi</strong> : Link kedai anda <br><strong>Contoh</strong> : <https://mirfaith.myshoppegram.com> </p>                                                                                    |
| <p><strong>Parameter</strong> : {{ checkout.currency }} <br><strong>Deskripsi</strong> : Currency yang digunakan pada kedai anda <br><strong>Contoh</strong> : MYR</p>                                                                                        |
| <p><strong>Parameter</strong> : {{ checkout.total }} <br><strong>Deskripsi</strong> : Jumlah pembayaran yang dikenakan <br><strong>Contoh</strong> : 10</p>                                                                                                   |
| <p><strong>Parameter</strong> : {{ checkout.shipping }} <br><strong>Deskripsi</strong> : Harga shipping rates yang anda telah tetapkan <br><strong>Contoh</strong> : 0</p>                                                                                    |
| <p><strong>Parameter</strong> : {{ checkout.rate }} <br><strong>Deskripsi</strong> : Nama shipping rates yang pelanggan telah pilih <br><strong>Contoh</strong> : FREE SHIPPING COD</p>                                                                       |
| <p><strong>Parameter</strong> : {{ checkout.completed\_at }} <br><strong>Deskripsi</strong> : Tarikh dan masa pelanggan berjaya membuat pembayaran <br><strong>Contoh</strong> : 2021-03-03T22:58:32+08:00</p>                                                |
| <p><strong>Parameter</strong> : {{ checkout.created\_at }} <br><strong>Deskripsi</strong> : Tarikh dan masa pelanggan ingin membuat pembayaran <br><strong>Contoh</strong> : 2021-03-03T22:58:17+08:00</p>                                                    |
| <p><strong>Parameter</strong> : {{ checkout.items }} <br><strong>Deskripsi</strong> : Data items/variant dalam checkout <br><strong>Contoh</strong> : \[Collection]</p>                                                                                       |
| <p><strong>Parameter</strong> : {{ checkout.items\[].product }} <br><strong>Deskripsi</strong> : Data produk dalam checkout <br><strong>Contoh</strong> : \[Collection]</p>                                                                                   |
| <p><strong>Parameter</strong> : {{ checkout.items\[].product.name }} <br><strong>Deskripsi</strong> : Nama produk anda  <br><strong>Contoh</strong> : Test </p>                                                                                               |
| <p><strong>Parameter</strong> : {{ checkout.items\[].product.sku }} <br><strong>Deskripsi</strong> : SKU untuk variant produk anda <br><strong>Contoh</strong> : 123456</p>                                                                                   |
| <p><strong>Parameter</strong> : {{ checkout.items\[].name }} <br><strong>Deskripsi</strong> : Nama variant produk anda <br><strong>Contoh</strong> : 2 Unit/ Hitam</p>                                                                                        |
| <p><strong>Parameter</strong> : {{ checkout.items\[].currency }} <br><strong>Deskripsi</strong> : Currency yang digunakan pada kedai anda <br><strong>Contoh</strong> : MYR </p>                                                                              |
| <p><strong>Parameter</strong> : {{ checkout.items\[].price }} <br><strong>Deskripsi</strong> : Harga produk variants anda <br><strong>Contoh</strong> : 10</p>                                                                                                |
| <p><strong>Parameter</strong> : {{ checkout.items\[].quantity }} <br><strong>Deskripsi</strong> : Kuantiti produk variant anda yang di Checkout <br><strong>Contoh</strong> : 1</p>                                                                           |
| <p><strong>Parameter</strong> : {{ checkout.items\[].subtotal }} <br><strong>Deskripsi</strong> : Jumlah keseluruhan harga produk variant yang di Checkout <br><strong>Contoh</strong> : 10</p>                                                               |
| <p><strong>Parameter</strong> : {{ checkout.customer }} <br><strong>Deskripsi</strong> : Data customer yang checkout pada website anda <br><strong>Contoh</strong> : \[Collection]</p>                                                                        |
| <p><strong>Parameter</strong> : {{ checkout.customer.first\_name }} <br><strong>Deskripsi</strong> : Nama first name customer yang checkout pada website anda <br><strong>Contoh</strong> : Abu</p>                                                           |
| <p><strong>Parameter</strong> : {{ checkout.customer.last\_name }}<br><strong>Deskripsi</strong> : Nama last name customer yang checkout pada website anda <br><strong>Contoh</strong> : Ali</p>                                                              |
| <p><strong>Parameter</strong> : {{ checkout.customer.phone }} <br><strong>Deskripsi</strong> : Nombor telefon customer yang checkout pada website anda<br><strong>Contoh</strong> : 60123456789</p>                                                           |
| <p><strong>Parameter</strong> : {{ checkout.customer.email }} <br><strong>Deskripsi</strong> : Email customer yang checkout pada website anda <br><strong>Contoh</strong> : <abuali@gmail.com></p>                                                            |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address }} <br><strong>Deskripsi</strong> : Data shipping yang dimasukkan semasa checkout pada website anda <br><strong>Contoh</strong> : \[Collection]</p>                                             |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.first\_name }} <br><strong>Deskripsi</strong> : Nama first name yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : Nur</p>             |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.last\_name }}  <br><strong>Deskripsi</strong> : Nama last name yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : Aishah</p>           |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.phone }} <br><strong>Deskripsi</strong> : Nombor telefon yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : 601122334455</p>           |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.email }}  <br><strong>Deskripsi</strong> : Email yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : <nuraishah@gmail.com></p>          |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.address1 }}  <br><strong>Deskripsi</strong> : Address yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : Persiaran Permata Perdana</p> |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.address2 }} <br><strong>Deskripsi</strong> : Address line 2 (Jika ada) yang dimasukkan pada bahagian page shipping semasa checkout pada website anda</p><p><strong>Contoh</strong> : -</p>      |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.zip }} <br><strong>Deskripsi</strong> : Postal kod yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : 63000</p>                        |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.city }} <br><strong>Deskripsi</strong> : Bandar yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : Selangor</p>                        |
| <p><strong>Parameter</strong> : {{ checkout.shipping\_address.state }} <br><strong>Deskripsi</strong> : Daerah yang dimasukkan pada bahagian page shipping semasa checkout pada website anda <br><strong>Contoh</strong> : Cyberjaya</p>                      |
