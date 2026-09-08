# Configuration Error

Anda mempunyai **isu data Purchase** pada akaun ads manager <mark style="color:red;">**tidak sama**</mark> dengan **order sebenar** di website?

## **Ada 2 sebab utama ralat ini boleh berlaku.**

### 1. Salah track data

![](../../../../../.gitbook/assets/-MBgA-voeVehpOQLt5NS.jpg)

Ramai yang gunakan **Purchase Count** dalam ads manager untuk **track purchase**. Sebenarnya cara ni <mark style="color:red;">**kurang tepat**</mark>.&#x20;

Untuk dapatkan **data purchase yang tepat** pada ads manager, anda kena gunakan **UNIQUE purchase data**. Unique bermaksud, FB hanya akan ambil data dari purchaser yang **IP address unik sahaja.** Jika pelanggan *refresh* banyak kali Thank You Page, events **Unique Purchase** masih lagi dikira **sekali sahaja** kerana dari **alamat IP/orang yang sama.**

### 2. Pixel bermasalah

![](../../../../../.gitbook/assets/-MBgBl2VF_xhMrUT0rVf.jpg)

Masih ramai lagi yang <mark style="color:red;">**tersalah install**</mark> atau <mark style="color:red;">**salah setup**</mark>**&#x20;Facebook Pixel** dengan betul. Macam mana nak troubleshoot? &#x20;

* Pergi events **manager pixel**, **test events**. Masukkan **URL website**. Jalankan satu persatu **standard event** dari **masuk homepage, add to cart / initiate checkout** hinggalah ke **purchase**. Sekiranya **semua event detected dengan normal**. Pixel anda <mark style="color:blue;">**OK**</mark>.&#x20;

## Situasi Facebook Pixel Bermasalah

**Situasi** : Standard events **trigger lebih dari sekali / duplicated?**

* Sekiranya berlaku isu begini, check pada **Pixel settings** -> **Event Setup** -> Pastikan anda **OFF "Track events automatically without code"**&#x20;

Ini adalah <mark style="color:red;">**setting yang menyebabkan isu data yang berlebihan**</mark> iaitu purchase dalam ads manager lagi banyak dari purchase sebenar dan ia akan **menggangu code original** untuk **track standard events.**

{% hint style="info" %}
**Pro tips:** Jika ingin test Pixel dengan chrome extension [**pixel helper**](https://chrome.google.com/webstore/detail/facebook-pixel-helper/fdgfkebogiimcoedlicjlajpkdmockpc?utm_source=chrome-ntp-icon)**,** pastikan anda <mark style="color:red;">**Disabled AdBlocker**</mark>**&#x20;(jika ada).**
{% endhint %}

## Troubleshoot Facebook Pixel

Jika anda mempunyai **masalah berkenaan dengan Facebook Pixel anda** dimana **data** anda <mark style="color:red;">**tidak selaras (tally)**</mark>, anda boleh rujuk pada link tutorial untuk lakukan troubleshoot:

<https://my.shoppego.com/courses/facebook-ads-essentials-2024/116>
