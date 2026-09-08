# Paypal

{% hint style="info" %}
**Account verification, fees, and transactional funds,** they are **fully managed by Paypal.**
{% endhint %}

## Paypal account registration

Click on this link <https://www.paypal.com/my/webapps/mpp/account-selection> to start registering your Paypal account.&#x20;

{% hint style="info" %}
\*\*<mark style="color:red;">**Note**</mark>: For the Paypal account registration process, make sure you select as a **Business Account**.
{% endhint %}

![](../../../../.gitbook/assets/NWcU8kF63R7C7WPGaOf5.png)

## Get all the required keys from the Paypal account

To connect Paypal with the Shoppego website, you need some keys for the verification process. Among the keys required are **Client ID** and **Client Secret**.&#x20;

To start the Paypal payment gateway setup process you can follow these setup steps:

1\. Log in to your Paypal account via this link <https://developer.paypal.com/developer/applications>

![](../../../../.gitbook/assets/GYwY2u4F4toyf4566jjx.png)

2\. Next on the Paypal dashboard section, you can click on the **LIVE** tab

![](../../../../.gitbook/assets/lK3RcsIozIAKADhI0Kxs.png)

3\. Next you will be able to see your **Create App** button there. You can click on the button.

![](../../../../.gitbook/assets/1dVRv35uSeUoo5aJU6Cy.png)

4\. On this screen, you are required to enter the **App Name**. It is recommended to enter your own business name. Next, press the **Create App** button.

![](../../../../.gitbook/assets/FJpj8cY4fu8avAsphcWu.png)

5\. Next, after you click on **Create app** a new screen will appear. In this view, you are required to create a webhook setting.

![](../../../../.gitbook/assets/6j3TQsL3oeYEDhqTpSKy.png)

6\. On this display you are **required to enter the URL name <https://subdomain.myshoppegram.com> of your Shoppego account that was given for free during the registration of your Shoppego account into the Webhook URL field**.

You can find your subdomain URL in the following section:\
Dashboard Overview Shoppego -> **Settings** -> **Custom domain** -> **Subdomain**

<figure><img src="../../../../.gitbook/assets/i6ChVkQCDHAFSqE60OI8.jpg" alt=""><figcaption></figcaption></figure>

For example, **<https://hartamas.myshoppegram.com/webhooks/payments/callback/checkouts/paypal>** and **tick** on **Checkout > Checkout order approved**

![](../../../../.gitbook/assets/9n6gqzfValY7ovYOdgLt.jpg)

## Setup in Shoppego

For the process of setting the Paypal payment gateway in Shoppego, you need to first activate the payment gateway and enter both keys into your payment gateway settings.

To start setting up the payment gateway, you can follow these setup steps.

1\. Log in to your Shoppego account.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Next you can click on the **Settings** tab

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. You will be taken to the Settings page and you can click on the **Payment options** button

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. On the Payment options page, you can click the **Activate/Edit** button on the Paypal payment gateway tab.

![](../../../../.gitbook/assets/xLLfT2NuG0oYhLzQQK0l.jpg)

5\. Using the key provided on the **Paypal Dashboard** -> **My App & Credentials** -> **LIVE** -> **Select the App Name you created**. **Copy the Client ID** and **Secret Key**, **enter it in the Paypal field in Shoppego**. **Tick ​​on the Enable toggle** button and click the **Save** button

{% hint style="info" %}
If you want to perform a **real transaction**, kindly <mark style="color:red;">**deactivate**</mark> the **Test Mode** toggle
{% endhint %}

![](../../../../.gitbook/assets/LxPUTyR1ovRfS2rhuJEQ.jpg)

## Example on the Website

After completing the setup process, you can try making a purchase on your Shoppego website to see the results.

![](../../../../.gitbook/assets/aF8tmfdgtRCRp186HLZ7.png)
