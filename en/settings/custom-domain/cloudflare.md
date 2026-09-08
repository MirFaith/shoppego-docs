# Cloudflare

{% hint style="danger" %}
This tutorial is for those who <mark style="color:red;">**have problems**</mark> with the use of DNS by domain providers.
{% endhint %}

Each domain purchased has a section called Nameserver for us to give access to platforms such as Cloudflare to manage our DNS.

**Starting February 26, 2026, every Shoppego user only need to do a CNAME record and every store/website will have the same CNAME record value/setting.**

## **Domain Migration**

{% embed url="<https://www.youtube.com/watch?v=LiehNct34GU>" %}

## Part 1: Value CNAME Record

1\. You can log in to the **Shoppego Dashboard.**

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Settings.**

![](../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Click on **Custom domain.**

![](../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg)

4\. Click on **Add existing domain.**

![](../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg)

5\. Later you will be able to see a popup that has a **value for your CNAME record**.

{% hint style="info" %}
**CNAME designation in the domain provider.**\
1: If the **CNAME value** is **@**, enter **your domain name** or "**@**" in the **CNAME field** in the domain provider.
{% endhint %}

![](../../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg)

{% hint style="info" %}
You need to save the **Value** for **CNAME record** for you to enter in your domain's **DNS record** in the domain provider's system later.
{% endhint %}

## Part 2: Cloudflare Registration

1. Go to the following link  <https://dash.cloudflare.com/sign-up>. Enter your email and password to **register** and click **Create Account.**

![](../../../.gitbook/assets/-MBgEp0MNxilcHx3mufb.png)

2. Enter your purchased domain name from your domain provider. Then, click **Add Site**.

{% hint style="info" %}
In this section, you need to **enter the domain name&#x20;**<mark style="color:red;">**without**</mark>**&#x20;[www](http://www).**
{% endhint %}

![](../../../.gitbook/assets/-MBgEztcg5pkhZMqJLcz.png)

3. Next click on **Free Plan** and click **Confirm Plan.**

![](../../../.gitbook/assets/-MBgF5Aa3tOvBNTmSYZP.png)

## Part 3: DNS Setup

Wait until the display like the picture below comes out.

![](../../../.gitbook/assets/-MBgFDbSwXka2QlmBG_6.png)

{% hint style="warning" %}
If there are any **DNS records that are different** from the settings below, you can <mark style="color:red;">**delete**</mark> all of those records and refer back to the settings below.
{% endhint %}

{% hint style="info" %}
If the value of the **DNS record is the same** as the display below, you can just <mark style="color:blue;">**ignore**</mark> the settings below.
{% endhint %}

### 1: CNAME record settings:&#x20;

1. For the **CNAME record** settings, you can select the CNAME **dropdown** and enter the information in the corresponding fields:&#x20;

   * **Type**: CNAME&#x20;
   * **Name**: @&#x20;
   * **Target**: shops.shoppego.my
   * **Proxy Status**: DNS Only (\*\*<mark style="color:red;">**Note**</mark>: Make sure the **cloud icon** is **gray**)&#x20;
   * **TTL**: Automatic / 1 Hour&#x20;

   After completing the settings, click the **Save** button.

<figure><img src="../../../.gitbook/assets/mNlxA464L0smlicsevum.jpg" alt=""><figcaption></figcaption></figure>

### 2: Setting up CNAME www Record(Optional):&#x20;

2. For **CNAME Record**, select the **CNAME dropdown** and enter the information in the fields:&#x20;

   * **Type**: CNAME&#x20;
   * **Name**: www
   * **Target**: shops.shoppego.my
   * **Proxy Status**: DNS Only (\*\*<mark style="color:red;">**Note**</mark>: Make sure the **cloud icon** is **gray**)&#x20;
   * **TTL**: Automatic / 1 hour&#x20;

   After completing, click the **Save** button.

<figure><img src="../../../.gitbook/assets/hBSR4A7HCaF3zdIekBPM.jpg" alt=""><figcaption></figcaption></figure>

3. &#x20;When you have finished making the settings, the display you will receive is as follows:

<figure><img src="../../../.gitbook/assets/yStptMJ58g0yUSs0fFOK.jpg" alt=""><figcaption></figcaption></figure>

### 3: Nameserver Setting

1. Next in the **Proxy Status** column, there is an **orange cloud (Proxied)** icon.&#x20;

{% hint style="info" %}
**Click on the icon** to change it to **gray (DNS Only)** and click **Save**. Do it for the **A record** and also the **CNAME record**.&#x20;
{% endhint %}

2. Then click **Continue.**

![](../../../.gitbook/assets/UUl8yaeI0Y7VnJeCLT5f.jpg)

3. After clicking **Continue**, the display as below will appear. Click **Continue by default**

![](../../../.gitbook/assets/-MBgGlP1I5Hv2Sgu0F3-.png)

4. Then there will be a nameserver from Cloudflare that you can use in your domain name provider.

![](../../../.gitbook/assets/-MBgGu_CN5uBJ3P4FM0w.png)

5. Log in to your domain name provider's account and delete the nameserver on your domain provider. **Replace with Cloudflare nameserver** that has been provided as shown below :&#x20;

![](../../../.gitbook/assets/-MBgH67YbqzybYIynZiW.png)

6. After you replace the nameservers click the **Done** button, **check nameservers**.

{% hint style="info" %}
If you <mark style="color:red;">**encounter any issues**</mark> with changing your nameservers, you can **contact your domain provider for assistance** in making these changes.
{% endhint %}
