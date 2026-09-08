# Sendparcel Pro

{% hint style="success" %}
Fungsi ini tersedia untuk **plan Premium** dan **Ultimate** sahaja.
{% endhint %}

## Pada halaman ini:

* [Penetapan yang perlu dilakukan](sendparcel-pro.md#penetapan-yang-perlu-dilakukan)
* [Penetapan di Shoppego](sendparcel-pro.md#penetapan-di-shopppego)
* [Cara Fulfill Order](sendparcel-pro.md#cara-fulfill-order)

## Penetapan yang perlu dilakukan:

* Lengkapkan maklumat anda di dalam akaun Sendparcel Pro anda:
* Dapatkan **Client ID** akaun Sendparcel Pro anda
* Dapatkan **Client Secret** akaun Sendparcel Pro anda
* Dapatkan **Account Number** akaun Sendparcel Pro anda
* [Lakukan penetapan di dashboard Shoppego](sendparcel-pro.md#penetapan-di-shopppego)

{% hint style="warning" %}
**Kesemua maklumat dan penetapan diatas ini anda boleh dapatkan dengan berhubung dengan sales/akaun manager Sendparcel Pro anda.**
{% endhint %}

## Penetapan di Shopppego

Setelah anda mempunyai kesemua maklumat yang diperlukan untuk integration tersebut, anda boleh ikuti langkah dibawah untuk tetapkan ia di akaun Shoppego anda.

1. Log masuk akaun Shoppego anda.

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada **Shipping provider**

<figure><img src="../../../.gitbook/assets/ThCju4I3mPEWcQyXkxKW.jpg" alt=""><figcaption></figcaption></figure>

4. Klik **Edit/Activate** pada **shipping provider Sendparcel Pro**

<figure><img src="../../../.gitbook/assets/0ciGLDq1TILKsTwSjkkL.jpg" alt=""><figcaption></figcaption></figure>

5. Kemudian, anda boleh masukkan kesemua maklumat itu diruangan yang tersedia dan klik **Save**.

<table><thead><tr><th width="193">Ruang</th><th>Penerangan</th></tr></thead><tbody><tr><td><strong>Test mode</strong></td><td>Anda boleh aktifkan toggle ini sekiranya anda menggunakan akaun developer dari pihak Sendparcel Pro sendiri.</td></tr><tr><td><strong>Client ID</strong></td><td>Anda boleh masukkan <strong>Client ID</strong> untuk akaun Sendparcel Pro anda.</td></tr><tr><td><strong>Client Secret</strong></td><td>Anda boleh masukkan <strong>Client Secret</strong> untuk akaun Sendparcel Pro anda.</td></tr><tr><td><strong>Account Number</strong></td><td>Anda boleh masukkan <strong>Account Number</strong> untuk akaun Sendparcel Pro anda.</td></tr><tr><td><strong>Default Product Code</strong></td><td>Anda boleh lakukan pemilihan sama ada ingin gunakan untuk Pos Laju (standard domestic) atau International.</td></tr><tr><td><strong>Default HS Code (international)</strong></td><td>Anda boleh masukkan HS Code anda yang tersendiri untuk proses penghantaran international. Anda boleh biarkan kosong juga untuk menggunakan tetapan asal.</td></tr><tr><td><strong>Automatically add tracking</strong></td><td>Anda boleh aktifkan toggle ini sekiranya anda ingin sistem automatik hantar tracking number pada pelanggan melalui email(<strong>Khusus untuk bulk shipment sahaja</strong>).</td></tr><tr><td><strong>Enable content</strong></td><td>Anda boleh aktifkan toggle ini untuk pastikan details produk yang dibeli oleh pelanggan berada pada AWB order tersebut.</td></tr><tr><td><strong>Enable Sendparcel Pro</strong></td><td>Anda perlu aktifkan toggle ini untuk pastikan anda boleh gunakan shipping provider Sendparcel Pro ini.</td></tr></tbody></table>

<figure><img src="../../../.gitbook/assets/K3hgeuZVhBjP2q7kjjKL.jpg" alt=""><figcaption></figcaption></figure>

6. Setelah selesai kini proses penetapan shipping provider Sendparcel Pro anda kini sudah berjaya.

<figure><img src="../../../.gitbook/assets/vR4VRCS5SPd7dFxXgbr3.jpg" alt=""><figcaption></figcaption></figure>

## **Cara Fulfill Order**

Tutorial penetapan pada bahagian untuk cara urus order bagi menjana Airway Bill di platform Sendparcel Pro tanpa perlu log masuk dan hanya menggunakan platform Shoppego sahaja.

1. Log masuk ke **Dashboard Shoppego** -> **Orders** di panel kir&#x69;**.**&#x20;

![](../../../.gitbook/assets/lasUUilnpBxcaM16QKJd.png)

2. Pilih dan **klik** pada **order** yang anda ingin buat penghantaran menggunakan Sendparcel Pro dan paparan akan keluar seperti dibawah. Klik butang **Arrange shipment.**

![](../../../.gitbook/assets/8iFJZK2k86EUe0IDT4eN.jpg)

3. Tekan butang **Create Shipment** berwarna biru di sebelah penjuru kanan.

![](../../../.gitbook/assets/Q20cobeJSMXU7EOnh1kh.png)

4\. Seterusnya satu popup akan keluar, anda boleh klik pada **Select Shipment Provider** dan pilih **Sendparcel Pro.** Kemudian klik pada **Choose Services** dan klik pada mana-mana courier service yang anda mahu gun&#x61;**.** Harga telah ditentukan mengikut alamat yang ada pada order.&#x20;

![](../../../.gitbook/assets/oZXXIbKyIQsHtf6JuJvz.jpg)

5\. Seterusnya, klik pada method dan pilih **Dropoff** atau **Pickup.**

{% hint style="info" %}
**Method** :&#x20;

* **Dropoff -** Anda sendiri akan pergi ke pejabat pos berhampiran dan hantarkan barang.&#x20;
* **Pickup** - Pihak courier akan menghantar kenderaan untuk mengambil barang yang telah di pesan di alamat yang telah ditetapkan pada penetapan Location anda.
  {% endhint %}

![](../../../.gitbook/assets/wTGRlNTam3r29RWmGlca.jpg)

{% hint style="success" %}
Biasanya Method **Pickup** akan dipilih bagi memudahkan para penjual.&#x20;
{% endhint %}

6. Apabila **Method Pickup** dipilih, **jadual** akan dipaparkan untuk pilihan tarikh pengambilan oleh pihak courier. Klik pada tarikh yang anda mahukan dan kemudian klik butang **Submit**. Rujuk gambar dibawah.&#x20;

<figure><img src="../../../.gitbook/assets/UhifghyZRJbeh6yVDXDD.jpg" alt=""><figcaption></figcaption></figure>

7. Setelah klik butang **Submit**, order anda akan automatik mendapat tracking number seperti gambar dibawah.&#x20;

{% hint style="info" %}
Satu **Airwaybill (AWB)** terhadap order ini telah pun **dijana secara automatik** dan anda hanya perlu **cetak AWB ini.**
{% endhint %}

<figure><img src="../../../.gitbook/assets/lZqZ0pTSiJN89zcOj9mY.jpg" alt=""><figcaption></figcaption></figure>

Setelah proses **Add Shipment** dibuat, semak di dalam Dashboard Sendparcel Pro untuk pastikan maklumat yang dipaparkan adalah sama.&#x20;
