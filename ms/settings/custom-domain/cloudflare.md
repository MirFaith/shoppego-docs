# Cloudflare

{% hint style="warning" %}
Untuk tutorial ni adalah bagi mereka yang <mark style="color:red;">**menghadapi masalah**</mark> terhadap penggunaan DNS oleh domain provider.&#x20;
{% endhint %}

Setiap domain yang dibeli terdapat satu bahagian yang dinamakan Nameserver untuk kita beri akses kepada platform seperti Cloudflare bagi menguruskan DNS kita.

**Bermula 26 Februari 2026 setiap pengguna Shoppego hanya perlu lakukan CNAME record sahaja dan setiap store/website akan mempunyai value/penetapan CNAME record yang sama.**

## Domain Migration

{% embed url="<https://www.youtube.com/watch?v=LiehNct34GU>" %}

## **Bahagian 1 :** Nilai CNAME Record <a href="cloudflare.md#cloudflare-a-cname" id="cloudflare-a-cname"></a>

1\. Anda boleh log masuk kedalam **Dashboard Shoppego**

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Settings**

![](../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Klik pada **Custom domain**

![](../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg)

4\. Klik pada **Add existing domain**

![](../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg)

5\. Nanti anda akan dapat lihat popup yang mempunyai **value untuk CNAME record anda**.

{% hint style="info" %}
**Penetapan CNAME di dalam domain provider.**

**1 :** Jika **nilai CNAME** adalah **@**, masukkan **nama domain anda** atau "**@**" didalam **ruang CNAME** dalam domain provider.
{% endhint %}

![](../../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg)

## **Bahagian 2 : Pendaftaran Cloudlflare**

{% hint style="warning" %}
Untuk tutorial ni adalah bagi mereka yang menghadapi <mark style="color:red;">**masalah terhadap penggunaan DNS**</mark> oleh domain provider.&#x20;
{% endhint %}

Setiap domain yang dibeli terdapat satu bahagian yang dinamakan **Nameserver** untuk kita beri akses kepada platform seperti **Cloudflare** bagi menguruskan DNS kita.

1. Pergi ke link berikut <https://dash.cloudflare.com/sign-up>. Masukkan **email** dan **password** untuk pendaftaran dan klik **Create Account.**

![](../../../.gitbook/assets/-MBgEp0MNxilcHx3mufb.png)

2. Masukkan nama domain anda yang telah dibeli dari domain provider. Selepas itu klik **Add Site**

{% hint style="info" %}
Pada bahagian ini, anda perlu **masukkan nama domain&#x20;**<mark style="color:red;">**tanpa www**</mark>.
{% endhint %}

![](../../../.gitbook/assets/-MBgEztcg5pkhZMqJLcz.png)

3. Seterusnya klik pada **Free Plan** dan klik **Confirm Plan**

![](../../../.gitbook/assets/-MBgF5Aa3tOvBNTmSYZP.png)

## **Bahagian 3 : DNS Setup**

1. Tunggu sehingga paparan seperti gambar di bawah keluar.&#x20;

![](../../../.gitbook/assets/-MBgFDbSwXka2QlmBG_6.png)

{% hint style="warning" %}
Sekiranya terdapat **sebarang DNS record**, yang berlainan seperti penetapan dibawah anda boleh <mark style="color:red;">**padam semua record**</mark> tersebut dan rujuk semula penetapan dibawah.&#x20;
{% endhint %}

{% hint style="info" %}
Sekiranya value DNS record tersebut sama sahaja seperti paparan dibawah, anda boleh abaikan sahaja penetapan dibawah.&#x20;
{% endhint %}

### 1 : Penetapan CNAME record:&#x20;

1. Penetapan CNAME **record**, anda boleh **pilih dropdown CNAME** dan masukkan maklumat ada ruangan tersebut masukkan :&#x20;

   * **Type** : CNAME
   * **Name** : @&#x20;
   * **Target** : shops.shoppego.my
   * **Proxy Status** : DNS Only  (\*\*<mark style="color:red;">**Perhatian**</mark> : Pastikan **ikon awan** berwarna **kelabu**)
   * **TTL** : Automatik / 1 Jam

   Setelah selesai, tekang butang **Save**.

<figure><img src="../../../.gitbook/assets/mNlxA464L0smlicsevum.jpg" alt=""><figcaption></figcaption></figure>

### 2 : Penetapan CNAME Record www(tidak diwajibkan):&#x20;

2. Penetapan **CNAME Record**, anda boleh **pilih dropdown CNAME** masukkan maklumat ada ruangan tersebut masukkan :

   * **Type** : CNAME
   * **Name** : www
   * **Target** : shops.shoppego.my
   * **Proxy Status** : [DNS Only  (\*\*<mark style="color:red;">**Perhatian**</mark> : Pastikan **ikon awan** berwarna **kelabu**)](cloudflare.md#user-content-fn-1)[^1]
   * **TTL** : Automatik / 1 Jam

   Setelah selesai, tekang butang **Save**.

<figure><img src="../../../.gitbook/assets/hBSR4A7HCaF3zdIekBPM.jpg" alt=""><figcaption></figcaption></figure>

3. Apabila anda selesai membuat penetapan, paparan yang anda akan terima adalah seperti dibawah :&#x20;

<figure><img src="../../../.gitbook/assets/yStptMJ58g0yUSs0fFOK.jpg" alt=""><figcaption></figcaption></figure>

### 3 : Penetapan Nameserver Cloudflare

1. Seterusnya pada ruangan **Proxy Status** ada ikon awan **Oren (Proxied)**.&#x20;

{% hint style="info" %}
Klik pada ikon tersebut dan tukar kepada warna **kelabu (DNS Only)** dan klik **Save**. Lakukan untuk **A Record** dan **CNAME Record**.&#x20;
{% endhint %}

2. Kemudian klik **Continue.**

![](../../../.gitbook/assets/UUl8yaeI0Y7VnJeCLT5f.jpg)

3. Selepas klik **Continue**, paparan seperti dibawah akan keluar. Klik **Continue with default.**

![](../../../.gitbook/assets/-MBgGlP1I5Hv2Sgu0F3-.png)

4. Maka akan keluar nameserver dari Cloudflare yang anda boleh gunakan di domain name provider anda. &#x20;

![](../../../.gitbook/assets/-MBgGu_CN5uBJ3P4FM0w.png)

5. Log masuk ke **akaun domain name provider anda** dan **padam nameserver di domain provider anda**. <mark style="color:blue;">**Gantikan dengan Nameserver Cloudflare**</mark> yang telah diberikan seperti gambar di bawah&#x20;

![](../../../.gitbook/assets/-MBgH67YbqzybYIynZiW.png)

6. Setelah anda gantikan nameservers tersebut klik butang **Done, check nameservers.**&#x20;

{% hint style="info" %}
Sekiranya **anda mengalami sebarang isu** untuk penukaran nameserver ini, anda boleh **hubungi pihak domain provider** untuk mereka bantu anda dalam lakukan penetapan ini.
{% endhint %}

[^1]:
