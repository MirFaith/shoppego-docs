# Godaddy

Terdapat 3 bahagian untuk setup ini:

* **Bahagian 1** : Dapatkan value untuk CNAME record
* **Bahagian 2** : Penetapan di Godaddy
* **Bahagian 3** : Penetapan di Shoppego

{% hint style="warning" %}
Pastikan **domain anda sudah dibeli dan sudah boleh digunakan untuk setup**. Jika anda **membeli domain ".com", anda boleh terus ikut tutorial ini**.&#x20;
{% endhint %}

Jika **domain Malaysia** seperti **".my, .com.my, .net.my"** anda perlu lakukan penetapan **DNS records** ini didalam akaun **MYNIC** anda yang tersendiri atau anda boleh hubungi pihak **domain provider** anda untuk lakukan penetapan tersebut.

**Bermula 26 Februari 2026 setiap pengguna Shoppego hanya perlu lakukan CNAME record sahaja dan setiap store/website akan mempunyai value/penetapan CNAME record yang sama.**

## **Bahagian 1 :** Nilai CNAME Record

1\. Anda boleh log masuk kedalam dashboard Shoppego

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Settings**

![](../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Klik pada **Custom domain**

![](../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg)

4\. Klik pada **Add existing domain**

![](../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg)

5\. Anda akan lihat paparan yang mempunyai **nilai CNAME Record anda**.

{% hint style="info" %}
**Penetapan CNAME di dalam domain provider.**

**1 :** Jika **nilai CNAME** adalah **@**, masukkan **nama domain anda** atau "**@**" didalam **ruang CNAME** dalam domain provider.
{% endhint %}

![](../../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg)

## Bahagian 2 : Penetapan di Godaddy

1\. Log masuk kedalam **Akaun Godaddy anda** dan pergi pada halaman produk anda.\
\
2\. Pada ruangan **Domain Manager**, anda boleh klik pada domain yang anda ingin tetapkan penetapan **DNS** record tersebut.\
\
3\. Skroll kebawah pada ruangan **Additional Settings** dan **Klik pada Manage DNS**.

![](../../../.gitbook/assets/-MBm5dQGcp3zlmavJrWY.png)

{% hint style="info" %}
**Sekiranya domain provider anda ini tidak boleh lakukan penetapan CNAME record untuk host ke main domain atau @ anda boleh lakukan pemindahan pengurusan DNS ke sistem Cloudflare. Boleh rujuk di link ini untuk contoh penetapan:** [**https://docs.shoppego.com/ms/settings/custom-domain/cloudflare**](cloudflare.md)
{% endhint %}

### Penetapan CNAME Record

1. Pada halaman **DNS Management**, di bahagian **Records** anda boleh klik pada **Add**.
2. Anda boleh **pilih CNAME** daripada **pilihan Type** untuk ruangan menu tersebut.
3. Anda boleh masukkan maklumat yang mereka minta untuk penetapan CNAME record anda:
   * Type : CNAME
   * Name : **@** atau **nama domain anda**
   * Data : **shops.shoppego.my**
   * TTL: **Default (1 Hour)**

### Penetapan CNAME Record www (tidak diwajibkan)

1. Klik **Add semula** dan **pilih CNAME** dari pilihan **Type.**
2. Anda boleh **pilih CNAME** daripada **pilihan Type** untuk ruangan menu tersebut.
3. Anda boleh masukkan maklumat yang mereka minta untuk penetapan A record anda:
   * Type : **CNAME**
   * Name : **www**
   * Data : **shops.shoppego.my**
   * TTL : **Default (1 Hour)**

Paparan penetapan domain anda akan seperti dibawah.

<figure><img src="../../../.gitbook/assets/RVF69TdBjIwjaukji52d.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Setelah selesai anda boleh klik **Save.** Setelah itu anda boleh rujuk [**Tempoh Propagation**](godaddy.md#tempoh-propagation).
{% endhint %}

## Tempoh propagation

Anda hanya perlu <mark style="color:red;">**tunggu dalam tempoh 48 jam**</mark> untuk penetapan tersebut dapat dibaca dan domain anda boleh digunakan sebelum anda lakukan penetapan Custom domain di Shoppego.

**Tempoh paling cepat** domain anda boleh digunakan ialah **dalam 1 jam**. Jika tidak, anda perlu tunggu dalam **tempoh 48 jam hingga ke 72 jam** tersebut.

Anda boleh semak status propagation domain anda melalui link yang telah kami berikan (<https://www.whatsmydns.net/>)

## **Info Tambahan**

﻿Bagi memastikan DNS anda telah dituju ke Shoppego anda boleh [Semak DNS anda Disini](https://www.whatsmydns.net/) dan pastikan DNS yang terpapar ialah **penetapan yang anda telah tetapkan**

Bagi menyemak DNS anda:

1. Anda boleh klik Link ini : [Semak DNS anda Disini](https://www.whatsmydns.net/) atau <https://www.whatsmydns.net/>

{% hint style="info" %}
Anda boleh **masukkan nama domain anda** (**beserta www** dan tanpa www) ke dalam ruangan yang disediakan. Pastikan anda telah lakukan perubahan kepada semakan CNAME record.
{% endhint %}

<figure><img src="../../../.gitbook/assets/CrQgoaGRS5ABXprQaxE5.jpg" alt=""><figcaption></figcaption></figure>

## Bahagian 3 : Penetapan di Shoppego

1. Pada Dashboard Shoppego, anda boleh tekan **Settings (1)** dan skrol ke bawah sehingga ke **Custom Domain (2).**

<figure><img src="../../../.gitbook/assets/rkJDVGfqLTo3sj7i9kCn.jpg" alt=""><figcaption></figcaption></figure>

2. Selepas itu, tekan **Add Existing Domain**.

<figure><img src="../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg" alt=""><figcaption></figcaption></figure>

3. **Masukkan nama domain** <mark style="color:red;">**tanpa**</mark>**&#x20;www** yang telah anda beli tadi.&#x20;

<figure><img src="../../../.gitbook/assets/ZCtFRdcw1oog2Y893cKW.jpg" alt=""><figcaption></figcaption></figure>

4. Apabila anda telah berjaya masukkan domain anda, paparan akan bertukar seperti di bawah :&#x20;

{% hint style="info" %} <mark style="color:red;">\*\*Perhatian</mark>: Jika **tiada isu**, sistem hanya akan mengambil masa **5-10 minit** untuk mengaktifkan domain anda. Jika domain anda masih tidak diaktifkan dalam tempoh masa ini, sila hubungi kami.
{% endhint %}

<figure><img src="../../../.gitbook/assets/OxA9xwgku7giuleysijh.jpg" alt=""><figcaption></figcaption></figure>

5. Sekiranya **Custom Domain** anda telah sedia dan boleh digunakan, paparan contoh seperti berikut akan keluar.&#x20;

{% hint style="success" %}
Perkataan **Connected** dan **SSL activated** akan menjadi <mark style="color:green;">**hijau**</mark> jika segala tetapan yang telah dilakukan adalah betul.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/X85NI3O093W3eevMgOSb.jpg" alt=""><figcaption></figcaption></figure>
