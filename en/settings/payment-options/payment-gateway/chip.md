# Chip

To use Chip please make sure you have created a Chip account first.

{% hint style="success" %}
For the **Chip account registration** process, you need to make sure you **already:**

* **Have SSM.**&#x20;
* **A current Bank Account.**
  {% endhint %}

{% hint style="info" %}
**Account verification, charges and transaction money are fully managed by Chip.**
{% endhint %}

## Chip Settings

To integrate Chip payment gateway with Shoppego, you need to get **Brand ID**, **Secret key.**\
\
If you have not yet registered a Chip account, you can use this link:\
<https://onboarding.chip-in.asia/>

### Get Brand ID

1. Log in to your Chip account.

<figure><img src="../../../../.gitbook/assets/vG67oKqRpQdGbzkyFYnK.png" alt=""><figcaption></figcaption></figure>

2. Click on the **Developers** button/text.

<figure><img src="../../../../.gitbook/assets/y3xhqMXHs6ajXiBz50HV.jpg" alt=""><figcaption></figcaption></figure>

3. Click on the **Brands** button/text

<figure><img src="../../../../.gitbook/assets/OBbjjBjC1apTBFfGRpi7.jpg" alt=""><figcaption></figcaption></figure>

4. Then, you can **copy your Brand ID** as shown below. You need to **save this Brand ID for setting in Shoppego later.**

<figure><img src="../../../../.gitbook/assets/ylGIpR2ZGvgy3ROV7N35.jpg" alt=""><figcaption></figcaption></figure>

### Get Secret Key

1. From the **Developers** page, you can also click on the **Keys** button/text.

<figure><img src="../../../../.gitbook/assets/fafsVFJDy1U16c71bHwr.jpg" alt=""><figcaption></figcaption></figure>

2. Then, make sure the V**iew/Viewing test data toggle is deactivated (grey)**.

<figure><img src="../../../../.gitbook/assets/lj69nkTqv7tDNbHCkSqm.jpg" alt=""><figcaption></figcaption></figure>

3. Next, you can click on the **New live key** button.

<figure><img src="../../../../.gitbook/assets/MlaNWaQdHZbP20IjTp2P.jpg" alt=""><figcaption></figcaption></figure>

3. Then, you will be asked to **enter the Key title in the field that has been provided**. This key title acts as a reference for you to know where this key is used later. For example we enter Shoppego and after that click **Create**.

<figure><img src="../../../../.gitbook/assets/iZ55pW97NGpQRiGIp2vM.jpg" alt=""><figcaption></figcaption></figure>

4. Once you have created the key, you can **click on the key again** and you can click on the **Copy** button/text. You need to **save this key to set it up in Shoppego later.**

<figure><img src="../../../../.gitbook/assets/4U1yAruNefJebqkM7PN5.jpg" alt=""><figcaption></figcaption></figure>

## Settings in Shoppego

1\. Log in to your Shoppego account.

![](../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Settings**

![](../../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg)

3\. Click on **Payment options**

![](../../../../.gitbook/assets/CA5qmbxGnMXdjUXh5W4M.jpg)

4\. If you have not activated the payment option for Chip. Click the **Activate** button on the **Alternative Payments** section for Chip. If you have activated the payment option for Chip, click the **Edit** button.

![](../../../../.gitbook/assets/Lh0e3bJ2ljzdooESDyvW.jpg)

5\. Next, a display will appear as below, you can fill in the information:

![](../../../../.gitbook/assets/KRk9znifIZqSXZssPLaS.jpg)

* **Display name at checkout : Enter the name of the payment you want (Example Chip)**
* **Secret key : Enter the Secret key that you have obtained in your Chip account.**
* **Brand ID : Enter the Brand ID that you have obtained in your Chip account.**

6\. After finishing, make sure you have clicked **Enable** and click the **Save** button.

{% hint style="info" %}
**For information, the&#x20;**<mark style="color:red;">**Test mode toggle**</mark>**&#x20;is only used by Developers. For Shoppego users, please make sure you&#x20;**<mark style="color:red;">**deactivate**</mark>**&#x20;the toggle.**
{% endhint %}

![](../../../../.gitbook/assets/VxNwkeQT1Ci4gDLYEJiu.jpg)

After saving you can make a purchase attempt on your website to see the Chip payment option during checkout for the setting you just set a moment ago.
