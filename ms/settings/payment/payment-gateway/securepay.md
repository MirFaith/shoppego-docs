# Securepay

## Pendaftaran akaun Securepay

Klik di link ini <https://securepay.my/p/6WSC78CY> untuk mula daftar **akaun Securepay** anda. Bagi proses **pendaftaran akaun Securepay.**&#x20;

{% hint style="success" %}
Anda perlu pastikan anda sudah:

* Mempunyai SSM&#x20;
* Akaun Bank Syarikat
  {% endhint %}

{% hint style="info" %}
**Urusan pengesahan akaun, caj dan wang transaksi** adalah **diuruskan sepenuhnya oleh pihak Securepay**.
{% endhint %}

## Dapatkan Key yang diperlukan dari akaun Securepay

Untuk menghubungkan Securepay dengan website Shoppego, anda memerlukan beberapa key untuk proses pengesahan. Antara key yang diperlukan ialah **UID,** **Authentication token** dan **Checksum token**.&#x20;

Untuk memulakan proses penetapan payment gateway Securepay anda boleh ikut langkah penetapan ini :

1\. Log masuk ke akaun **Securepay** anda.

![](../../../../.gitbook/assets/-MKIL8PF0XYBCP7z8ODW.png)

2\. Seterusnya pada bahagian Dashboard Securepay, anda boleh klik pada Tab **< > API**

![](../../../../.gitbook/assets/-MKILd35viKvwnqraIkt.png)

3\. Seterusnya anda akan dapat lihat API anda disitu anda boleh klik pada text **Default** tersebut

![](../../../../.gitbook/assets/-MKIMQYMP59yw6pGKVI2.jpg)

4\. Setelah anda klik pada API default tersebut anda akan jumpa ketiga-tiga key yang anda perlukan untuk penetapan payment gateway Securepay anda.

![](../../../../.gitbook/assets/-MKIMwfRNN8SSRBFuje-.jpg)

Anda boleh simpan ketiga-tiga key tersebut untuk kegunaan di langkah seterusnya. Key yang anda perlu simpan ialah :

* **UID**
* **Authentication token**
* **Checksum token**

6\. Setelah selesai mencipta API securepay. Klik show button pada API anda **"kotak berwarna merah"**.&#x20;

![](../../../../.gitbook/assets/-Ml9DaULiJUESU00BClH.jpg)

7\. Tekan pada butang **EDIT** di atas.

![](../../../../.gitbook/assets/-Ml9ECKi3mrfy9968D-a.jpg)

8\. Tick pada checkbox **FPX B2B1** dan tekan butang **UPDATE**

![](../../../../.gitbook/assets/-Ml9F8N-phm-t6PZcIhh.jpg)

9\. . Pastikan **FPX B2B1** memaparkan status **YES**

![](../../../../.gitbook/assets/-Ml9GTmdU0YtPBNzC5_P.jpg)

## **Penetapan di Shoppego**

Untuk proses penetapan payment gateway Securepay di Shoppego anda perlu aktifkan terlebih dahulu payment gateway tersebut dan masukkan ketiga-tiga key tersebut kedalam setting payment gateway anda. Untuk memulakan penetapan payment gateway tersebut, anda boleh ikut langkah penetapan ini.

1\. Log masuk kedalam akaun Shoppego anda.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Seterusnya anda boleh klik pada tab **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Anda akan dibawa ke halaman **Settings** dan anda boleh klik pada butang **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. Pada bahagian halaman Payment options, anda boleh klik butang **Activate/Edit** pada tab payment gateway Securepay

![](../../../../.gitbook/assets/YP760kujcmjXd6EqqXOm.jpg)

5\. Seterusnya, anda akan dibawa ke halaman penetapan untuk payment gateway Securepay.

![](../../../../.gitbook/assets/hKFLIiqplDBR464RkYbT.jpg)

6\. Dengan menggunakan key yang anda sudah simpan pada langkah mendapatkan key tersebut, anda boleh masukkan kesemua key tersebut pada ruangan mereka.

![](../../../../.gitbook/assets/sM2gYX6Jvu18Qmh29IKN.png)

7\. Setelah selesai anda boleh klik **Save** untuk simpan setting tersebut.&#x20;

{% hint style="info" %}
Sekiranya anda ingin **memulakan transaksi sebenar**, diminta untuk anda <mark style="color:red;">**mematikan**</mark> toggle **Test Mode** itu.
{% endhint %}

![](../../../../.gitbook/assets/xQHwviwBh7hb2J7WaRSZ.png)

## Contoh di Website

Setelah selesai proses penetapan tersebut, anda boleh cuba membuat pembelian di website Shoppego anda untuk melihat hasilnya.

![](../../../../.gitbook/assets/-MKIQvb2wS4urHd77IMV.png)

## Info Tambahan

{% hint style="info" %} <mark style="color:red;">**Perhatian**</mark>: Jika anda ingin menggunakan **payment gateway Securepay** ini kepada **2 store** yang berbeza. Anda boleh **cipta 2 API key** di dalam akaun Securepay anda dan tetapkan details **API key** tersebut kepada setting payment gateway store anda.
{% endhint %}

Untuk memulakan penetapan ini, anda boleh ikut langkah penetapan ini :

1\. Log masuk ke akaun **Securepay** anda

![](../../../../.gitbook/assets/-MN1R34ghvbuuCzv_6rz.png)

2\. Klik pada **< >** **API**

![](../../../../.gitbook/assets/-MN1R9JTsUbX3YjuMWA2.png)

3\. Klik pada butang **New API Key**

![](../../../../.gitbook/assets/-MN1RQnFUMkqW4v0rpW7.png)

4\. Pada bahagian **Interface name** anda boleh masukkan nama untuk **API** tersebut supaya senang untuk anda monitor data tersebut. Sebagai contoh anda ingin menggunakan **API** tersebut untuk monitor store gadget.myshoppegram.com, jadi anda boleh letak diruangan itu gadget.myshoppegram.com.

![](../../../../.gitbook/assets/-MN1RZAdW5l1w0w3BRUZ.png)

5\. Setelah selesai anda boleh klik **Save**

![](../../../../.gitbook/assets/-MN1ReapXOunaZi1auM6.png)

6\. Seterusnya, anda boleh klik pada API tersebut dan simpan maklumat yang anda perlukan untuk membuat tetapan di Shoppego pula.

![](../../../../.gitbook/assets/-MN1RuxKVe18L4IWzORZ.png)
