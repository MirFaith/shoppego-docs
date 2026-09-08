# Shinjiru (Domain.my)

There are 6 parts required for setting up a .com.my domain:

* **Part 1** : CNAME Record Value
* **Part 2**: Purchase Domain from Shinjiru&#x20;
* **Part 3**: Identity Verification&#x20;
* **Part 4**: Cloudflare Registration&#x20;
* **Part 5**: Setting up **Cloudflare Nameservers** in **MYNIC** .
* **Part 6**: Configuration in Shoppego

**Starting February 26, 2026, every Shoppego user only need to do a CNAME record and every store/website will have the same CNAME record value/setting.**

## Part 1: CNAME Record Value

1. To obtain the **values of A and CNAME Records** in Shoppego, you simply need to go to:&#x20;

**Dashboard Overview -> Settings -> Custom Domain -> Add Existing Domain.**

{% hint style="info" %}
You need to **save** the **Value for CNAME record** for you to enter in your domain's DNS record in the domain provider's system later.
{% endhint %}

<figure><img src="../../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg" alt=""><figcaption></figcaption></figure>

## Part 2: Purchasing a Domain from Shinjiru&#x20;

1. To **purchase** a domain from Shinjiru, you can go to this link: <https://www.shinjiru.com.my/>.

<figure><img src="../../../.gitbook/assets/N4mQbYg68NjTSz8yFB4F.png" alt=""><figcaption></figcaption></figure>

## Part 3: Identity Verification&#x20;

1. After purchasing the domain, Shinjiru will send you an email **requesting identity verification** such as an **identification card (IC)** picture as shown below.

<figure><img src="../../../.gitbook/assets/lKO324JFpzFXcNQn74NI.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %} <mark style="color:red;">**Attention**</mark>: After replying to their email, you **need to wait for 1\~2 days for the activation** of your **MYNIC domain registration**.
{% endhint %}

2. After the activation is successfully done, you will **receive information to log in** to your **MYNIC account.**

<figure><img src="../../../.gitbook/assets/0KcIoVXdOyz3RX82VrA0.jpg" alt=""><figcaption></figcaption></figure>

3. After the **activation is successfully done**, you **need to log in** to <https://selfcare.ichoose.my/login> using the given information.

<figure><img src="../../../.gitbook/assets/3zcFSfRZ9C2zJhOSmLYA.png" alt=""><figcaption></figcaption></figure>

## Part 4: Cloudflare Registration&#x20;

1. To **register for Cloudflare**, you can go to this link: <https://www.cloudflare.com/> and click on the **Sign Up** button.

<figure><img src="../../../.gitbook/assets/9v0tpEcQxHN8how4P8yB.jpg" alt=""><figcaption></figcaption></figure>

2. After that, you **can enter your Email Address** and **Password**, then **click the Sign Up** button. After that, you can **log in to your Cloudflare account**.

<figure><img src="../../../.gitbook/assets/oaphQblC7pNIHzkmzeVm.png" alt=""><figcaption></figcaption></figure>

3. After that, click on the **Add Site** button.

<figure><img src="../../../.gitbook/assets/ch2Nc2CqkwGRcHHPSIKc.jpg" alt=""><figcaption></figcaption></figure>

4. Enter the **domain name you have purchased** and **click on the Add Site** button.

<figure><img src="../../../.gitbook/assets/oXEA1JWYx3BRuWpjQBNE.jpg" alt=""><figcaption></figcaption></figure>

5. After that, you need to click on your **domain name** and **select Free** on the Plan as shown below.

<figure><img src="../../../.gitbook/assets/xRgleIXGSsjS39YeIRc9.jpg" alt=""><figcaption></figcaption></figure>

6. After that, you need to **set up DNS** in Cloudflare. You just need to **click on DNS on the left side** and **click on the Record section**.

### 1: Setting up CNAME Record:&#x20;

1. To set up the CNAME **Record**, you can **select the CNAME dropdown** and enter the following information in the field:

   * **Type**: CNAME
   * **Name**: @ or your own domain name&#x20;
   * **IPv4 Address**: shops.shoppego.my
   * **Proxy Status**: DNS Only&#x20;
   * **TTL**: Automatic / 1 Hour&#x20;

   After you are done, click the **Save** button.

<figure><img src="../../../.gitbook/assets/mNlxA464L0smlicsevum.jpg" alt=""><figcaption></figcaption></figure>

### 2: Setting up CNAME www Record(Optional):&#x20;

2. To set up the **CNAME Record**, you can **select the CNAME dropdown** and enter the following information in the field:&#x20;

   * **Type**: CNAME&#x20;
   * **Name**: www&#x20;
   * **Target**: shops.shoppego.my
   * **Proxy Status**: DNS Only&#x20;
   * **TTL**: Automatic / 1 Hour&#x20;

   After you are done, click the **Save** button.

<figure><img src="../../../.gitbook/assets/hBSR4A7HCaF3zdIekBPM.jpg" alt=""><figcaption></figcaption></figure>

3. After completing the setup, the **display of your DNS** will be as follows:&#x20;

<figure><img src="../../../.gitbook/assets/yStptMJ58g0yUSs0fFOK.jpg" alt=""><figcaption></figcaption></figure>

### 3: Get Nameservers from Cloudflare:&#x20;

1. On your **Overview** page, you can scroll down to the **section Replace with Cloudflare's Nameserver**. **Copy both nameservers** to be placed in your **MYNIC account.**

<figure><img src="../../../.gitbook/assets/1N0K3fUsnLswZuPuHc7J.jpg" alt=""><figcaption></figcaption></figure>

## Part 5: Setting up Cloudflare Nameservers in MYNIC&#x20;

1. You need to log in to <https://selfcare.ichoose.my/login> using the given information.

<figure><img src="../../../.gitbook/assets/3zcFSfRZ9C2zJhOSmLYA.png" alt=""><figcaption></figcaption></figure>

2. After that, you need to click on the **Manage** button.

<figure><img src="../../../.gitbook/assets/xjm7eyBmiQRXgy9lmfT8.jpg" alt=""><figcaption></figcaption></figure>

3. After that, you need to click on the Manage button. Then, go to **Nameservers (1)**, click on **Edit (2)** and **enter both Nameservers (3)** that have **been copied from Cloudflare**. You need to click on **Save** button to save the settings that have been made.

<figure><img src="../../../.gitbook/assets/lwppgUbnJoSUL2ydm2jN.jpg" alt=""><figcaption></figcaption></figure>

## Propagation Period

You only need to wait for a <mark style="color:red;">**period of 48 hours**</mark> for the setting to be read and your domain can be used before you make a Custom domain setting in Shoppego.&#x20;

The shortest time your domain can **be used is within 1 hour**. If not, you need to <mark style="color:red;">**wait for a period of 48 hours to 72 hours.**</mark> You can check the status of your domain propagation through the link we provided (<https://www.whatsmydns.net/>)

## Additional information:&#x20;

﻿To ensure that your DNS is directed to Shoppego, you can [Check your DNS Here ](https://www.whatsmydns.net/)and make sure the **DNS displayed is the one you have set**.

1. To check your DNS: You can click this link: Check your [**DNS here**](https://www.whatsmydns.net/) or <https://www.whatsmydns.net/>&#x20;

{% hint style="info" %}
You can enter your **domain name** (with <mark style="color:red;">www</mark> and **without www**) in the space provided. Make sure you have made the changes to the CNAME record check.
{% endhint %}

<figure><img src="../../../.gitbook/assets/CrQgoaGRS5ABXprQaxE5.jpg" alt=""><figcaption></figcaption></figure>

## Part 6: Configuration in Shoppego

1. In the **Shoppego dashboard**, click on **Settings (1)** and scroll down to **Custom Domain (2).**

<figure><img src="../../../.gitbook/assets/rkJDVGfqLTo3sj7i9kCn.jpg" alt=""><figcaption></figcaption></figure>

2. After that, click on **Add Existing Domain**.

<figure><img src="../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg" alt=""><figcaption></figcaption></figure>

3. **Enter the domain name** that you purchased earlier.

<figure><img src="../../../.gitbook/assets/ZCtFRdcw1oog2Y893cKW.jpg" alt=""><figcaption></figcaption></figure>

4. When you have successfully entered your domain, the display will change as below:&#x20;

{% hint style="info" %}
\*\*<mark style="color:red;">**Note**</mark>: If there are **no issues**, the team will take **5-10 minutes to activate your domain**. If your domain still isn't activated within this timeframe, please contact our team.
{% endhint %}

<figure><img src="../../../.gitbook/assets/OxA9xwgku7giuleysijh.jpg" alt=""><figcaption></figcaption></figure>

5. If your **Custom Domain** is **ready** and **can be used**, an example display like the following will appear.&#x20;

{% hint style="success" %}
The words "**Connected**" and "**SSL activated**" will turn <mark style="color:green;">**green**</mark>. This condition will only occur if all the **settings that have been made are correct.**
{% endhint %}

<figure><img src="../../../.gitbook/assets/X85NI3O093W3eevMgOSb.jpg" alt=""><figcaption></figcaption></figure>
