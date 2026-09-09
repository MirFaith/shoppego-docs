# Stripe

Bagi menggunakan Stripe sila pastikan anda **sudah cipta** terlebih dahulu **akaun Stripe.**

{% hint style="info" %}
**Urusan pengesahan akaun, caj dan wang transaksi** adalah **diuruskan sepenuhnya oleh pihak Stripe**.
{% endhint %}

{% hint style="danger" %}
Jumlah transaksi minimum untuk Stripe ialah sekurang-kurangnya RM2.00
{% endhint %}

## Dapatkan API key di Stripe

1\. Pendaftaran akaun Stripe boleh dibuat di : [https://dashboard.stripe.com/register](https://dashboard.stripe.com/register)

2\. Untuk mendapatkan api key anda boleh mencarinya di **dashboard** atau klik sahaja link ini : [https://dashboard.stripe.com/login?redirect=%2Faccount%2Fapikeys](https://dashboard.stripe.com/login?redirect=%2Faccount%2Fapikeys)

3\. Setelah anda mendapatkan **Publishable key** dan **Secret key** anda boleh simpankan key tersebut untuk penetapan di Shoppego.

![](../../../../.gitbook/assets/-MD8Z-UDHUXIhH4PNbRk.png)

## Penetapan Webhooks di Stripe

Terdapat 2 jenis webhooks yang anda perlu masukkan pada penetapan webhooks akaun Stripe anda, iaitu:\
1\. [https://hartamas.myshoppegram.co\&#x6D;\*\*/webhooks/payments/callback/checkouts/stripe\*\*\\\\](https://hartamas.myshoppegram.co&/#x6D;**/webhooks/payments/callback/checkouts/stripe**\\\\) 2. [https://hartamas.myshoppegram.co\&#x6D;\*\*/webhooks/payments/callback/typ\\\\\_offer/stripe](https://hartamas.myshoppegram.co&/#x6D;**/webhooks/payments/callback/typ\\\\_offer/stripe)\*\*

Anda **diwajibkan untuk menggantikan** [**https://hartamas.myshoppegram.com**](https://hartamas.myshoppegram.com) **tersebut dengan URL** [**https://subdomain.myshoppegram.com**](https://subdomain.myshoppegram.com) **website anda yang tersendiri yang telah diberikan secara percuma sewaktu pendaftaran akaun Shoppego anda** tersebut.

Anda boleh dapati URL subdomain anda pada bahagian berikut:\
Dashboard Overview Shoppego -> **Settings** -> **Custom domain** -> **Subdomain**

<figure><img src="../../../../.gitbook/assets/i6ChVkQCDHAFSqE60OI8.jpg" alt=""><figcaption></figcaption></figure>

Anda boleh rujuk contoh penetapan webhooks dibawah:

1. Didalam dashboard Stripe tersebut, anda boleh klik pada bahagian **Developers** -> **Webhooks**. Anda juga boleh klik pada link ini terus: [https://dashboard.stripe.com/webhooks](https://dashboard.stripe.com/webhooks)

<figure><img src="../../../../.gitbook/assets/CpjwIAo8ZjwuuYrEEMAS.png" alt=""><figcaption></figcaption></figure>

2. Seterusnya, anda boleh klik pada **Add an endpoint/Add endpoint**

<figure><img src="../../../../.gitbook/assets/OuVy4UW3iXmuB2PvOKBk.jpg" alt=""><figcaption></figcaption></figure>

3. Seterusnya, anda boleh **masukkan salah satu URL webhooks store anda yang tersendiri pada bahagian Endpoint URL**. Sebagai contoh disini, kami telah masukkan URL ini terlebih dahulu: [https://hartamas.myshoppegram.com/webhooks/payments/callback/checkouts/stripe](https://hartamas.myshoppegram.com/webhooks/payments/callback/checkouts/stripe)

<figure><img src="../../../../.gitbook/assets/Ik4VT0UP5PyIaSt12KgA.jpg" alt=""><figcaption></figcaption></figure>

4. Kemudian, anda boleh **klik** pada **butang Select events**

<figure><img src="../../../../.gitbook/assets/MxpMbYZlb9i8iXiIRmcL.jpg" alt=""><figcaption></figcaption></figure>

5. Setelah anda dapat lihat paparan pemilihan events, anda boleh **cari events** yang mempunyai nama **Payment Intent** dan anda boleh **klik pada event tersebut**.

<figure><img src="../../../../.gitbook/assets/0LHR70LozLVqfOyaLxke.jpg" alt=""><figcaption></figcaption></figure>

6. Kemudian, anda boleh **tick Select all Payment Intent events** terlebih dahulu.

<figure><img src="../../../../.gitbook/assets/8Nf6CxecwtHrQUzb8ZJg.jpg" alt=""><figcaption></figcaption></figure>

7. Seterusnya, anda boleh **untick checkbox payment\_intent.amount\_capturable\_updated** dan **payment\_intent.partially\_funded**

<figure><img src="../../../../.gitbook/assets/JZKdsrfIT6SbXq5SsmlU.jpg" alt=""><figcaption></figcaption></figure>

8. Setelah selesai, anda boleh klik pada butang **Add events**

<figure><img src="../../../../.gitbook/assets/B7pysE3FIrK6VtUIhfRi.jpg" alt=""><figcaption></figcaption></figure>

9. Setelah anda pastikan penetapan anda sudah betul, anda boleh klik pada butang **Add endpoint**

<figure><img src="../../../../.gitbook/assets/NaHsOzf9DUpkLy5hh1Nk.jpg" alt=""><figcaption></figcaption></figure>

10. Jika anda dibawa kehalaman ini, anda boleh klik sahaja semula pada butang **Webhooks**

<figure><img src="../../../../.gitbook/assets/4x6TKKV933cjpI9JZssW.jpg" alt=""><figcaption></figcaption></figure>

11. Nanti, anda akan dibawa semula ke halaman Webhooks dan anda boleh lihat penetapan endpoint yang anda baru lakukan sebelum ini. Seterusnya anda boleh **ulang langkah diatas dan masukkan pula endpoint/webhooks URL yang kedua**.

<figure><img src="../../../../.gitbook/assets/L7jz5pi7hCvs6MkxqskS.png" alt=""><figcaption></figcaption></figure>

Setelah selesai, anda sepatutnya akan mempunyai **2 endpoint/webhooks URL** seperti pada paparan dibawah:

<figure><img src="../../../../.gitbook/assets/QTvA4EazoEqf1DyPbjn0.png" alt=""><figcaption></figcaption></figure>

## Penetapan di Shoppego

1\. Log masuk ke akaun Shoppego anda.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Klik pada **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. Jika anda belum aktifkan payment option untuk Stripe. Klik butang **Activate** pada bahagian **Alternative Payments** untuk Stripe. Jika anda sudah aktifkan payment option untuk Stripe klik butang **Edit.**

![](../../../../.gitbook/assets/4RR2o2QPI4YtfTS3OtQk.jpg)

5\. Seterusnya akan keluar paparan seperti dibawah, anda boleh isi maklumat tersebut :

![](../../../../.gitbook/assets/Y7mRZk9lurcPP9Bixg7T.jpg)

* **Display name at checkout : Masukkan nama payment yang anda inginkan ( Contoh Online Payment )**
* **Publishable key : Masukkan Publishable key yang anda sudah dapatkan di akaun Stripe anda.**
* **Secret key : Masukkan Secret key yang anda sudah dapatkan di akaun Stripe anda.**

6\. Setelah selesai pastikan anda sudah klik **Enable** dan klik button **Save**.

{% hint style="info" %}
Sekiranya anda ingin **memulakan transaksi sebenar**, diminta untuk anda <mark style="color:red;">**mematikan**</mark> toggle **Test Mode** itu.
{% endhint %}

![](../../../../.gitbook/assets/dS3chJnBh2OUueJHYYAi.png)

7\. Setelah **Save** anda boleh membuat percubaan pembelian pada website anda untuk lihat payment option Stripe tersebut semasa checkout untuk penetapan yang anda baru tetapkan sebentar tadi.
