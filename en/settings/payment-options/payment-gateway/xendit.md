# Xendit

To use Xendit, please make sure you **have first created** a **Xendit account**.

{% hint style="success" %}
You need to make sure you have:

* Have SSM/TIN
* Current bank account.
  {% endhint %}

{% hint style="info" %}
**Account verification, charges and transaction funds are fully managed by Xendit.**
{% endhint %}

## Setting up in Xendit

{% hint style="danger" %}
**Before you follow this tutorial, make sure your Xendit account has been verified first and make sure you are not using a Test account.**
{% endhint %}

To integrate Xendit payment gateway with Shoppego, you need to obtain a **Secret API Key and Webhook Verification Token. You also need to set up a Webhook on your Xendit account.**\
\
If you haven't registered a Xendit account yet, you can use this link:\
<https://dashboard.xendit.co/register/1>

### Get the Secret API Key

1. Log in to your Xendit account.

<figure><img src="../../../../.gitbook/assets/lop878I3vDJ2Q4iWomOr.jpg" alt=""><figcaption></figcaption></figure>

2. Click on the **Settings** button/text

<figure><img src="../../../../.gitbook/assets/torOGCjeWZS7WHs8OlV8.jpg" alt=""><figcaption></figcaption></figure>

3. Click on the **API keys** button/text

<figure><img src="../../../../.gitbook/assets/nIsVkE2vfQX4CN8Lbype.jpg" alt=""><figcaption></figcaption></figure>

4. Then, you can click on **Generate secret key**

<figure><img src="../../../../.gitbook/assets/PZQx4w7jy8htvbHcLXUq.jpg" alt=""><figcaption></figcaption></figure>

5. You can **enter your Secret key name as a reference and tick other settings as shown in the image below.**

<figure><img src="../../../../.gitbook/assets/aJ5VaKWBmEezfMtQiRQy.jpg" alt=""><figcaption></figcaption></figure>

6. After finishing click **Generate key**

<figure><img src="../../../../.gitbook/assets/1wiGn3HKmq1xhtNFyh19.jpg" alt=""><figcaption></figcaption></figure>

7. Then, you can **copy** and **save your Secret key** to **use in settings in Shoppego**.

<figure><img src="../../../../.gitbook/assets/vCRlDpcOFHytctdlCwPU.jpg" alt=""><figcaption></figcaption></figure>

### Get Webhook Verification Token

1. From the **API Keys** **page**, you can click on the **Webhooks** button/text

<figure><img src="../../../../.gitbook/assets/KnfSnpjBQDxhsiSgAC6X.jpg" alt=""><figcaption></figcaption></figure>

2. Then, click on the **View Webhook Verification Token** button

<figure><img src="../../../../.gitbook/assets/unT8Zj5az03hwqZwJL0C.jpg" alt=""><figcaption></figcaption></figure>

3. Next, you can **copy your Webhook Verification Token** to **use in the settings on Shoppego**.

<figure><img src="../../../../.gitbook/assets/u2Wm9F8fhm2XoGWujLDB.jpg" alt=""><figcaption></figcaption></figure>

### Webhook Setting

#### Get the Webhook Link

1. Log in to your Shoppego account.

<figure><img src="../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **Payment options**

<figure><img src="../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg" alt=""><figcaption></figcaption></figure>

4. Click **Activate/Edit** on **Xendit**

<figure><img src="../../../../.gitbook/assets/0egeOsfGLxBW6Xf31Ssa.jpg" alt=""><figcaption></figcaption></figure>

5. Then, you can **copy your Webhook URL** to **enter in the settings in Xendit**.

<figure><img src="../../../../.gitbook/assets/Zj1YfBg6JTNqzR6hc7xD.jpg" alt=""><figcaption></figcaption></figure>

#### Enter the Webhook Link in Xendit

1. On the **Webhooks settings page**, you can **scroll down** **to see the** "**Invoices paid**" setting. You can **enter the Webhook URL** you just copied into the setting field.

<figure><img src="../../../../.gitbook/assets/d64zarK9JqMm19ecszxx.jpg" alt=""><figcaption></figcaption></figure>

2. Once finished, click on the **Test and save** button

<figure><img src="../../../../.gitbook/assets/fUYfBv0WFzDJOW7FMJPe.jpg" alt=""><figcaption></figcaption></figure>

## Setting up in Shoppego

1\. Log in to your Shoppego account.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Click on **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. If you have not activated the payment option for Xendit. Click the **Activate** button in the **Alternative Payments section** for Xendit. If you have already activated the payment option for Xendit, click the **Edit** button.

![](../../../../.gitbook/assets/0egeOsfGLxBW6Xf31Ssa.jpg)

5\. Next, a display will appear as below, you can fill in the information:

![](../../../../.gitbook/assets/2RVwbs3xgm3oVGXpUdts.jpg)

* **Display name at checkout: Enter the payment name you want (Example Xendit)**
* **Webhook URL: Only used for you to copy to set up the webhook in your Xendit account.**
* **Secret API Key: Enter the Secret API key that you have obtained in your Xendit account.**
* **Webhook Verification Token: Enter the Webhook Verification Token that you have obtained in your Xendit account.**

6\. After finishing, make sure you have clicked Enable and click the **Save** button.

![](../../../../.gitbook/assets/Jk8yRhyPKocahCajDPpe.jpg)

After **Save**, you can make a trial purchase on your website to see the Xendit payment option during checkout for the settings you just set.
