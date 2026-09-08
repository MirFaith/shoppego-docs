# Pages

{% hint style="info" %}
Sebelum anda ikuti langkah penetapan ini pastikan anda:

* Sudah mempunyai produk yang anda ingin buat untuk **express checkout**
* Sudah mempunyai pages yang tersendiri untuk anda masukkan **fungsi express checkout**
  {% endhint %}

## Dapatkan Produk ID

1\. Log masuk ke akaun Shoppego anda

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Products**

![](../../.gitbook/assets/3QYpKlTI5mdyrdLeiYts.jpg)

3\. Klik pada Produk yang anda ingin masukkan fungsi Express Checkout tersebut.

![](../../.gitbook/assets/i3S3XPC8L5SjJS1W4hLs.jpg)

4\. Klik pada **Express checkout**

![](../../.gitbook/assets/bqs406u5zwylQ0lJnPQ6.jpg)

5\. Pilih variant yang anda ingin pelanggan anda terus beli dan simpan link tersebut

![](../../.gitbook/assets/iA6m613XvwBy9vep3yLN.jpg)

6\. Pastikan anda simpan terlebih dahulu URL link tersebut kerana ia akan digunakan untuk penetapan pada pages anda.&#x20;

## **Penetapan pada Pages**

1\. Log masuk akaun Shoppego anda&#x20;

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Online Store** -> **Pages**

![](../../.gitbook/assets/YW5MKHAFthkHAX6ApmOw.jpg)

3\. Klik pada butang **Edit** pada pages yang anda ingin masukkan fungsi Express Checkout tersebut.

![](../../.gitbook/assets/E1metuuRouovYFNz12pX.png)

4\. Klik pada **icon < >** untuk masukkan custom code butang anda

![](../../.gitbook/assets/cocGHw3XwzixRJbXOg1v.jpg)

5\. Seterusnya, anda hanya perlu masukkan **code** ini pada ruangan tersebut.

**Code** : \<a class="btn btn-success btn-lg text-white" href="**link produk variant anda**" target="\_blank">Buy Now\</a>\
\
**\*\* Pada bahagian href tersebut, anda boleh masukkan link produk variant anda yang anda baru dapatkan pada langkah 1**

![](../../.gitbook/assets/mGZb0URqfJBhu5XNJwYL.jpg)

6\. Setelah selesai anda boleh klik **Save** dan lihat hasilnya dengan tekan pada butang **Preview**.

![](../../.gitbook/assets/Dm5z1QnMT7RPIGXrcZE6.jpg)

### Info Tambahan

Jika anda mahu ubah styling butang anda, anda boleh rujuk link ini untuk maklumat lanjut : <https://getbootstrap.com/docs/4.0/components/buttons/>\
\
Jika anda ingin membuat pelanggan anda terus checkout dengan 3 produk terus, anda boleh asingkan setiap produk variant ID dengan simbol koma.\
\
**Sebagai contoh** : /cart/**57085:1,12345:2,57779:3**

{% hint style="info" %}
\*\* **Nombor selepas titik bertindih** tersebut merujuk kepada **quantity barang** yang dibeli. \
\
\*\* **Maksimum hanya 3 variant ID (yang valid)** sahaja yang boleh dibaca oleh sistem kami.
{% endhint %}
