# Custom Domain

{% hint style="info" %}
Each store in Shoppego will **get a hosting and free subdomain(&#x20;**<mark style="color:red;">**cannot be changed afterwards**</mark>**)** in the form of : [https://kedaianda.myshoppegram.com](https://kedaianda.myshoppegram.com./)
{% endhint %}

However, if users want to use their own domain is also allowed by Shoppego by only having to **set up DNS on CNAME record** from the domain provider to DNS Shoppego information.

**Starting February 26, 2026, every Shoppego user only need to do a CNAME record and every store/website will have the same CNAME record value/setting.**

## List of Domains and Setup Tutorials&#x20;

The following are the names of domains and setup tutorials:

{% content-ref url="custom-domain/shinjiru.md" %}
[Shinjiru](custom-domain/shinjiru.md)
{% endcontent-ref %}

{% content-ref url="custom-domain/godaddy.md" %}
[Godaddy](custom-domain/godaddy.md)
{% endcontent-ref %}

{% content-ref url="custom-domain/namecheap.md" %}
[Namecheap](custom-domain/namecheap.md)
{% endcontent-ref %}

{% content-ref url="custom-domain/cloudflare.md" %}
[Cloudflare](custom-domain/cloudflare.md)
{% endcontent-ref %}

{% content-ref url="custom-domain/exabytes.md" %}
[Exabytes](custom-domain/exabytes.md)
{% endcontent-ref %}

{% content-ref url="custom-domain/cpanel.md" %}
[CPanel](custom-domain/cpanel.md)
{% endcontent-ref %}

{% content-ref url="custom-domain/domain-migration.md" %}
[Domain Migration](custom-domain/domain-migration.md)
{% endcontent-ref %}

## Important Tips

### Domain name

{% hint style="info" %}
**Make sure your domain name&#x20;**<mark style="color:red;">**does not have a hyphen ( -)**</mark> symbol.

* This is because domains that have a hyphen ( -) symbol are often symbolized/categorized as <mark style="color:red;">**domain spam**</mark>.&#x20;
* Domains that have this symbol will also always have a <mark style="color:red;">**typo**</mark> while the customer/buyer is typing.
  {% endhint %}

{% hint style="info" %}
**Make sure you&#x20;**<mark style="color:red;">**use a .com domain**</mark> because a .com domain makes it easier for your customers/buyers to find your website.&#x20;

* In addition, each mobile phone also has a .com button and it can make it easier for your customers/buyers to type in the URL of your website.&#x20;
* <mark style="color:red;">**Note**</mark>: If there is no .com domain, you can use the .com.my domain instead.
  {% endhint %}

{% hint style="info" %}
**Make sure your domain name is&#x20;**<mark style="color:red;">**short and easy to remember**</mark>**&#x20;and called**&#x20;

* Domain that is **short and easy** to remember **can reduce typos** typed by customers/buyers.&#x20;
* We recommend that your domain name be <mark style="color:red;">**no longer**</mark>**&#x20;than 15 words.**
  {% endhint %}

{% hint style="info" %}
**Make sure your&#x20;**<mark style="color:red;">**domain name is unique**</mark>**&#x20;and has its own brand**&#x20;

* Attractive domains can attract people to come to your website.&#x20;
* For example, Amazon.com looks more attractive than BuyBooksOnline.com.
  {% endhint %}

## Get a Custom Domain

To use your own domain, you can get it from any Domain Name provider according to your convenience, among them are at&#x20;

* **shinjiru.com.my**
* **exabytes.my**
* **namecheap.com**.

### Setting up Malaysian Domain

For .com domains usually after purchase, it will immediately can be used for DNS setup. For Malaysian domains such as **.my, .com.my, .net.my** need to <mark style="color:red;">**wait for at least 72 working hours before it can be used**</mark> and you need to change your DNS records in your MYNIC account only.

{% hint style="info" %}
You can **contact** your **domain provider** to make the changes.
{% endhint %}

Once you have your own domain, you can go to the DNS Manager and edit DNS records to point to DNS Shoppego by:-

1. Create an CNAME **record** for **@** and point to **shops.shoppego.my**
2. Create a **CNAME** record for **www** and point to **shops.shoppego.my(Optional)**

{% hint style="info" %}
**These records are&#x20;**<mark style="color:red;">**important**</mark>**&#x20;and&#x20;**<mark style="color:red;">**mandatory**</mark>. Only the www CNAME record are optional. So the record you have made should look more or less like the picture below.
{% endhint %}

![](../../.gitbook/assets/-MgobEIADMBXLjOSWcB1.png)

{% hint style="info" %}
**If your domain provider cannot set a CNAME record for the host to the main domain or @, you can transfer DNS management to the Cloudflare system. You can refer to this link for an example of setting: <https://docs.shoppego.com/en/settings/custom-domain/cloudflare>**
{% endhint %}

### Subdomain&#x20;

**Situation**: I have a domain websitesaya.com and I want to add a subdomain.&#x20;

**Answer**: You only need to add CNAME **Record** for your subdomain.&#x20;

**For example**:&#x20;

* **Main Domain**: websitesaya.com&#x20;
* **Host**: @  or your own domain name
* **Value**: shops.shoppego.my

To use a subdomain from the main domain, you just need to add CNAME **record.**&#x20;

* **Host**: kedai&#x20;
* **Value**: shops.shoppego.my

Then, the domain for your new store is **kedai.websitesaya.com**.&#x20;

{% hint style="info" %}
To use a **subdomain from the main domain**, you just need to **add CNAME Record.**
{% endhint %}

## Value CNAME Record

1. In the **Shoppego dashboard**, click on **Settings (1)** and scroll down to **Custom Domain (2).**

<figure><img src="../../.gitbook/assets/rkJDVGfqLTo3sj7i9kCn.jpg" alt=""><figcaption></figcaption></figure>

2. After that, click on **Add Existing Domain**.

![](../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg)

5. Later you will be able to see a popup that has a **value for your A record** and your **CNAME record**.

{% hint style="info" %}
**CNAME designation in the domain provider.**\
1: If the **CNAME value** is **@**, enter **your domain name** or "**@**" in the **CNAME field** in the domain provider.
{% endhint %}

![](../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg)

## Additional information:&#x20;

﻿To ensure that your DNS is directed to Shoppego, you can [Check your DNS Here ](https://www.whatsmydns.net/)and make sure the **DNS displayed is the one you have set**.

1. To check your DNS: You can click this link: Check your [**DNS here**](https://www.whatsmydns.net/) or <https://www.whatsmydns.net/>

{% hint style="info" %}
You can enter your **domain name** (with <mark style="color:red;">www</mark> and **without www**) in the space provided. Make sure you have made the changes to the CNAME record check.
{% endhint %}

<figure><img src="../../.gitbook/assets/CrQgoaGRS5ABXprQaxE5.jpg" alt=""><figcaption></figcaption></figure>

## Propagation Period

You only need to wait for a <mark style="color:red;">**period of 48 hours**</mark> for the setting to be read and your domain can be used before you make a Custom domain setting in Shoppego.&#x20;

The shortest time your domain can **be used is within 1 hour**. If not, you need to <mark style="color:red;">**wait for a period of 48 hours to 72 hours.**</mark> You can check the status of your domain propagation through the link we provided (<https://www.whatsmydns.net/>)

## Set up a Custom Domain in Shoppego

1. Log into **Dashboard Shoppego** -> **Settings** -> **Custom Domain** -> **Add existing domain**

<figure><img src="../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg" alt=""><figcaption></figcaption></figure>

2. **Enter the domain name** <mark style="color:red;">**without**</mark>**&#x20;www** that you purchased earlier.

<figure><img src="../../.gitbook/assets/ZCtFRdcw1oog2Y893cKW.jpg" alt=""><figcaption></figcaption></figure>

3. When you have successfully entered your domain, the display will change as below:&#x20;

{% hint style="info" %}
\*\*<mark style="color:red;">**Note**</mark>: If there are **no issues**, the team will take **5-10 minutes to activate your domain**. If your domain still isn't activated within this timeframe, please contact our team.
{% endhint %}

<figure><img src="../../.gitbook/assets/OxA9xwgku7giuleysijh.jpg" alt=""><figcaption></figcaption></figure>

4. If your Custom domain is ready and usable, the following example display will appear.

{% hint style="success" %}
The words **Connected** and **SSL activated** will be green. This situation will only happen if all the settings that have been done above are correct.
{% endhint %}

<figure><img src="../../.gitbook/assets/X85NI3O093W3eevMgOSb.jpg" alt=""><figcaption></figcaption></figure>

### Automatic SSL

In Shoppego, each custom domain will also be given SSL automatically without the need to buy at the domain provider. It is enough to just buy a regular domain and Shoppego will provide an SSL certificate for each domain.

When SSL has been successfully entered into your Custom domain, the HTTP protocol will switch to HTTPS automatically.

{% hint style="info" %}
'S' means 'secure', and now a 'padlock' icon will appear on the browser indicating that your website is secure to all buyers. as in the picture
{% endhint %}

![](https://helpwiseknowledgebase.s3.amazonaws.com/uploads/207347/204578/4a457f4c60b295bcf0fa6a964bbd94e3c7c98d94-1591001503-ad0661cff6497e560dcfc85229159fbf4fd44668)
