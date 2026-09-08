# Chip

Bagi menggunakan Chip sila pastikan anda **sudah cipta** terlebih dahulu **akaun Chip.**

{% hint style="success" %}
Anda perlu pastikan anda sudah:

* Mempunyai SSM&#x20;
* Akaun bank semasa.
  {% endhint %}

{% hint style="info" %}
**Urusan pengesahan akaun, caj dan wang transaksi** adalah **diuruskan sepenuhnya oleh pihak Chip**.
{% endhint %}

## Penetapan di Chip

Untuk lakukan integration payment gateway Chip dengan Shoppego, anda perlu dapatkan **Brand ID**, **Secret key.**\
\
Jika anda masih belum mendaftar akaun Chip, anda boleh menggunakan link ini:\
<https://onboarding.chip-in.asia/>

### Dapatkan Brand ID

1. Log masuk dalam akaun Chip anda.

<figure><img src="../../../../.gitbook/assets/vG67oKqRpQdGbzkyFYnK.png" alt=""><figcaption></figcaption></figure>

2. Klik pada butang/teks **Developers**

<figure><img src="../../../../.gitbook/assets/y3xhqMXHs6ajXiBz50HV.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada butang/teks **Brands**

<figure><img src="../../../../.gitbook/assets/OBbjjBjC1apTBFfGRpi7.jpg" alt=""><figcaption></figcaption></figure>

4. Kemudian, anda boleh **copy Brand ID** anda seperti yang dalam paparan dibawah. **Brand ID ini anda perlu simpan untuk penetapan di Shoppego pula nanti**.

<figure><img src="../../../../.gitbook/assets/ylGIpR2ZGvgy3ROV7N35.jpg" alt=""><figcaption></figcaption></figure>

### Dapatkan Secret Key

1. Dari halaman **Developers**, anda boleh klik pula pada butang/teks **Keys**.

<figure><img src="../../../../.gitbook/assets/fafsVFJDy1U16c71bHwr.jpg" alt=""><figcaption></figcaption></figure>

2. Kemudian, pastikan **toggle View/Viewing test data tersebut dalam keadaan nyah aktif(berwarna kelabu)**.

<figure><img src="../../../../.gitbook/assets/lj69nkTqv7tDNbHCkSqm.jpg" alt=""><figcaption></figcaption></figure>

3. Seterusya, anda boleh klik pada butang **New live key**

<figure><img src="../../../../.gitbook/assets/MlaNWaQdHZbP20IjTp2P.jpg" alt=""><figcaption></figcaption></figure>

3. Kemudian, anda akan diminta untuk **masukkan Key title pada ruangan yang telah disediakan**. Key title ini bertindak sebagai rujukan untuk anda kenali key ini digunakan dimana nanti. Sebagai contoh kami masukkan Shoppego dan setelah itu klik **Create**.

<figure><img src="../../../../.gitbook/assets/iZ55pW97NGpQRiGIp2vM.jpg" alt=""><figcaption></figcaption></figure>

4. Setelah anda cipta key tersebut, anda boleh **klik semula pada key itu** dan anda boleh klik pada butang/teks **Copy**. **Anda perlu simpan key ini untuk lakukan penetapan di Shoppego pula nanti**.

<figure><img src="../../../../.gitbook/assets/4U1yAruNefJebqkM7PN5.jpg" alt=""><figcaption></figcaption></figure>

## Penetapan di Shoppego

1\. Log masuk ke dalam akaun Shoppego anda.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Klik pada **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. Jika anda belum aktifkan payment option untuk Chip. Klik butang **Activate** pada bahagian **Alternative Payments** untuk Chip. Jika anda sudah aktifkan payment option untuk Chip klik butang **Edit.**

![](../../../../.gitbook/assets/Lh0e3bJ2ljzdooESDyvW.jpg)

5\. Seterusnya akan keluar paparan seperti dibawah, anda boleh isi maklumat tersebut :&#x20;

![](../../../../.gitbook/assets/KRk9znifIZqSXZssPLaS.jpg)

* **Display name at checkout : Masukkan nama payment yang anda inginkan (Contoh Chip)**
* **Secret key : Masukkan Secret key yang anda sudah dapatkan di akaun Chip anda.**
* **Brand ID : Masukkan Brand ID yang anda sudah dapatkan di akaun Chip anda.**

6\. Setelah selesai pastikan anda sudah klik **Enable** dan klik button **Save**.

{% hint style="info" %}
**Untuk makluman,&#x20;**<mark style="color:red;">**toggle Test mode**</mark>**&#x20;hanya digunakan oleh pihak Developer sahaja. Untuk pengguna Shoppego, sila pastikan anda&#x20;**<mark style="color:red;">**nyah aktifkan**</mark>**&#x20;toggle tersebut.**
{% endhint %}

![](../../../../.gitbook/assets/VxNwkeQT1Ci4gDLYEJiu.jpg)

Setelah **Save** anda boleh membuat percubaan pembelian pada website anda untuk lihat payment option Chip tersebut semasa checkout untuk penetapan yang anda baru tetapkan sebentar tadi.
