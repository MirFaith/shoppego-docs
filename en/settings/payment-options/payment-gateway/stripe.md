# Stripe

To use Stripe please make sure you have **created a Stripe** account first.

{% hint style="info" %}
**Account verification, fees, and transactional funds,** they are **fully managed by Stripe.**
{% endhint %}

{% hint style="danger" %}
The minimum transaction amount for Stripe is at least RM2.00
{% endhint %}

## Get an API key on Stripe

1\. Stripe account registration can be done at: [https://dashboard.stripe.com/register](https://dashboard.stripe.com/register)

2\. To get the **live key** you can find it on the dashboard or just click this link: [https://dashboard.stripe.com/login?redirect=%2Faccount%2Fapikeys](https://dashboard.stripe.com/login?redirect=%2Faccount%2Fapikeys)

3\. Once you get the **Publishable key** and **Secret key** you can save the key for setting in Shoppego.

![](../../../../.gitbook/assets/-MD8Z-UDHUXIhH4PNbRk.png)

## Webhooks settings at Stripe

There are **2 types of webhooks** that you need to enter in the webhooks settings of your Stripe account, namely:\
1\. [https://hartamas.myshoppegram.co\&#x6D;\*\*/webhooks/payments/callback/checkouts/stripe\*\*\\\\](https://hartamas.myshoppegram.co&/#x6D;**/webhooks/payments/callback/checkouts/stripe**\\\\) 2. [https://hartamas.myshoppegram.co\&#x6D;\*\*/webhooks/payments/callback/typ\\\\\_offer/stripe](https://hartamas.myshoppegram.co&/#x6D;**/webhooks/payments/callback/typ\\\\_offer/stripe)\*\*

You are **required to replace the** [**https://hartamas.myshoppegram.com**](https://hartamas.myshoppegram.com) **with the URL** [**https://subdomain.myshoppegram.com**](https://subdomain.myshoppegram.com) **of your own website which has been given for free during the registration of your Shoppego account**.

You can find your subdomain URL in the following section:\
Dashboard Overview Shoppego -> **Settings** -> **Custom domain** -> **Subdomain**

<figure><img src="../../../../.gitbook/assets/i6ChVkQCDHAFSqE60OI8.jpg" alt=""><figcaption></figcaption></figure>

You can refer to examples of setting webhooks below:

1. In the Stripe dashboard, you can click on the **Developers** -> **Webhooks** section. You can also click on this link directly: [https://dashboard.stripe.com/webhooks](https://dashboard.stripe.com/webhooks)

<figure><img src="../../../../.gitbook/assets/CpjwIAo8ZjwuuYrEEMAS.png" alt=""><figcaption></figcaption></figure>

2. Next, you can click on **Add an endpoint/Add endpoint**

<figure><img src="../../../../.gitbook/assets/OuVy4UW3iXmuB2PvOKBk.jpg" alt=""><figcaption></figcaption></figure>

3. Next, you can **enter one of your unique webhooks store URLs in the Endpoint URL section**. For example here, we have entered this URL first: [https://hartamas.myshoppegram.com/webhooks/payments/callback/checkouts/stripe](https://hartamas.myshoppegram.com/webhooks/payments/callback/checkouts/stripe)

<figure><img src="../../../../.gitbook/assets/Ik4VT0UP5PyIaSt12KgA.jpg" alt=""><figcaption></figcaption></figure>

4. Then, you can **click on the Select events button**

<figure><img src="../../../../.gitbook/assets/MxpMbYZlb9i8iXiIRmcL.jpg" alt=""><figcaption></figcaption></figure>

5. Once you can see the event selection display, you can **search for events** that have the name **Payment Intent** and you can **click on the event**.

<figure><img src="../../../../.gitbook/assets/0LHR70LozLVqfOyaLxke.jpg" alt=""><figcaption></figcaption></figure>

6. Then, you can **tick Select all Payment Intent events** first.

<figure><img src="../../../../.gitbook/assets/8Nf6CxecwtHrQUzb8ZJg.jpg" alt=""><figcaption></figcaption></figure>

7. Next, you can **untick checkbox payment\_intent.amount\_capturable\_updated** and **payment\_intent.partially\_funded** settings

<figure><img src="../../../../.gitbook/assets/JZKdsrfIT6SbXq5SsmlU.jpg" alt=""><figcaption></figcaption></figure>

8. Once done, you can click on the **Add events button**

<figure><img src="../../../../.gitbook/assets/B7pysE3FIrK6VtUIhfRi.jpg" alt=""><figcaption></figcaption></figure>

9. Once you make sure your settings are correct, you can click on the **Add endpoint button**

<figure><img src="../../../../.gitbook/assets/NaHsOzf9DUpkLy5hh1Nk.jpg" alt=""><figcaption></figcaption></figure>

10. If you are taken to this page, you can simply click again on the **Webhooks** button

<figure><img src="../../../../.gitbook/assets/4x6TKKV933cjpI9JZssW.jpg" alt=""><figcaption></figcaption></figure>

11. Later, you will be taken back to the Webhooks page and you can see the endpoint setting you just made earlier. Next, you can **repeat the steps above and enter the second endpoint/webhooks URL**.

<figure><img src="../../../../.gitbook/assets/L7jz5pi7hCvs6MkxqskS.png" alt=""><figcaption></figcaption></figure>

Once finished, you should have **2 endpoints/webhooks URL** as shown below:

<figure><img src="../../../../.gitbook/assets/QTvA4EazoEqf1DyPbjn0.png" alt=""><figcaption></figcaption></figure>

## Setup in Shoppego

1\. Log in to your Shoppego account.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Click on **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. If you have not enabled the payment option for Stripe. Click the **Activate** button in the Alternative Payments for Stripe section.

If you have enabled the payment option for Stripe, click the **Edit** button.

![](../../../../.gitbook/assets/4RR2o2QPI4YtfTS3OtQk.jpg)

5\. Next will appear the display as below, you can fill in the information:

![](../../../../.gitbook/assets/Y7mRZk9lurcPP9Bixg7T.jpg)

* **Display name at checkout: Enter the name of the payment you want (Example Online Payment)**
* **Publishable key: Enter the Publishable key you already got in your Stripe account.**
* **Secret key: Enter the Secret key you already got in your Stripe account.**

6\. Once done make sure you have clicked **Enable** and click the **Save** button.

{% hint style="info" %}
If you want to perform a **real transaction**, kindly <mark style="color:red;">**deactivate**</mark> the **Test Mode** toggle
{% endhint %}

![](../../../../.gitbook/assets/dS3chJnBh2OUueJHYYAi.png)

7\. After **Save** you can make a purchase attempt on your website to see the Stripe payment option during checkout for the setting that you just set just now.
