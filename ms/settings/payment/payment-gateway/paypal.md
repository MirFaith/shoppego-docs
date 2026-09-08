# Paypal

{% hint style="info" %}
**Urusan pengesahan akaun, caj dan wang transaksi** adalah **diuruskan sepenuhnya oleh pihak Paypal**.
{% endhint %}

## Pendaftaran akaun Paypal

Klik di link ini <https://www.paypal.com/my/webapps/mpp/account-selection> untuk mula daftar  akaun Paypal anda. Bagi proses pendaftaran akaun Paypal pastikan anda memilih sebagai Business Account.

![](../../../../.gitbook/assets/NWcU8kF63R7C7WPGaOf5.png)

## Dapatkan kesemua key yang diperlukan dari akaun Paypal

Untuk menghubungkan Paypal dengan website Shoppego, anda memerlukan beberapa key untuk proses pengesahan. Antara key yang diperlukan ialah **Client ID** dan **Client Secret**. Untuk memulakan proses penetapan payment gateway Paypal anda boleh ikuti langkah penetapan ini :

1\. Log masuk ke akaun Paypal anda melalui link ini <https://developer.paypal.com/developer/applications>

![](../../../../.gitbook/assets/GYwY2u4F4toyf4566jjx.png)

2\.  Seterusnya pada bahagian dashboard Paypal, anda boleh klik pada tab **LIVE**

![](../../../../.gitbook/assets/lK3RcsIozIAKADhI0Kxs.png)

3\. Seterusnya anda akan dapat lihat butang **Create App** anda disitu. Anda boleh klik pada butang tersebut.

![](../../../../.gitbook/assets/1dVRv35uSeUoo5aJU6Cy.png)

4\. Pada paparan ini, anda dikehendaki untuk memasukan nama **App Name.** Disarankan untuk memasukkan nama bisnes anda sendiri. Seterusnya, tekan butang **Create App**.

![](../../../../.gitbook/assets/FJpj8cY4fu8avAsphcWu.png)

5\. Seterusnya, setelah anda klik pada **Create app** satu paparan baru akan muncul. Pada paparan ini anda dikehendaki untuk membuat penetapan webhook.&#x20;

![](../../../../.gitbook/assets/6j3TQsL3oeYEDhqTpSKy.png)

6\. Pada paparan ini anda **diwajibkan untuk memasukkan nama URL <https://subdomain.myshoppegram.com> akaun Shoppego anda yang telah diberikan secara percuma sewaktu pendaftaran akaun Shoppego** anda ke dalam **ruangan Webhook URL**.

Anda boleh dapati URL subdomain anda pada bahagian berikut:\
Dashboard Overview Shoppego -> **Settings** -> **Custom domain** -> **Subdomain**

<figure><img src="../../../../.gitbook/assets/i6ChVkQCDHAFSqE60OI8.jpg" alt=""><figcaption></figcaption></figure>

Sebagai contoh :\
**<https://hartamas.myshoppegram.com/webhooks/payments/callback/checkouts/paypal>** dan **tick** pada **Checkout** > **Checkout order approved**

![](../../../../.gitbook/assets/9n6gqzfValY7ovYOdgLt.jpg)

## Penetapan di Shoppego

Untuk proses penetapan payment gateway Paypal di Shoppego anda perlu aktifkan terlebih dahulu payment gateway tersebut dan masukkan kedua-dua key tersebut kedalam setting payment gateway anda.&#x20;

Untuk memulakan penetapan payment gateway tersebut, anda boleh ikut langkah penetapan ini.

1\. Log masuk akaun Shoppego anda.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Seterusnya anda boleh klik pada tab **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Anda akan dibawa ke halaman Settings dan anda boleh klik pada butang **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. Pada bahagian halaman Payment options, anda boleh klik butang **Activate/Edit** pada tab payment gateway Paypal.

![](../../../../.gitbook/assets/xLLfT2NuG0oYhLzQQK0l.jpg)

5\.  Dengan menggunakan key yang diberikan pada **Paypal Dashboard** -> **My App & Credentials** -> **LIVE** -> Pilih **App Name** yang anda cipta. Copy **Client ID** dan **Secret Key** , masukkan pada ruang Paypal di Shoppego. **Tick pada butang toggle Enable** dan klik butang **Save.**

{% hint style="info" %}
Sekiranya anda ingin **memulakan transaksi sebenar**, diminta untuk anda <mark style="color:red;">**mematikan**</mark> toggle **Test Mode** itu.
{% endhint %}

![](../../../../.gitbook/assets/LxPUTyR1ovRfS2rhuJEQ.jpg)

## Contoh di Website

Setelah selesai proses penetapan tersebut, anda boleh cuba membuat pembelian di website Shoppego anda untuk melihat hasilnya.

![](../../../../.gitbook/assets/aF8tmfdgtRCRp186HLZ7.png)
