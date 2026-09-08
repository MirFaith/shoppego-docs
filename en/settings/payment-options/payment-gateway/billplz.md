# Billplz

## Billplz account registration

Click on this link <https://sso.billplz.com/users/sign_up> to start registering your Billplz account.&#x20;

{% hint style="success" %}
For the Billplz account registration process, you need to make sure you **already :**&#x20;

* **Have SSM**&#x20;
* **A current Bank Account.**
  {% endhint %}

{% hint style="info" %}
**Account verification, fees, and transactional funds,** they are **fully managed by Billplz.**
{% endhint %}

## Get all the necessary keys from your Billplz account

To connect Billplz with your Shoppego website, you need several keys for the authentication process. Some of the required keys are **Collection ID, Secret Key,** and **X Signature**. To start the process of setting up the **Billplz** payment gateway, you can follow these steps:

1. Log in to your **Billplz/Plzlogin** account.

![](../../../../.gitbook/assets/-MfezlhF2gq4BYpMPCxl.png)

### Get a Collection ID

1\. In the Billplz dashboard section, you can click on **Billing**

![](../../../../.gitbook/assets/-Mff3zrKtGpKuSJl2TsE.jpg)

2\. On the Billing page, you can click on the **Create Collection** button

![](../../../../.gitbook/assets/-Mff6h8Ac2pVzoGQfHxw.jpg)

3\. After you click the button, you will be asked to fill in the **Collection title** field (The name you want to use as a reference for the payment entered on your billing). Once done you can **tick on I understand how reload credit works as stated below** and click **Submit**

![](../../../../.gitbook/assets/-Mff6jxbXRRWMTcix0QF.jpg)

4\. When done you will be able to see the Collection that you created just now. You can click on the **Copy** and save button first or you can just directly enter in Shoppego by referring to the Shoppego setup steps below.

![](../../../../.gitbook/assets/-Mff7HW9mPV-oPwfiC7d.jpg)

### Get the Secret key

1\. In the Billplz dashboard section, you can click on the **down arrow icon** and click **Settings**

![](../../../../.gitbook/assets/-Mff04bXJTn48I79LXdo.jpg)

2\. Next you will be taken to the Settings page, you can click on **BILLPLZ SECRET KEY**

![](../../../../.gitbook/assets/-Mff0tFLpZpxFqGe6rsK.jpg)

3\. After you click on the **BILLPLZ SECRET KEY** tab, you will be able to see your API key for you to enter in the Shoppego system. You can click the **Copy Billplz key** button and save it first or you can just enter it directly in Shoppego by referring to the Shoppego setup steps below.

![](../../../../.gitbook/assets/-Mff1gnd6TTwq5SdFT89.jpg)

### Get X Signature

1\. In the Billplz dashboard section, you can click on the **down arrow icon** and click **Settings**

![](../../../../.gitbook/assets/-Mff04bXJTn48I79LXdo.jpg)

2\. Next you will be taken to the Settings page, you can click on **XSIGNATURE PAYMENT**

![](../../../../.gitbook/assets/-Mff0tFLpZpxFqGe6rsK.jpg)

3\. After you click on the **XSIGNATURE PAYMENT** tab, you will be able to see your XSignature key for you to enter in the Shoppego system. You can click the **Save & Copy XSignature Key** button and save it first or you can just enter it directly in Shoppego by referring to the Shoppego setting steps below.

**\*\***<mark style="color:red;">**Note**</mark>**:** Make sure your **XSignature settings are the same** as the display below to **ensure no issues occur** during your settings. Make sure you **tick on Enable XSignature Payment Completion only.**

![](../../../../.gitbook/assets/-Mff3QAV3C7H7l7TinOC.jpg)

You can save the three keys for use in the next step. The keys you need to keep are:

* Collection ID
* Secret key
* Xsignature

## Setup in Shoppego

For the Billplz payment gateway setting process in Shoppego, you need to first activate the payment gateway and enter the three keys into your payment gateway setting.&#x20;

To start setting up the payment gateway, you can follow these setup steps.

1\. Log in to your Shoppego account.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Next you can click on the **Settings** tab

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. You will be taken to the Settings page and you can click on the **Payment options** button

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

6\. On the Payment options page, you can click the **Activate/Edit** button on the Billplz payment gateway tab.

![](../../../../.gitbook/assets/nIzITxEgKUY59FxQTRsr.jpg)

7\. Next, you will be taken to the setup page for the Billplz payment gateway.

![](../../../../.gitbook/assets/f8d1U8vEPq0X3uYsLsvn.jpg)

8\. By using the key that you have saved in the step to get the key, you can enter all the keys in their space.

![](../../../../.gitbook/assets/BuIXClN9Aqcp3ukTNisk.jpg)

9\. Once done you can click **Save** to save the settings.&#x20;

{% hint style="info" %}
If you want to perform a **real transaction**, kindly <mark style="color:red;">**deactivate**</mark> the **Test Mode** toggle.
{% endhint %}

![](../../../../.gitbook/assets/CeQr3Hz8RZuYI6EjE9Qa.jpg)

## Example on the Website

After completing the setup process, you can try making a purchase on your Shoppego website to see the results.

![](../../../../.gitbook/assets/-MffAaoLUxhh2CHw9A5u.png)
