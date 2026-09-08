# Page Builder

Sebelum anda ikuti langkah penetapan ini pastikan anda:

* Sudah **mempunyai produk** yang anda ingin buat untuk **express checkout.**
* Sudah **mempunyai pages yang tersendiri** untuk anda masukkan **fungsi express checkout.**
* Sudah **langgan plan Shoppego&#x20;**<mark style="color:red;">**Standard**</mark>**&#x20;ke-atas.**

## Dapatkan Produk ID

1. Log masuk ke akaun Shoppego anda

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2. Klik pada **Products**

![](../../.gitbook/assets/3QYpKlTI5mdyrdLeiYts.jpg)

3\. Klik pada Produk yang anda ingin masukkan fungsi Express Checkout tersebut.

![](../../.gitbook/assets/i3S3XPC8L5SjJS1W4hLs.jpg)

4\. Klik pada **Express checkout**

![](../../.gitbook/assets/bqs406u5zwylQ0lJnPQ6.jpg)

5\. Pilih variant yang anda ingin customer anda terus beli dan simpan link tersebut

![](../../.gitbook/assets/iA6m613XvwBy9vep3yLN.jpg)

6\. Pastikan anda simpan terlebih dahulu URL link tersebut kerana ia akan digunakan untuk penetapan pada page builder anda.&#x20;

## **Penetapan pada Page Builder**

1\. Log masuk akaun Shoppego anda

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Online Store** -> **Pages**

![](../../.gitbook/assets/YW5MKHAFthkHAX6ApmOw.jpg)

3\. Klik pada butang **Edit** pada pages yang anda ingin masukkan fungsi Express Checkout tersebut.

![](../../.gitbook/assets/E1metuuRouovYFNz12pX.png)

4\. Klik pada **Edit with Builder**

![](../../.gitbook/assets/6Ciuq7MNuHo6Vk382w6t.png)

5\. Seterusnya, anda akan dibawa ke halaman page builder anda. Untuk penetapan express checkout tersebut, anda boleh **drag** **element Button** tersebut **ke ruangan yang disediakan**.

![](../../.gitbook/assets/-MCtu97i3dGXrIXrW7bZ.png)

![](../../.gitbook/assets/-MCtwYtM8tMRsG7tT1j4.png)

6\. Klik pada **element Button** tersebut yang anda baru lepas drag dan masukkan ke dalam body content anda. Taip text yang anda inginkan supaya terpapar pada element Button tersebut.

![](../../.gitbook/assets/-MCtuWxn71xRmG15Uzxb.png)

7\. Dibahagian URL anda boleh masukkan **Url yang anda baru dapatkan dari langkah 1**&#x20;

(Contoh: <https://mirfaith.myshoppegram.com/cart/57085:1>)

8\. Pada **ruangan Target** anda boleh pilih option **Same Tab** atau **New Tab** manakala, pada ruangan setting lain anda boleh setting mengikut design anda.

9\. Setelah selesai anda boleh klik **Preview** untuk test button tersebut.

![](../../.gitbook/assets/-MIRwulSdjAgIV067RsI.jpg)

## Info Tambahan

### Checkout 3 Produk

1. Jika anda ingin membuat pelanggan anda **terus checkout** dengan **3 produk terus**, anda boleh **asingkan setiap produk variant ID** dengan **simbol koma**.\
   \
   **Sebagai contoh** : /cart/**57085:**<mark style="color:blue;">**1**</mark>**,12345:**<mark style="color:blue;">**2**</mark>**,57779:**<mark style="color:blue;">**3**</mark>

### Kod Diskaun

1. Jika anda ingin pastikan **pelanggan checkout automatik sekali dengan diskaun kod yang anda inginkan**, anda boleh **lakukan penambahan ?discount=\[Kod diskaun anda]** pada URL express checkout anda.\
   \
   Sebagai contoh kod diskaun anda ialah "**FREESHIPPING**":\
   /cart/57085:1,12345:2,57779:3<mark style="color:blue;">**?discount=FREESHIPPING**</mark>

{% hint style="info" %}
**\*\*Maksimum hanya&#x20;**<mark style="color:red;">**3 variant ID(yang valid)**</mark> sahaja yang boleh dibaca oleh sistem kami.

\*\* **Nombor selepas&#x20;**<mark style="color:red;">**titik bertindih**</mark> tersebut merujuk kepada <mark style="color:blue;">**quantity barang yang dibeli**</mark>.&#x20;
{% endhint %}
