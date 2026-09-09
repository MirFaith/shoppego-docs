# Delyva

Penetapan ini mengandungi 3 bahagian iaitu :

{% hint style="success" %}
Fungsi ini tersedia untuk **plan Premium** dan **Ultimate**.
{% endhint %}

* **Bahagian 1**: Di platform Delyva
* **Bahagian 2**: Di platform Shoppego
* **Bahagian 3**: Cara Fulfill Order

## **Bahagian 1 : Penetapan Delyva**

Pastikan anda sudah mempunyai akaun Delyva.

{% hint style="info" %}
[Klik sini](https://my.delyva.app/customer/login) untuk pendaftaran [Delyva](https://my.delyva.app/customer/login). Pendaftaran Delyva adalah **percuma**.
{% endhint %}

1. Log masuk ke akaun **Delyva.**

![](../../../.gitbook/assets/-MgdLFQeW5N0XczyliuB.png)

2\. Di dalam Dashboard, klik pada **Nama anda** di **bahagian penjuru kanan atas.**

![](../../../.gitbook/assets/-Mgd8zqqdCshPUiMK6wV.jpg)

3. Klik pad tab **Settings.**

![](../../../.gitbook/assets/-Mgd9iQxlbwkQKSALX0_.jpg)

3\. Klik pada tab **API** **Integrations.**

![](../../../.gitbook/assets/-Mgd9az3DgHdRVycx74q.jpg)

4. Di page **API** **Integrations,** anda boleh dapatkan ketiga-tiga key yang diperlukan untuk integrations dengan sistem Shoppego.
   1. [Company ID](delyva.md#4-1-dapatkan-company-id)
   2. [Customer ID](delyva.md#4-2-dapatkan-customer-id)
   3. [API Key](delyva.md#4-3-dapatkan-api-key)

### **1 : Company ID**

1\. Di dalam halaman **API Integrations** tersebut anda boleh dapatkan nilai **Company ID** anda. Anda boleh rujuk paparan dibawah :

![](../../../.gitbook/assets/-MgdC6tg-mHtVokj0LHm.jpg)

### **2 : Customer ID**

1\. Di dalam halaman **API Integrations** tersebut anda boleh dapatkan nilai **Customer ID** anda. Anda boleh rujuk paparan dibawah :

![](../../../.gitbook/assets/-MgdEMDlxN9H5s_VaOH7.jpg)

### **3 : API Key**

1\. Didalam halaman API Integrations tersebut, anda boleh klik butang **Add new key.**

![](../../../.gitbook/assets/-MgdFXb97xtmQ44PDA9W.jpg)

2\. Kemudian nanti akan keluar popup untuk anda **masukkan nama bagi API key anda**.

{% hint style="info" %}
Anda boleh **masukkan sahaja nama** yang anda inginkan sebagai rujukan anda.
{% endhint %}

![](../../../.gitbook/assets/-MgdFbMrvwWrJlUbgQtC.png)

3\. Setelah selesai, anda boleh klik butang **Create & View.**

![](../../../.gitbook/assets/-MgdFkl2Dnl4kFXgkpT5.jpg)

4\. Nanti akan ada paparan yang menunjukkan **API key anda.**

![](../../../.gitbook/assets/-MgdFzFKCk9h3VHlF3uC.jpg)

5\. Anda boleh klik butang **Copy** untuk salin API key tersebut untuk dimasukkan didalam sistem Shoppego.

![](../../../.gitbook/assets/-MgdG43WOjSVxXWpvML9.jpg)

6\. Setelah anda masukkan atau simpan API key tersebut, anda boleh klik **Done.**

![](../../../.gitbook/assets/-MgdGHFp4tTyAB00Eyjy.jpg)

## **Bahagian 2 : Penetapan di Shoppego**

1\. Log masuk ke **Dashboad Shoppego** -> **Settings** -> **Shipping Providers.**

<figure><img src="../../../.gitbook/assets/6iS5SNhNJ70UnRj5VwHF.jpg" alt=""><figcaption></figcaption></figure>

2. Klik butang **Activate/Edit** pada ruangan **Shipping Provider Delyva.**

![](../../../.gitbook/assets/GBXIUwyGh8TJ4AlziBEn.jpg)

3. Masukkan maklumat **Company ID**, **Customer ID** dan **API key** yang anda dapatkan pada langkah [Penetapan di Bahagian 1](delyva.md#bahagian-1-penetapan-di-delyva).

![](../../../.gitbook/assets/bjhyk72RwJecx6Ra8OD7.jpg)

4. Setelah anda masukkan kesemua maklumat tersebut, anda boleh klik **Save**. Rujuk gambar di bawah.

{% hint style="success" %}
Pastikan kotak **Enable Delyva (Matdespatch)** ditandakan dengan **klik** pada kotak tersebut.
{% endhint %}

![](../../../.gitbook/assets/-MgdKuYBguyt7MrLiEgu.jpg)

Kini Shoppego anda telah siap di hubungkan dengan platform **Delyva**.

{% hint style="success" %}
Pastikan akaun anda mempunyai **kredit yang cukup** untuk menggunakan sistem **Delyva**.
{% endhint %}

## **Bahagian 3 : Cara Fulfill Order**

Tutorial penetapan pada bahagian untuk cara urus order bagi menjana Airway Bill di platform Delyva tanpa perlu log masuk dan hanya menggunakan platform Shoppego sahaja.<br>

1. Log masuk ke **Dashboard Shoppego** -> **Orders** di panel kir&#x69;**.**

![](../../../.gitbook/assets/lasUUilnpBxcaM16QKJd.png)

2. Pilih dan **klik** pada **order** yang dibuat penghantaran menggunakan Delyva dan paparan akan keluar seperti dibawah. Klik butang **Arrange shipment.**

![](../../../.gitbook/assets/8iFJZK2k86EUe0IDT4eN.jpg)

3. Tekan butang **Create Shipment** bewarna biru di sebelah penjuru kanan. Klik pada **Select Shipment Provider** dan pilih **Delyva.**

![](../../../.gitbook/assets/Snrqd2SFXavpmDkJNkAO.jpg)

4\. Klik pada **Choose Services.** Klik pada mana-mana courier service yang anda mahu gun&#x61;**.** Harga telah ditentukan mengikut alamat yang ada pada order.

![](../../../.gitbook/assets/dL3zOiXfkmN22agi99V7.jpg)

5\. Seterusnya klik pada method dan pilih **Dropoff** atau **Pickup.**

{% hint style="info" %}
**Method** :

* **Dropoff -** Anda sendiri akan pergi ke pejabat pos berhampiran dan hantarkan barang.
* **Pickup** - Pihak courier akan menghantar kenderaan untuk mengambil barang yang telah di pesan di alamat yang telah ditetapkan pada penetapan Location anda.
{% endhint %}

![](../../../.gitbook/assets/vNNJgWxQMXlok1HCGm2z.jpg)

{% hint style="info" %}
**\*\*Nota** : Jika anda menggunakan penghantaran jenis **Cash On Delivery (COD)**, pastikan anda telah memilih service jenis **COD** dan hidupkan toggle **Enable COD**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/WhMewIhW0XYkCKHoNP3V.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Biasanya Method **Pickup** akan dipilih bagi memudahkan para penjual.
{% endhint %}

6. Apabila **Method Pickup** dipilih, **jadual** akan dipaparkan untuk pilihan tarikh pengambilan oleh pihak courier. Klik pada tarikh yang anda mahukan dan kemudian klik butang **Submit**. Rujuk gambar dibawah.

<figure><img src="../../../.gitbook/assets/LmBo0DYgwr9lUYZ68hpu.jpg" alt=""><figcaption></figcaption></figure>

7. Setelah klik butang **Submit**, order anda akan automatik mendapat tracking number seperti gambar dibawah.

{% hint style="info" %}
Satu **Airwaybill (AWB)** terhadap order ini telah pun **dijana secara automatik** dan anda hanya perlu **cetak AWB** ni dari platform **Delyva**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/o21IcxEDTN7Sf7g0Qk7Y.jpg" alt=""><figcaption></figcaption></figure>

8. Setelah proses **Add Shipment** dibuat, semak di dalam Dashboard Delyva untuk pastikan maklumat yang akan keluar adalah sama.

![](../../../.gitbook/assets/-MBlPjueEZZL-DnOIsfS.jpg)

9. Kemaskini **Tracking kepada customer**﻿ setelah pihak courier mengambil barang. Klik pada **Order** tersebut dan paparan adalah seperti gambar di bawah. Seterusnya klik pada **Add Tracking.**

<figure><img src="../../../.gitbook/assets/aTPJ6KaspOVaZY2GIL59.jpg" alt=""><figcaption></figcaption></figure>

10. Klik pada carrier dan **pilih nama Carrier(1)** untuk order tersebut yang telah ditetapkan semasa proses Add Shipment. Klik butang **Save(2).**

<figure><img src="../../../.gitbook/assets/L6y2edTzdQi6Ox49ixM7.jpg" alt=""><figcaption></figcaption></figure>

11. Apabila butang **Save** ditekan, pelanggan anda akan mendapat email nombor tracking mereka secara automatik dari sistem Shoppego. **Nombor tracking** ini juga akan keluar di sebelah kanan order anda apabila ianya di **Save**.

<figure><img src="../../../.gitbook/assets/Y1xJmZiu7VwK8wIwyXwj.jpg" alt=""><figcaption></figcaption></figure>

12. Anda juga boleh perhatikan pada **orders list** untuk lihat bahawa order tersebut telah diletakkan **nombor tracking**.

{% hint style="info" %}
Tekan ikon **i** pada Fullfillment untuk anda semak **tracking number order** tersebut.
{% endhint %}

<figure><img src="../../../.gitbook/assets/dB6BJxLn7QIPN2RzeJcs.jpg" alt=""><figcaption></figcaption></figure>

13. Untuk **cetak Airwaybill (AWB)**, anda perlu **log masuk** ke dalam akaun Delyva, dan klik pada **ikon printer** untuk **print AWB** tersebut.

![](../../../.gitbook/assets/-MBlPjueEZZL-DnOIsfS.jpg)

14. Klik ikon **print** untuk **cetak Airwaybill(AWB)** ini dan tampalkan pada parcel anda.

![](../../../.gitbook/assets/-MBlPoIT8xIsmEUcxDMN.jpg)
