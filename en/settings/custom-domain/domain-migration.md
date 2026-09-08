# Domain Migration

{% hint style="info" %}
To set up your migration domain from the old Shoppego server (**your own IP**) to the new Shoppego server (**shops.shoppego.my**)you can refer to the tutorial below:
{% endhint %}

**Starting February 26, 2026, every Shoppego user only need to do a CNAME record and every store/website will have the same CNAME record value/setting.**

## Before You Begin:

To complete the connection, you need to have the following information:

* Login information into your domain provider account (Platform you purchased the domain from)
* Access DNS record settings for your provider's domain account
* Shoppego's CNAME record value `shops.shoppego.my`
* The value of CNAME record www(optional) Shoppego that is `shops.shoppego.my`

There are several domain provider platforms such as Godaddy, Shinjiru and Exabyte that do not allow setting CNAME records for your main domain. For this issue, you need to [transfer the Nameserver to Cloudflare](cloudflare.md) and manage/set your DNS records there.

You also need to make sure that there is no A record set on your main domain and only the value `shops.shoppego.my` is set on your CNAME record.

## Part 1: Value CNAME Record

1. You can log in to the Shoppego dashboard

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2. Click on **Settings**

![](../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3. Click on **Custom domain**

![](../../../.gitbook/assets/NPDNVu0AWixGfseoNYZ8.jpg)

4\. If you still have your custom domain settings, you need to click on the **trash icon** button to delete your existing domain settings first.

<figure><img src="../../../.gitbook/assets/gDQMrIKRVU4IYihtwgrP.jpg" alt=""><figcaption></figcaption></figure>

5. Click on **Add existing domain**

![](../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg)

5\. Later, you will be able to see a pop-up that has a **value for your CNAME record**.

![](../../../.gitbook/assets/ewURFbN3hwGkPB6KWkmL.jpg)

**You need to save the Value for the CNAME record for you to enter in your domain's DNS record in the domain provider's system later.**

## Part 2: Make settings in the provider's domain account

{% hint style="info" %}
**If your domain provider cannot set a CNAME record for the host to the main domain or @, you can transfer DNS management to the Cloudflare system. You can refer to this link for an example of setting: <https://docs.shoppego.com/en/settings/custom-domain/cloudflare>**
{% endhint %}

1\. You need to **log in to your Domain provider account** and **go to the** **DNS Manager section** to edit the DNS records to point to the new DNS Shoppego in the following ways:-

* On the **CNAME record**, you can replace the value with the **value @ or your own domain name**

{% hint style="info" icon="triangle-exclamation" %}
**Make sure** your DNS record settings have your **CNAME record only**. If you **have A record**, **delete the DNS record** to **make sure there is no issue with your configuration**.
{% endhint %}

So the record you have made should look more or less like the picture below.

![](../../../.gitbook/assets/UUl8yaeI0Y7VnJeCLT5f.jpg)

## Additional information:&#x20;

To ensure that your DNS has been pointed to Shoppego, you can check your [**DNS here**](https://www.whatsmydns.net/) and make sure that the displayed DNS is your own Value.&#x20;

1. To check your DNS: You can click this link: Check your [**DNS here**](https://www.whatsmydns.net/) or <https://www.whatsmydns.net/>&#x20;

Referring to the image below, to check if your domain has propagated

{% hint style="info" %}
You can enter your **domain name** (with <mark style="color:red;">www</mark> and **without www**) in the space provided. Make sure you have made the changes to the CNAME record check.
{% endhint %}

<figure><img src="../../../.gitbook/assets/CrQgoaGRS5ABXprQaxE5.jpg" alt=""><figcaption></figcaption></figure>

### Propagation Period

You only need to wait for a period of <mark style="color:red;">**48 hours**</mark> for the setting to be read and your domain **can be used** before you make a **Custom domain** setting in Shoppego.&#x20;

The **shortest time** your domain can be used is within **1 hour.** If not, you need to wait for a period of <mark style="color:red;">**48 hours to 72 hours.**</mark> You can check the status of your domain propagation through the link we provided (<https://www.whatsmydns.net/>)

## Submit domain in Shoppego

So when the DNS is already pointed and propagated to Shoppego.

1\. Log in to the Shoppego dashboard

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **Custom Domains**

<figure><img src="../../../.gitbook/assets/NPDNVu0AWixGfseoNYZ8.jpg" alt=""><figcaption></figcaption></figure>

2\. Then you can click on **Add existing domain** and enter your **domain name without www**, and click the **Connect button**

![](../../../.gitbook/assets/ZCtFRdcw1oog2Y893cKW.jpg)

{% hint style="info" %}
\*\*<mark style="color:red;">**Note**</mark>: If there are **no issues**, the team will take **5-10 minutes to activate your domain**. If your domain still isn't activated within this timeframe, please contact our team.
{% endhint %}

If your Custom domain is ready and usable, the following example display will appear.

![](../../../.gitbook/assets/-MVsvXSd83b5HslqQTx6.png)

{% hint style="success" %}
The words **Connected** and **SSL activated** will be <mark style="color:green;">**green**</mark>. This situation will only happen if all the settings that have been done above are correct.
{% endhint %}
