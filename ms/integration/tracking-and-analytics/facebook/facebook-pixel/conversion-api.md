---
description: "Tutorial konfigurasi Conversion API"
---

# Conversion API

Didalam Shoppego anda boleh membuat penetapan **Conversion API** pada **FB Pixel** anda. Dengan Conversion API ini, data yang anda akan terima melalui **FB Pixel** anda akan <mark style="color:blue;">**lebih tepat**</mark>.

{% hint style="info" %}
\*\*<mark style="color:red;">**Perhatian**</mark> : Untuk menggunakan **fungsi Conversion API** ini, ianya hanya terdapat pada **plan&#x20;**<mark style="color:red;">**Ultimate**</mark> sahaja.
{% endhint %}

{% embed url="<https://youtu.be/dLYwf_YcwGA>" %}

## **Dapatkan Access Token**

Untuk penetapan Facebook Conversion API, anda hanya perlu masukkan sahaja **token Conversion API** pada platform Shoppego. Sangat mudah!

1. Pada bahagian pixels anda, pilih pixels yang anda ingin gunakan klik pada tab **Open in Events Manager**

![](../../../../../.gitbook/assets/FSiHXv4nvG5lncAv6Hvp.png)

2\. Seterusnya , anda akan di bawa kepada satu laman baru. Pada laman ini klik pada tab **Settings**

![](../../../../../.gitbook/assets/ivucXpjKSWqlbRZ90J3p.png)

3\. Pada tab settings , tekan **Get Started** pada ruangan **Set up Manually.**&#x20;

{% hint style="info" %}
**\*\***<mark style="color:red;">**Perhatian**</mark>**:** Jika button tidak boleh ditekan pastikan email anda telah diset pada Ads Manager.\*
{% endhint %}

![](../../../../../.gitbook/assets/4xpNvfEB57R50vfJVEFR.png)

4\. Klik **Continue**

![](../../../../../.gitbook/assets/IJAzmm5MQRmDIgucPpuk.png)

5\. Tick pada event **Purchase** dan **Initiate checkout or Leads**. Setelah anda tick kedua-dua events tersebut anda boleh klik **Continue**

{% hint style="info" %}
Untuk laman web yang menggunakan fungsi pembelian, adalah disyorkan agar anda menggunakan event "Purchase" dan "Initiate checkout". Untuk laman web yang hanya menggunakan fungsi "Borang/Forms", adalah disyorkan agar anda menggunakan event "Leads".
{% endhint %}

![](../../../../../.gitbook/assets/ZrcIahwPbnHNOIVUStWl.png)

6\. Pastikan **penetapan event details untuk event Initiate Checkout anda adalah sama seperti gambar dibawah**. Setelah anda pastikan ianya sama, anda boleh klik pada butang **Continue**

{% hint style="info" %}
Untuk event "Leads", anda masih boleh mengikuti semua parameter.
{% endhint %}

![](../../../../../.gitbook/assets/pU0rWUpX4K7jS5oXCswQ.jpg)

7\. Seterusnya, untuk **penetapan event details bagi event Purchase pula adalah seperti gambar dibawah**. Setelah anda pastikan ianya sama, anda boleh klik **Continue**

![](../../../../../.gitbook/assets/xpFlA5F84j1RYKmbfvxp.jpg)

8\. Pada halaman ini, anda boleh pastikan ianya sama terpapar seperti pada paparan penetapan anda. Setelah anda pastikan ianya sama anda boleh klik **Continue**

![](../../../../../.gitbook/assets/4loA0sQeqIbxXPpcEawf.jpg)

9\. Tekan **Finish** dan maka dengan itu penetapan anda telah selesai.

![](../../../../../.gitbook/assets/KVU2ciTEpaRxQ4sxm09Z.png)

10\. Seterusnya, anda boleh klik semula pada tab **Settings**

![](../../../../../.gitbook/assets/ivucXpjKSWqlbRZ90J3p.png)

11\.  Dapatkan token untuk conversion API anda dengan menekan **Generate access token. Anda perlu simpan access token ini untuk penetapan didalam Shoppego.**

![](../../../../../.gitbook/assets/vl1PzDKHyLE2JCoX8yGA.png)

## **Penetapan di Shoppego**

Setelah anda mendapatkan access token Conversion API. Anda dikehendaki untuk memasukkan access token tersebut ke dalam akaun Shoppego anda.

1. Log masuk pada akaun Shoppego. Klik pada **Settings** -> **General**. **Masukkan access token** anda pada **ruangan Facebook Pixel Access Token** dan klik butang **Save**

![](../../../../../.gitbook/assets/btd9gZu6SW0PSXTjCt4C.jpg)

## Lakukan Test event pada penetapan

1\. Pada bahagian pixels anda, pilih pixels yang anda ingin gunakan klik pada tab **Open in** **Events Manager**

![](../../../../../.gitbook/assets/FSiHXv4nvG5lncAv6Hvp.png)

2\. Seterusnya , anda akan di bawa kepada satu laman baru. Pada laman ini klik pada tab **Test events**

![](../../../../../.gitbook/assets/Z5hGY7uYJKKkn8HvLgf2.png)

3\. Pada ruangan tab **Test server event** anda boleh **simpan Test event code anda dengan klik pada kotak test code anda**.&#x20;

![](../../../../../.gitbook/assets/cEAeSdvw3gffJFfeLDen.png)

4\. Seterusnya, anda perlu masukkan **code ini** pada penetapan didalam **Shoppego**. Anda perlu Log masuk semula kedalam akaun Shoppego anda.

![](../../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

5\. Klik pada **Online store** -> **Preferences**. Letakkan **Test event code** anda pada **ruangan Facebook test\_event\_code** dan klik butang **Save**

![](../../../../../.gitbook/assets/LIGt5QICVDtt1z6hg2H5.jpg)

6\. Seterusnya , anda perlu kembali kepada **Test Events** dan masukkan domain store anda pada **Test browser events**. Setelah selesai klik pada butang **Open Website**.

![](../../../../../.gitbook/assets/pF07CTTqfRXeGRLcHIBa.png)

Setelah anda klik **butang tersebut** , anda akan dibawa ke **halaman website anda**. Anda boleh **refresh terlebih** dahulu untuk memastikan **event page view dapat di-trigger** pada penetapan test event anda. Jika **ianya dapat ditrigger** anda boleh meneruskan untuk **proses trigger event yang lain.**

Jika penetapan anda berjaya , pada test event anda akan menerima **events** **Initiate checkout** dan **Purchase** beserta maklumat **deduplication yang datang dari Server**.

![](../../../../../.gitbook/assets/vGpe8jLJQjSP4AVM7djC.jpg)

{% hint style="info" %}
**\*\*Setelah anda selesai membuat penetapan test event ini. Anda perlu&#x20;**<mark style="color:red;">**delete facebook test event code**</mark>**&#x20;pada penetapan Shoppego anda.\*\***
{% endhint %}
