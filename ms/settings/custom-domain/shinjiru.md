# Shinjiru

Terdapat 3 bahagian untuk lakukan penetapan ini:

* **Bahagian 1** : Dapatkan value untuk CNAME record
* **Bahagian 2** : Penetapan di Shinjiru
* **Bahagian 3** : Penetapan di Shoppego

{% hint style="warning" %}
Pastikan **domain anda sudah dibeli dan sudah boleh digunakan untuk setup**. Jika anda **membeli domain ".com", anda boleh terus ikut tutorial ini**.&#x20;
{% endhint %}

Jika **domain Malaysia** seperti **".my, .com.my, .net.my"** anda perlu lakukan penetapan **DNS records** ini didalam akaun **MYNIC** anda yang tersendiri atau anda boleh hubungi pihak **domain provider** anda untuk lakukan penetapan tersebut.

**Bermula 26 Februari 2026 setiap pengguna Shoppego hanya perlu lakukan CNAME record sahaja dan setiap store/website akan mempunyai value/penetapan CNAME record yang sama.**

## **Bahagian 1 :** Nilai CNAME Record <a href="shinjiru.md#a-dan-cname" id="a-dan-cname"></a>

1\. Anda boleh log masuk kedalam dashboard Shoppego

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Settings**

![](../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Klik pada **Custom domain.**

![](../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg)

4\. Klik pada **Add existing domain.**

![](../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg)

5\. Nanti anda akan dapat lihat paparan yang mempunyai **value untuk CNAME record anda**.

{% hint style="info" %}
**Penetapan CNAME di dalam domain provider.**

**1 :** Jika **nilai CNAME** adalah **@**, masukkan **nama domain anda** atau "**@**" didalam **ruang CNAME** dalam domain provider.
{% endhint %}

![](../../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg)

{% hint style="info" %}
Anda perlu **simpan Value** untuk **CNAME record** tersebut untuk anda masukkan didalam **DNS record domain** anda didalam sistem domain provider nanti.
{% endhint %}

## Bahagian 2 : Penetapan Shinjiru

1\. Log masuk ke dalam akaun Shinjiru anda dan klik pada **Domain** -> **Manage DNS**

<figure><img src="../../../.gitbook/assets/PH5Vxd4M4X89rPXMJXqx.jpg" alt=""><figcaption></figcaption></figure>

2\. Dalam halaman **Manage DNS**, klik butang **Add Record**

<figure><img src="../../../.gitbook/assets/9S6zRlCJZe31rl2dp9EB.jpg" alt=""><figcaption></figcaption></figure>

3. Satu paparan akan keluar untuk anda lakukan penetapan bagi **CNAME Record** dalam bahagian ini.

<figure><img src="../../../.gitbook/assets/vZKVwsRYX0ofGJw6hzfe.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Sekiranya domain provider anda ini tidak boleh lakukan penetapan CNAME record untuk host ke main domain atau @ anda boleh lakukan pemindahan pengurusan DNS ke sistem Cloudflare. Boleh rujuk di link ini untuk contoh penetapan:** [**https://docs.shoppego.com/ms/settings/custom-domain/cloudflare**](cloudflare.md)
{% endhint %}

### 1 : Penetapan CNAME Record

1. Penetapan CNAME Record :&#x20;
   * **Type** : **CNAME**
   * **Name** : **@** atau nama domain anda
   * **TTL** : **Default**
   * **CNAME** : **shops.shoppego.my**
2. Penetapan CNAME Record www (tidak diwajibkan):&#x20;
   * **Type** : **CNAME**
   * **Name** : **www**
   * **TTL** : **Default**
   * **CNAME** : **shops.shoppego.my**

Setelah selesai membuat kedua-dua penetapan, paparan yang keluar adalah seperti dibawah :&#x20;

<figure><img src="../../../.gitbook/assets/oPVekZi2rIncv3QbbXFN.jpg" alt=""><figcaption></figcaption></figure>

Proses untuk domain siap sedia untuk dimasukkan pada website anda mengambil masa lebih kurang **12 - 48 jam.**

{% hint style="info" %}
Sekiranya **anda mengalami sebarang isu** untuk penetapan DNS record ini, anda boleh **hubungi pihak domain provider** untuk mereka bantu anda dalam lakukan penetapan ini.
{% endhint %}

## **Info Tambahan**

Bagi memastikan DNS anda telah dituju ke Shoppego anda boleh [Semak DNS anda Disini](https://www.whatsmydns.net/) dan pastikan DNS yang terpapar ialah **penetapan yang anda telah tetapkan**

Bagi menyemak DNS anda:

1. Anda boleh klik Link ini : [Semak DNS anda Disini](https://www.whatsmydns.net/) atau <https://www.whatsmydns.net/>

{% hint style="info" %}
Anda boleh **masukkan nama domain anda** (**beserta www** dan tanpa www) ke dalam ruangan yang disediakan. Pastikan anda telah lakukan perubahan kepada semakan CNAME record.
{% endhint %}

<figure><img src="../../../.gitbook/assets/CrQgoaGRS5ABXprQaxE5.jpg" alt=""><figcaption></figcaption></figure>

### Tempoh propagation

Anda hanya perlu <mark style="color:red;">**tunggu dalam tempoh 48 jam**</mark> untuk penetapan tersebut dapat dibaca dan domain anda boleh digunakan sebelum anda lakukan penetapan Custom domain di Shoppego.

**Tempoh paling cepat** domain anda boleh digunakan ialah **dalam 1 jam**. Jika tidak, anda perlu tunggu dalam <mark style="color:red;">**tempoh 48 jam hingga ke 72 jam**</mark> tersebut.

Anda boleh semak status propagation domain anda melalui link yang telah kami berikan (<https://www.whatsmydns.net/>)

## Bahagian 3 : Penetapan di Shoppego

1. Pada Dashboard Shoppego, anda boleh tekan **Settings (1)** dan skrol ke bawah sehingga ke **Custom Domain (2).**

<figure><img src="../../../.gitbook/assets/AzF4kys3LWOBaSYI3mZj.jpg" alt=""><figcaption></figcaption></figure>

2. Selepas itu, tekan **Add Existing Domain**.

<figure><img src="../../../.gitbook/assets/NfXmp5IicyVtewuJQs0q.jpg" alt=""><figcaption></figcaption></figure>

3. **Masukkan nama domain** <mark style="color:red;">**tanpa**</mark>**&#x20;www** yang telah anda beli tadi.

<figure><img src="../../../.gitbook/assets/UPhvCF3QjYfSJPKdK5dJ.jpg" alt=""><figcaption></figcaption></figure>

4. Apabila anda telah berjaya masukkan domain anda, paparan akan bertukar seperti di bawah :&#x20;

{% hint style="info" %} <mark style="color:red;">\*\*Perhatian</mark>: Jika **tiada isu**, sistem hanya akan mengambil masa **5-10 minit** untuk mengaktifkan domain anda. Jika domain anda masih tidak diaktifkan dalam tempoh masa ini, sila hubungi kami.
{% endhint %}

<figure><img src="../../../.gitbook/assets/OxA9xwgku7giuleysijh.jpg" alt=""><figcaption></figcaption></figure>

5. Sekiranya **Custom Domain** anda telah sedia dan boleh digunakan, paparan contoh seperti berikut akan keluar.&#x20;

{% hint style="success" %}
Perkataan **Connected** dan **SSL activated** akan menjadi <mark style="color:green;">**hijau**</mark>. Keadaan ini hanya akan berlaku jika segala tetapan yang telah dilakukan adalah betul.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/X85NI3O093W3eevMgOSb.jpg" alt=""><figcaption></figcaption></figure>

Untuk sistem pengurusan DNS yang lebih stabil kami galakkan pengguna kami menggunakan Cloudflare. Untuk contoh penetapan boleh rujuk di link ini:

{% content-ref url="cloudflare.md" %}
[Cloudflare](cloudflare.md)
{% endcontent-ref %}

Sekiranya anda sudah menggunakan Nameserver dari pihak Cloudflare itu, anda boleh rujuk contoh penetapan di link ini untuk penukaran Nameserver tersebut:

{% content-ref url="shinjiru/penukaran-nameserver.md" %}
[Penukaran Nameserver](shinjiru/penukaran-nameserver.md)
{% endcontent-ref %}
