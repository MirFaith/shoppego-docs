# Cloudflare Turnstile

Sebelum anda ikuti langkah di bawah, pastikan anda telah mempunyai akaun Cloudflare Turnstile. Jika anda masih belum mempunyai akaun tersebut, anda boleh lakukan pendaftaran pada link dibawah:

{% embed url="<https://dash.cloudflare.com/sign-up>" %}

Terdapat 2 data yang anda perlukan untuk integration Cloudflare Turnstile ini dengan sistem Shoppego:

* Site key
* Secret key

## Penetapan di Cloudflare Turnstile

1. Anda boleh log masuk kedalam dashboard Cloudflare anda terlebih dahulu

<figure><img src="../../../.gitbook/assets/88PyYDqTx9CQobeOYWFX.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Application security** dan **Turnstile**

<figure><img src="../../../.gitbook/assets/jMYVhxd0kOw1Nsu5LWK6.jpg" alt=""><figcaption></figcaption></figure>

3. Kemudian, anda boleh klik **Add widget**

<figure><img src="../../../.gitbook/assets/OwAfBlsf5Av0D5fUgM0i.jpg" alt=""><figcaption></figcaption></figure>

4. Nanti anda akan dapat lihat penetapan yang anda perlu lakukan. Untuk "**Widget name**" anda boleh masukkan teks nama untuk rujukan anda nanti.

<figure><img src="../../../.gitbook/assets/z1quo5AFcYn9T8BALlyb.jpg" alt=""><figcaption></figcaption></figure>

5. Kemudian, anda perlu lakukan penetapan Hostnames dengan klik pada butang "**Add Hostnames**"

<figure><img src="../../../.gitbook/assets/ODp3ptkcFhM3j6k6J0bH.jpg" alt=""><figcaption></figcaption></figure>

Jika anda **tidak ada penetapan hostname/domain di dalam akaun Cloudflare**, anda boleh **masukkan hostname/domain anda itu di bahagian Custom hostname(Highlight kuning)**.

Jika **hostname/domain anda itu sudah berada di dalam akaun Cloudflare** anda ini, anda boleh terus **lakukan pemilihan seperti yang telah dipaparkan(Highlight hijau)**.

Setelah selesai klik **Add**

<figure><img src="../../../.gitbook/assets/vyuUuwR0qbs2EVQB0Fbp.jpg" alt=""><figcaption></figcaption></figure>

6. Seterusnya, untuk penetapan "**Widget Mode**", anda boleh tetapkan ikut penetapan yang anda inginkan. Pihak kami syorkan anda tetapkan kepada "**Invisible**".

<figure><img src="../../../.gitbook/assets/e5mz4NeznMMUAx7QyxX5.jpg" alt=""><figcaption></figcaption></figure>

7. Setelah selesai klik **Create**

<figure><img src="../../../.gitbook/assets/R7oFT0Qg3wWEUyg8FAIn.jpg" alt=""><figcaption></figcaption></figure>

Kini, anda sudah boleh dapat lihat "**Site key**" dan "**Secret key**" yang anda perlu masukkan pada penetapan di dashboard Shoppego nanti.

<figure><img src="../../../.gitbook/assets/NBMafyuwTpKwTU50F3MY.jpg" alt=""><figcaption></figcaption></figure>

## Penetapan di Shoppego

1. Log masuk kedalam akaun Shoppego anda

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada **Captcha providers**

<figure><img src="../../../.gitbook/assets/WTAu7U4FoU0pJaCJ60S7.jpg" alt=""><figcaption></figcaption></figure>

4. Klik pada butang **Activate/Edit** untuk jenis provider "**Cloudflare Turnstile**"

<figure><img src="../../../.gitbook/assets/cbXRJ3HCKz0wbjySNxLu.jpg" alt=""><figcaption></figcaption></figure>

5. Kemudian, anda boleh **masukkan Site key** dan **Secret key** **Cloudflare Turnstile anda itu pada ruangan yang disediakan**. Pastikan **tick pada toggle Enable** dan klik **Save**

<figure><img src="../../../.gitbook/assets/sE3K4qVvNryEZTIXvLBg.jpg" alt=""><figcaption></figcaption></figure>

Kini penetapan anda sudah selesai. Anda sepatutnya dapat lihat paparan logo Cloudflare(Jika anda menggunakan "Widget mode" "Manage") itu nanti pada halaman yang mempunyai "Forms" dan juga halaman "Log masuk" website anda itu.

<figure><img src="../../../.gitbook/assets/in9s3cRCKwnP8DMIzgh2.jpg" alt=""><figcaption></figcaption></figure>
