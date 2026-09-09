# AffanPay

Bagi menggunakan AffanPay sila pastikan anda **sudah cipta** terlebih dahulu **akaun AffanPay.**

{% hint style="success" %}
Anda perlu pastikan anda sudah:

* Mempunyai SSM/TIN&#x20;
* Akaun bank semasa.
{% endhint %}

{% hint style="info" %}
**Urusan pengesahan akaun, caj dan wang transaksi** adalah **diuruskan sepenuhnya oleh pihak AffanPay.**
{% endhint %}

## Pada Halaman Ini:

* [Penetapan di AffanPay](affanpay.md#penetapan-di-affanpay)
* [Penetapan di Shoppego](affanpay.md#penetapan-di-shoppego)

## Penetapan di AffanPay

{% hint style="danger" %}
**Sebelum anda ikuti tutorial ini, pastikan akaun AffanPay anda sudah di Verify terlebih dahulu dan pastikan anda tidak menggunakan Test account.**
{% endhint %}

Untuk lakukan integration payment gateway AffanPay dengan Shoppego, anda perlu dapatkan **Secret Key.**\
\
Jika anda masih belum mendaftar akaun Affanpay, anda boleh menggunakan link ini:\
[https://app.affanpay.my/register](https://app.affanpay.my/register)

### Dapatkan Secret Key

1. Log masuk dalam akaun AffanPay anda.

<figure><img src="../../../../.gitbook/assets/shoppego-x-affanpay-dashboard.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada butang/teks **Settings > Developers. Nanti anda akan dapat lihat Secret key akaun anda untuk anda Copy dan masukkan kedalam penetapan di Shoppego.**

## Penetapan di Shoppego

1\. Log masuk ke dalam akaun Shoppego anda.

![](../../../../.gitbook/assets/dashboard-shoppego.jpg)

2\. Klik pada **Settings**

![](../../../../.gitbook/assets/dashboard-shoppego-click-settings.jpg)

3\. Klik pada **Payment options**

![](../../../../.gitbook/assets/dashboard-shoppego-settings-click-payment-options.jpg)

4\. Jika anda belum aktifkan payment option untuk AffanPay. Klik butang **Activate** pada bahagian **Alternative Payments** untuk AffanPay. Jika anda sudah aktifkan payment option untuk AffanPay klik butang **Edit.**

![](../../../../.gitbook/assets/dashboard-shoppego-payment-options-click-edit-affanpay.jpg)

5\. Seterusnya akan keluar paparan seperti dibawah, anda boleh isi maklumat tersebut :&#x20;

![](../../../../.gitbook/assets/dashboard-shoppego-affanpay.jpg)

* **Display name at checkout : Masukkan nama payment yang anda inginkan (Contoh AffanPay)**
* **Email :** **Masukkan email akaun AffanPay anda**
* **Password : Masukkan password akaun AffanPay anda**
* **Secret Key : Masukkan Secret Key akaun AffanPay anda yang anda baru sahaja Copy pada langkah sebelum ini.**

6\. Setelah selesai pastikan anda sudah klik **Enable** dan klik button **Save**.

![](../../../../.gitbook/assets/dashboard-shoppego-affanpay-click-save.jpg)

Setelah **Save** anda boleh membuat percubaan pembelian pada website anda untuk lihat payment option AffanPay tersebut semasa checkout untuk penetapan yang anda baru tetapkan sebentar tadi.
