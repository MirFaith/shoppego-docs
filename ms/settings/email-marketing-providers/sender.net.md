# Sender.net

Untuk buat penetapan **Sender.net**, anda perlu dapatkan **API Access Token** dari **Sender** dan **masukkan key** yang telah anda dapatkan masuk kedalam sistem Shoppego.

## Log masuk akaun Sender

1. Anda boleh log masuk kedalam akaun Sender [<mark style="color:blue;">**di sini**</mark>](https://auth.sender.net/oauth/login?scope=scope\&client_id=21\&response_type=code\&redirect_uri=https%3A%2F%2Fapp.sender.net%2F) atau pada link ini: [https://auth.sender.net/oauth/login](https://auth.sender.net/oauth/login?scope=scope\&client_id=21\&response_type=code\&redirect_uri=https%3A%2F%2Fapp.sender.net%2F)

<figure><img src="../../../.gitbook/assets/LJ4BMZqNVGjR3aspmbgB.jpg" alt=""><figcaption></figcaption></figure>

## Dapatkan API Access Token Sender

1. Anda akan dibawa ke halaman **Dashboard Sender**, anda perlu **tekan pada Account settings**

<figure><img src="../../../.gitbook/assets/H4JiWVazm3IWOVyZWbkq.jpg" alt=""><figcaption></figcaption></figure>

2. Anda boleh tekan pada **API access tokens**

<figure><img src="../../../.gitbook/assets/fisMGtvL6sfdwGGUP9MH.jpg" alt=""><figcaption></figcaption></figure>

2. Setelah itu, anda boleh **tekan** pada **Create API token**

<figure><img src="../../../.gitbook/assets/hSrErdJnieNru8tYvLPD.jpg" alt=""><figcaption></figcaption></figure>

4. Seterusnya, anda boleh pilih **Forever** dan klik **Create**

<figure><img src="../../../.gitbook/assets/yD4FTowxtOz3sjHyl9Ea.png" alt=""><figcaption></figcaption></figure>

5. Setelah itu, anda boleh klik pada **Copy token** untuk digunakan bagi proses integration di platform Shoppego nanti.

<figure><img src="../../../.gitbook/assets/IvM7FOzoYWQBqUrEkjNh.jpg" alt=""><figcaption></figcaption></figure>

## Dapatkan Group ID(Optional)

Sekiranya anda tidak lakukan penetapan ini, maklumat pelanggan anda yang akan dibawa masuk itu tidak akan berada didalam mana-mana list.

1. Log masuk dashboard Sender.net

<figure><img src="../../../.gitbook/assets/LJ4BMZqNVGjR3aspmbgB.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Subscribers**

<figure><img src="../../../.gitbook/assets/05qnrRI01D2f1d6SNaVq.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada **Groups**

<figure><img src="../../../.gitbook/assets/vaX1kL3xeBlTK46PYfGM.jpg" alt=""><figcaption></figcaption></figure>

4. Klik pada **Create new group**

<figure><img src="../../../.gitbook/assets/hBGFpb1dV6lN26qKTNEz.jpg" alt=""><figcaption></figcaption></figure>

5. Seterusnya, anda boleh masukkan nama group sebagai rujukan anda dan klik **Save**

<figure><img src="../../../.gitbook/assets/cICXWudb1cZ5d64ELw5V.jpg" alt=""><figcaption></figcaption></figure>

6. Kemudian, anda akan di bawa ke halaman group itu sendiri dan anda akan dapat lihat Group ID. Anda boleh **copy Group ID** itu untuk digunakan bagi integrasi dengan platform Shoppego.

<figure><img src="../../../.gitbook/assets/eubJJyAjJzviaetCQdw9.jpg" alt=""><figcaption></figcaption></figure>

## Penetapan di Shoppego

1. Pada **Dashboard Overview**, anda boleh pergi ke **Settings**.

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

2. Selepas itu, anda boleh tekan pada **Email Marketing Provider**.

<figure><img src="../../../.gitbook/assets/G7jjXYelY1uP9ZamRoMj.jpg" alt=""><figcaption></figcaption></figure>

3. Pada halaman ini, anda akan perlu tekan butang **Activate/Edit** untuk **mengaktifkan Sender.net**

<figure><img src="../../../.gitbook/assets/qaurcCBgZH0Yi4dF8GMZ.jpg" alt=""><figcaption></figcaption></figure>

4. Anda perlu masukkan **API access token** yang anda telah dapat dari **Sender.net** kedalam ruang yang disediakan. Anda juga boleh letakkan **Group ID**.&#x20;

{% hint style="info" %}
\*\*<mark style="color:red;">**Perhatian**</mark> :&#x20;

* **Group ID** - Digunakan untuk meletakkan pelanggan yang berdaftar kedalam kumpulan yang anda mahukan.&#x20;
  {% endhint %}

5. Pastikan anda hidupkan toggle **Enable** untuk menggunakan **Sender.net**

<figure><img src="../../../.gitbook/assets/L7GkehXoLYMIlFBrdV8m.jpg" alt=""><figcaption></figcaption></figure>

<mark style="color:blue;">**Tahniah**</mark>! Penetapan **Sender.net** anda telahpun berjaya.

### Sync Maklumat pelanggan Shoppego Dengan Sender Group List

Untuk lakukan sync maklumat, anda hanya perlu klik pada butang **Sync All Customers/Sync**

<figure><img src="../../../.gitbook/assets/AtrJQEHnOcl8dZK8lmOv.jpg" alt=""><figcaption></figcaption></figure>
