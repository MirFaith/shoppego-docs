# Domain Troubleshoot

Sekiranya, domain anda mempunyai sebarang isu atau memaparkan error Error 1014, CNAME Cross-User Banned atau lain-lain, anda perlu lakukan semakan semula terhadap penetapan domain anda itu. Terdapat 3 perkara yang anda perlu lakukan semakan:

## Anda perlu pastikan anda sudah lakukan penambahan semula Custom domain tersebut pada penetapan Custom domain di store anda.

Untuk ini, anda boleh pergi pada bahagian:

1. Log masuk akaun Shoppego

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Klik pada **Custom domain**

<figure><img src="../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg" alt=""><figcaption></figcaption></figure>

4. Klik pada **ikon tong sampah** untuk padam penetapan domain anda itu

<figure><img src="../../../.gitbook/assets/gDQMrIKRVU4IYihtwgrP.jpg" alt=""><figcaption></figcaption></figure>

5. Setelah anda padam penetapan domain itu, anda boleh klik pada butang **Add existing domain**

<figure><img src="../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg" alt=""><figcaption></figcaption></figure>

6. Kemudian, anda boleh **masukkan semula nama domain** anda itu dan klik **Connect**

<figure><img src="../../../.gitbook/assets/ZCtFRdcw1oog2Y893cKW.jpg" alt=""><figcaption></figcaption></figure>

## Sekiranya anda menguruskan DNS anda di platform Cloudflare, anda perlu pastikan penetapan Proxy status anda itu ditetapkan kepada DNS Only

Untuk ini, anda boleh semak pada bahagian:

1. Log masuk akaun Cloudflare anda

<figure><img src="../../../.gitbook/assets/AsU7Yh7Q530lkakw0ZxL.jpg" alt=""><figcaption></figcaption></figure>

2. Klik pada domain anda itu dan akses semula penetapan DNS record domain anda

<figure><img src="../../../.gitbook/assets/GibT8z87j0ASxllfjR0o.jpg" alt=""><figcaption></figcaption></figure>

3. Pastikan penetapan Proxy status CNAME record anda itu ditetapkan kepada `DNS Only` dan bukannya `Proxied`

<figure><img src="../../../.gitbook/assets/URCP8K53vV96aUfd8zZf.jpg" alt=""><figcaption></figcaption></figure>

## Jika penetapan anda itu baru sahaja dilakukan, anda perlu tunggu sehingga ia propagate sepenuhnya.

Untuk situasi ini, penetapan domain itu selalunya akan ambil masa dalam 24-48 jam untuk ia propagate sepenuhnya. Sekiranya, penetapan anda itu baru sahaja dilakukan anda perlu tunggu dalam tempoh yang dimaklumkan itu.
