# Page Builder

{% hint style="info" %}
Sebelum anda ikuti langkah penetapan ini pastikan anda:

* Sudah mempunyai **produk** yang anda ingin buat untuk **express cart**
* Sudah mempunyai **pages yang tersendiri** untuk anda masukkan fungsi **express cart**
* Sudah langgan plan **Shoppego&#x20;**<mark style="color:red;">**Standard**</mark>**&#x20;ke-atas** untuk anda menggunakan fungsi page builder.
  {% endhint %}

## Dapatkan Produk ID

1\. Log masuk ke akaun Shoppego anda

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Products**

![](../../.gitbook/assets/3QYpKlTI5mdyrdLeiYts.jpg)

3\. Klik pada Produk yang anda ingin masukkan fungsi Express Checkout tersebut.

![](../../.gitbook/assets/i3S3XPC8L5SjJS1W4hLs.jpg)

4\. Klik pada **Express checkout**

![](../../.gitbook/assets/bqs406u5zwylQ0lJnPQ6.jpg)

5\. Pilih variant yang anda ingin customer anda terus beli dan simpan link tersebut

![](../../.gitbook/assets/iA6m613XvwBy9vep3yLN.jpg)

6\. Berdasarkan link url tersebut anda hanya perlu simpan produk variant ID nya sahaja. Sebagai contoh link yang anda dapat ialah **<https://mirfaith.myshoppegram.com/cart/57085:1>**

Jadi anda perlu simpan **57085** sahaja untuk digunakan pada langkah seterusnya.

## **Penetapan pada Page Builder**

1\. Log masuk akaun Shoppego anda&#x20;

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Klik pada **Online Store** -> **Pages**

![](../../.gitbook/assets/YW5MKHAFthkHAX6ApmOw.jpg)

3\. Klik pada butang **Edit** pada pages yang anda ingin masukkan fungsi Express Checkout tersebut.

![](../../.gitbook/assets/E1metuuRouovYFNz12pX.png)

4\. Klik pada **Edit with Builder**

![](../../.gitbook/assets/6Ciuq7MNuHo6Vk382w6t.png)

5\. Seterusnya, anda akan dibawa ke halaman page builder anda. Untuk penetapan express checkout tersebut, anda boleh **drag** **element Button** tersebut **ke ruangan yang disediakan**.

![](../../.gitbook/assets/-MCtu97i3dGXrIXrW7bZ.png)

![](../../.gitbook/assets/-MUMbvfcKeFEwZTkkOtu.png)

6\. Klik pada **element Button** tersebut yang anda baru lepas drag dan masukkan ke dalam body content anda. Taip teks yang anda inginkan supaya terpapar pada element Button tersebut.

![](../../.gitbook/assets/-MUMbvfcKeFEwZTkkOtu.png)

7\. Dibahagian URL anda boleh masukkan /cart/**add?id**=**masukkan ID yang anda dapatkan pada langkah 1 .**

{% hint style="info" %}
\*\*<mark style="color:red;">**Perhatian**</mark> : Pastikan anda masukkan **add?id=** pada URL anda.
{% endhint %}

(Contoh: [https://mirfaith.myshoppegram.com/cart/add?id=57085](https://mirfaith.myshoppegram.com/cart/57085:1))

8\. Pada ruangan **Target** anda boleh pilih option **Same Tab** manakala, pada ruangan setting lain anda boleh setting mengikut design anda.

9\. Setelah selesai anda boleh klik **Preview** untuk lakukan percubaan bagi penetapan button tersebut.

![](../../.gitbook/assets/-MUMcBoPZtIWDpZnnO1W.jpg)

## Info Tambahan

Jika anda ingin membuat pelanggan anda terus masukkan 3 produk terus kedalam cart mereka anda boleh asingkan setiap produk variant ID dengan simbol koma.\
\
Sebagai contoh : /cart/**add?id=57085,12345**

{% hint style="info" %}
**\*\*Maksimum hanya&#x20;**<mark style="color:red;">**3 variant ID**</mark>**&#x20;sahaja boleh dimasukkan.**

\*\*Jika anda ingin menambah **kuantiti dalam Express Cart** anda, pastikan anda ubah dan **tekan butang Update Cart.**
{% endhint %}
