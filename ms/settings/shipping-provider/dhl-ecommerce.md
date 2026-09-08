# DHL eCommerce

{% hint style="success" %}
Fungsi ini tersedia untuk **plan Premium** dan **Ultimate** sahaja.
{% endhint %}

Untuk makluman, bagi penetapan integration ini, anda perlu mempunyai:

* API Client ID
* API Password
* PickUp Account
* SoldTo Account
* Prefix

{% hint style="warning" %}
**Kesemua maklumat diatas ini anda boleh dapatkan dengan berhubung dengan sales/akaun manager DHL eCommerce anda.**
{% endhint %}

Setelah anda mempunyai kesemua maklumat yang diperlukan untuk integration tersebut, anda boleh ikuti langkah dibawah untuk tetapkan ia di akaun Shoppego anda.

1. Log masuk akaun Shoppego anda.

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada **Shipping provider**

<figure><img src="../../../.gitbook/assets/ThCju4I3mPEWcQyXkxKW.jpg" alt=""><figcaption></figcaption></figure>

4. Klik **Edit/Activate** pada **shipping provider DHL eCommerce**

<figure><img src="../../../.gitbook/assets/PnMDhcgCH4IscSPpwZNq.jpg" alt=""><figcaption></figcaption></figure>

5. Kemudian, anda boleh masukkan kesemua maklumat itu diruangan yang tersedia dan klik **Save**.

<table><thead><tr><th width="193">Ruang</th><th>Penerangan</th></tr></thead><tbody><tr><td><strong>Test mode</strong></td><td>Nyahtanda penetapan ini untuk pastikan anda boleh gunakan shipping provider DHL eCommerce. Penetapan ini boleh digunakan jika anda ialah developer.</td></tr><tr><td><strong>API</strong> <strong>Client ID</strong></td><td>Anda boleh masukkan <strong>API</strong> <strong>Client ID</strong> yang anda sudah dapatkan dari sales/akaun manager DHL eCommerce anda.</td></tr><tr><td><strong>API</strong> <strong>Password</strong></td><td>Anda boleh masukkan <strong>API</strong> <strong>Password</strong> yang anda sudah dapatkan dari sales/akaun manager DHL eCommerce anda.</td></tr><tr><td><strong>Pickup Account</strong></td><td>Anda boleh masukkan <strong>Pickup Account</strong> yang anda sudah dapatkan dari sales/akaun manager DHL eCommerce anda.</td></tr><tr><td><strong>SoldTo Account</strong></td><td>Anda boleh masukkan <strong>SoldTo Account</strong> yang anda sudah dapatkan dari sales/akaun manager DHL eCommerce anda.</td></tr><tr><td><strong>Prefix</strong></td><td>Anda boleh masukkan <strong>Prefix</strong> yang anda sudah dapatkan dari sales/akaun manager DHL eCommerce anda.</td></tr><tr><td><strong>Automatically add tracking</strong></td><td>Anda boleh aktifkan toggle ini jika anda ingin pastikan setiap order yang diproses secara bulk untuk arrange shipment itu akan ditambah juga tracking number yang anda inginkan secara auto.(Pengguna Ultimate sahaja)</td></tr><tr><td><strong>Enable content</strong></td><td>Anda boleh aktifkan toggle ini untuk pastikan details produk yang dibeli oleh pelanggan berada pada AWB order tersebut.</td></tr><tr><td><strong>Enable DHL</strong></td><td>Anda perlu aktifkan toggle ini untuk pastikan anda boleh gunakan shipping provider DHL eCommerce ini.</td></tr></tbody></table>

<figure><img src="../../../.gitbook/assets/bnRv2eWM2dv0czqL9yVN.jpg" alt=""><figcaption></figcaption></figure>

6. Setelah selesai kini proses penetapan shipping provider DHL eCommerce anda kini sudah berjaya.

<figure><img src="../../../.gitbook/assets/mpgltTHtviN9qYw2KnW2.jpg" alt=""><figcaption></figcaption></figure>

## **Cara Fulfill Order**

Tutorial penetapan pada bahagian untuk cara urus order bagi menjana Airway Bill di platform DHL eCommerce tanpa perlu log masuk dan hanya menggunakan platform Commerce sahaja.

1. Log masuk ke **Dashboard Commerce** -> **Orders** di panel kir&#x69;**.**&#x20;

![](../../../.gitbook/assets/lasUUilnpBxcaM16QKJd.png)

2. Pilih dan **klik** pada **order** yang anda ingin buat penghantaran menggunakan DHL eCommerce dan paparan akan keluar seperti dibawah. Klik butang **Arrange shipment.**

![](../../../.gitbook/assets/8iFJZK2k86EUe0IDT4eN.jpg)

3. Tekan butang **Create Shipment** bewarna biru di sebelah penjuru kanan.

![](../../../.gitbook/assets/Q20cobeJSMXU7EOnh1kh.png)

4\. Seterusnya satu popup akan keluar, anda boleh klik pada **Select Shipment Provider** dan pilih **DHL.** Kemudian klik pada **Choose Services** dan klik pada mana-mana courier service yang anda mahu gun&#x61;**.** Harga telah ditentukan mengikut alamat yang ada pada order.&#x20;

![](../../../.gitbook/assets/96drwbnSDQkcPsy91YOy.jpg)

5\. Seterusnya klik pada method dan pilih **Dropoff** atau **Pickup.**

{% hint style="info" %}
**Method** :&#x20;

* **Dropoff -** Anda sendiri akan pergi ke pejabat pos berhampiran dan hantarkan barang.&#x20;
* **Pickup** - Pihak courier akan menghantar kenderaan untuk mengambil barang yang telah di pesan di alamat yang telah ditetapkan pada penetapan Location anda.
  {% endhint %}

![](../../../.gitbook/assets/cv7kAP0XV8qUIQ6BXiEr.jpg)

{% hint style="info" %}
**\*\*Nota** : Jika anda menggunakan penghantaran jenis **Cash On Delivery (COD)**, pastikan anda telah hidupkan toggle **Enable COD**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/MQYdA3lKbEiKCAvpNIFR.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Biasanya Method **Pickup** akan dipilih bagi memudahkan para penjual.&#x20;
{% endhint %}

6. Apabila **Method Pickup** dipilih, **jadual** akan dipaparkan untuk pilihan tarikh pengambilan oleh pihak courier. Klik pada tarikh yang anda mahukan dan kemudian klik butang **Submit**. Rujuk gambar dibawah.&#x20;

<figure><img src="../../../.gitbook/assets/ikzrL8TRgwBFXg3M6kzH.jpg" alt=""><figcaption></figcaption></figure>

7. Setelah klik butang **Submit**, order anda akan automatik mendapat tracking number seperti gambar dibawah.&#x20;

{% hint style="info" %}
Satu **Airwaybill (AWB)** terhadap order ini telah pun **dijana secara automatik** dan anda hanya perlu **cetak AWB ini.**
{% endhint %}

<figure><img src="../../../.gitbook/assets/qhraN9t9ccTred5oPIqz.jpg" alt=""><figcaption></figcaption></figure>

Setelah proses **Add Shipment** dibuat, semak di dalam Dashboard DHL untuk pastikan maklumat yang dipaparkan adalah sama.&#x20;
