# Multi-stores

Anda boleh menggunakan fungsi ini untuk selaraskan penolakan produk anda antara store-store Shoppego anda. **Perlu dimaklumkan sistem hanya akan selaraskan stok produk untuk:**

* **Perubahan stok dari platform Shoppego(master)**
* **Perubahan stok melalui pembelian di antara website**
* **Perubahan stok melalui proses cancel/refund di platform Shoppego**

**Fungsi penyelerasan stok antara platform Store Shoppego juga akan berpandukan penetapan SKU pada produk/variants produk itu sendiri.**

{% hint style="danger" %}
Fungsi ini hanya terdapat untuk langganan plan **Ultimate** sahaja.
{% endhint %}

## Format Produk Untuk Shoppego

Anda perlu pastikan setiap produk anda di Shoppego yang anda ingin selaraskan stok itu mempunyai SKU yang sama.

Untuk penetapan SKU di platform Shoppego, anda boleh pergi pada bahagian:

1. Log masuk akaun Shoppego

<figure><img src="../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Products**

<figure><img src="../../.gitbook/assets/3QYpKlTI5mdyrdLeiYts.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada produk yang anda ingin selaraskan stok itu atau anda boleh sahaja cipta produk yang baru.

<figure><img src="../../.gitbook/assets/WsykI0oqPDfVUycKw15s.jpg" alt=""><figcaption></figcaption></figure>

4. Anda boleh pergi pada tab **Variants**

<figure><img src="../../.gitbook/assets/hcJh169rZEzDyT4AnyPO.jpg" alt=""><figcaption></figcaption></figure>

5. Klik pada tab pemilihan variants yang anda ingin lakukan penambahan penetapan SKU untuk selaraskan stok.

<figure><img src="../../.gitbook/assets/DhqDZd1pxafo33ZP23v1.jpg" alt=""><figcaption></figcaption></figure>

6. Kemudian, anda **boleh masukkan penetapan SKU yang sama seperti produk anda di sstore yang lain itu pada penetapan "SKU (Stock Keeping Unit)" di platform Shoppego** dan klik **Save**

<figure><img src="../../.gitbook/assets/GWKksQRhlZDjve4OPIXq.jpg" alt=""><figcaption></figcaption></figure>

## Penetapan Multi-stores di Shoppego

1. Log masuk akaun Shoppego anda

<figure><img src="../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Settings**

<figure><img src="../../.gitbook/assets/dashboard-shoppego-click-settings.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada "**Multi-stores**"

<figure><img src="../../.gitbook/assets/dashboard-shoppego-settings-click-multi-stores (1).jpg" alt=""><figcaption></figcaption></figure>

4. Kemudian, anda boleh lakukan carian store Shoppego yang anda ingin selaraskan stok itu dan klik pada store tersebut.

<figure><img src="../../.gitbook/assets/dashboard-shoppego-multi-stores-select-store.jpg" alt=""><figcaption></figcaption></figure>

Nanti, anda akan diminta untuk terus lakukan pemilihan lokasi antara 2 store tersebut.

<figure><img src="../../.gitbook/assets/dashboard-shoppego-multi-stores-select-location.jpg" alt=""><figcaption></figcaption></figure>

Kini, store Shoppego anda sudah berhubung dengan akaun Woocommerce anda.

<figure><img src="../../.gitbook/assets/dashboard-shoppego-multi-stores-locations-selected.jpg" alt=""><figcaption></figcaption></figure>

## Maklumat Tambahan

Penyelarasan stok secara manual hanya boleh dilakukan untuk store yang menjadi "master/sumber utama" stok sahaja. Jika anda lakukan perubahan secara manual pada store yang bukan "master/sumber utama" stok, ia tidak akan berikan sebarang perubahan antara store tersebut.

**Penyegerakan stok automatik hanya berfungsi apabila SKU dalam Shoppego sama di antara store Shoppego tersebut sahaja**. Jika SKU tersebut berbeza, Shoppego tidak akan dapat menyegerakkan stok produk berkenaan.

**Salah satu store Shoppego akan menjadi sumber utama inventori anda**. Kami mengesyorkan agar anda mengemas kini stok produk hanya di store Shoppego tersebut sahaja. Elakkan daripada mengemas kini stok pada store Shoppego yang lain juga, kerana tindakan ini boleh menyebabkan ketidakseragaman data stok.
