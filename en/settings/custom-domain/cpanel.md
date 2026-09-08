# CPanel

There are 3 parts to this setup:

* **Part 1**: Get the value for CNAME record
* **Part 2**: Setup in CPanel
* **Part 3**: Setup in Shoppego

{% hint style="info" %} <mark style="color:red;">**Reminder**</mark> Make sure your domain **has been purchased** and **can be used for setup**. If you purchased a "**.com**" domain, you can **continue to follow** this tutorial.
{% endhint %}

If the Malaysian domain is like "**.my, .com.my, .net.my**" you need to **setup your DNS records** in your **MYNIC account** or you can **contact your domain provider** to make the changes.

**Starting February 26, 2026, every Shoppego user only need to do a CNAME record and every store/website will have the same CNAME record value/setting.**

## Part 1: Value CNAME Record

1\. You can log in to the Shoppego dashboard

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Settings**

![](../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Click on **Custom domain**

![](../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg)

4\. Click on **Add existing domain**

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

## Part 2: Setup in CPanel

1\. Log in to your CPanel account.

![](../../../.gitbook/assets/-MUvHsBL7s2s5XOn3LuL.jpg)

2\. On the CPanel dashboard, you can click on the **Zone Editor** section

![](../../../.gitbook/assets/-MUvHwJ65wcmAg86FWoY.jpg)

{% hint style="info" %}
**If your domain provider cannot set a CNAME record for the host to the main domain or @, you can transfer DNS management to the Cloudflare system. You can refer to this link for an example of setting: <https://docs.shoppego.com/en/settings/custom-domain/cloudflare>**
{% endhint %}

3\. Next, to enter a CNAME record you can click on the **+CNAME RECORD** button

![](../../../.gitbook/assets/-MUvI20Tqkxfdg6ax74A.jpg)

4. Once you click on the button you can enter the requested.
   * **Name** : Your domain name.
   * **Value** : shops.shoppego.my

![](../../../.gitbook/assets/-MgoOVEoY6SAC7YgfSe3.jpg)

5\. Once you have entered the information, you can click on the **ADD AN CNAME RECORD** button

![](../../../.gitbook/assets/-MgoOiq9qnYOAdHwqItk.jpg)

6\. Next to enter a CNAME www record(Optional), you can click on the **+CNAME RECORD** button

![](../../../.gitbook/assets/-MUvITs228XKtvVKrK2n.jpg)

7. Once you click on the button you can enter the requested information.
   * **Name**: Domain name with www
   * **Value** : shops.shoppego.my

![](../../../.gitbook/assets/-MgoP957SAF2KBJNqAkc.jpg)

8\. Once you have entered that information, you can click on the **ADD AN CNAME RECORD** button

![](../../../.gitbook/assets/-MgoPORqWiidM8UAp9ez.jpg)

{% hint style="info" %}
Your domain will take **24-48 hours** for it to be used and included in the settings in Shoppego. You may refer to [**Propagation Period**](cpanel.md#propagation-time)**.**
{% endhint %}

### Propagation Period

You only need to wait for a period of <mark style="color:red;">**48 hours**</mark> for the setting to be read and your domain **can be used** before you make a **Custom domain** setting in Shoppego.&#x20;

The **shortest time** your domain can be used is within **1 hour.** If not, you need to wait for a period of <mark style="color:red;">**48 hours to 72 hours.**</mark> You can check the status of your domain propagation through the link we provided (<https://www.whatsmydns.net/>)

## Additional information:&#x20;

﻿To ensure that your DNS is directed to Shoppego, you can [Check your DNS Here ](https://www.whatsmydns.net/)and make sure the **DNS displayed is the one you have set**.

1. To check your DNS: You can click this link: Check your [**DNS here**](https://www.whatsmydns.net/) or <https://www.whatsmydns.net/>&#x20;

{% hint style="info" %}
You can enter your **domain name** (with <mark style="color:red;">www</mark> and **without www**) in the space provided. Make sure you have made the changes to the CNAME record check.
{% endhint %}

<figure><img src="../../../.gitbook/assets/CrQgoaGRS5ABXprQaxE5.jpg" alt=""><figcaption></figcaption></figure>

## Part 3: Setup in Shoppego

﻿1. Log in to the Shoppego Dashboard -> **Settings(1)** and click **Custom Domains(2).**

<figure><img src="../../../.gitbook/assets/rkJDVGfqLTo3sj7i9kCn.jpg" alt=""><figcaption></figcaption></figure>

2. On this Domains page, click on the **Add existing domain** button.

<figure><img src="../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg" alt=""><figcaption></figcaption></figure>

3. The Add existing domain pop-up will appear. Fill in the name of your website in the **Custom Domain** field and click the **Connect** button

{% hint style="info" %}
In the space below, you need to **enter your domain** name <mark style="color:red;">**without**</mark>**&#x20;www**.
{% endhint %}

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
