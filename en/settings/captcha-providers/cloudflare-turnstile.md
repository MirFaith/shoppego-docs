# Cloudflare Turnstile

Before you follow the steps below, make sure you have a Cloudflare Turnstile account. If you don't have one yet, you can register at the link below:

{% embed url="<https://dash.cloudflare.com/sign-up>" %}

There are 2 pieces of data you need to integrate Cloudflare Turnstile with the Shoppego system:

* Site key
* Secret key

## Settings on Cloudflare Turnstile

1. You can log in to your Cloudflare dashboard first.

<figure><img src="../../../.gitbook/assets/88PyYDqTx9CQobeOYWFX.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Application security** and **Turnstile**

<figure><img src="../../../.gitbook/assets/jMYVhxd0kOw1Nsu5LWK6.jpg" alt=""><figcaption></figcaption></figure>

3. Then, you can click **Add widget**

<figure><img src="../../../.gitbook/assets/OwAfBlsf5Av0D5fUgM0i.jpg" alt=""><figcaption></figcaption></figure>

4. Later, you will be able to see the settings you need to make. For "**Widget name**" you can enter a name text for your reference later.

<figure><img src="../../../.gitbook/assets/z1quo5AFcYn9T8BALlyb.jpg" alt=""><figcaption></figcaption></figure>

5. Then, you need to set the Hostnames by clicking on the "**Add Hostnames**" button.

<figure><img src="../../../.gitbook/assets/ODp3ptkcFhM3j6k6J0bH.jpg" alt=""><figcaption></figcaption></figure>

If you **do not have a hostname/domain set in your Cloudflare account**, you can **enter your hostname/domain in the Custom hostname section (Highlighted in yellow)**.\
\
If your **hostname/domain is already in your Cloudflare account**, you can **continue to make the selection as shown (Highlighted in green)**.\
\
Once done, click **Add**

<figure><img src="../../../.gitbook/assets/vyuUuwR0qbs2EVQB0Fbp.jpg" alt=""><figcaption></figcaption></figure>

6. Next, for the "**Widget Mode**" setting, you can set it to whatever you want. We recommend setting it to "**Invisible**".

<figure><img src="../../../.gitbook/assets/e5mz4NeznMMUAx7QyxX5.jpg" alt=""><figcaption></figcaption></figure>

7. Once finished, click **Create**

<figure><img src="../../../.gitbook/assets/R7oFT0Qg3wWEUyg8FAIn.jpg" alt=""><figcaption></figcaption></figure>

Now, you can see the "**Site key**" and "**Secret key**", which you need to enter in the settings on the Shoppego dashboard later.

<figure><img src="../../../.gitbook/assets/NBMafyuwTpKwTU50F3MY.jpg" alt=""><figcaption></figcaption></figure>

## Setting up in Shoppego

1. Log in to your Shoppego account.

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **Captcha providers**

<figure><img src="../../../.gitbook/assets/WTAu7U4FoU0pJaCJ60S7.jpg" alt=""><figcaption></figcaption></figure>

4. Click on the **Activate/Edit** button for the provider type "**Cloudflare Turnstile**"

<figure><img src="../../../.gitbook/assets/cbXRJ3HCKz0wbjySNxLu.jpg" alt=""><figcaption></figcaption></figure>

5. Then, you can **enter your Cloudflare Turnstile Site key** and **Secret key** in the spaces provided. Make sure to **tick the Enable toggle** and click **Save**

<figure><img src="../../../.gitbook/assets/sE3K4qVvNryEZTIXvLBg.jpg" alt=""><figcaption></figcaption></figure>

Now your setup is complete. You should be able to see the Cloudflare logo (If you are using "Widget mode" "Manage") displayed on the "Forms" page and also the "Login" page of your website.

<figure><img src="../../../.gitbook/assets/in9s3cRCKwnP8DMIzgh2.jpg" alt=""><figcaption></figcaption></figure>
