# Easyparcel

This setting contains 3 parts, namely:

{% hint style="success" %}
This feature is available for **Premium** and **Ultimate** plans.
{% endhint %}

* **Part 1**: On the Easyparcel platform
* **Part 2**: On the Shoppego platform
* **Part 3**: How to use

{% hint style="info" %}
For Easyparcel shipping provider you <mark style="color:red;">**cannot use the Pickup**</mark> function during the **Arrange shipment process**.
{% endhint %}

## Part 1: On the Easyparcel platform

1. Make sure you have registered your **Easyparcel** account first.&#x20;

{% hint style="info" %}
You can register your account here: <https://easyparcel.com/my/en/signup/>​
{% endhint %}

2. Once you have successfully registered you can see your **Dashboard** as shown below.

![](../../../.gitbook/assets/-MKYk7HNlDueVP2NX67M.png)

3\. To get the **Integration ID** you can click on **Integrations** -> **Add New Store.**

![](../../../.gitbook/assets/-MKYkgI90a9x42p5G_Ca.png)

4\. You will be taken to the Integration page. On that page, you can scroll down to click on the **Shoppego icon.**

![](../../../.gitbook/assets/-Mhl4wE2fWYobwz5H9nD.png)

5\. Next, on the same page you will be asked to enter information as shown below.

![](../../../.gitbook/assets/-Mhl6efTJwaAV-996F09.jpg)

<table><thead><tr><th width="164">Field</th><th>Description</th></tr></thead><tbody><tr><td><strong>Shop Name</strong></td><td>Enter the name of your Shoppego store</td></tr><tr><td><strong>Integration ID</strong></td><td>You can save the text in this field to be included in your Easyparcel integration settings in Shoppego in the API key field later.</td></tr><tr><td><strong>Shop URL</strong></td><td>Enter your Shoppego store link</td></tr></tbody></table>

{% hint style="info" %}
You need to **save the Integration ID** for use in the next step.
{% endhint %}

6. Once you have entered all the information, you can click **Submit.**

![](../../../.gitbook/assets/-Mhl7qub0jjnIgrIbLPE.png)

7. After you click the button, you will be taken to a page as shown below. It indicates that your setup has been successful.

![](../../../.gitbook/assets/-Mhl97XgsmWrquFQqKpb.jpg)

8. You need to make sure the toggle on your setting is colored green it indicates this setting is in active state.

## Part 2: On the Shoppego platform

1\.  Log in to your Shoppego Dashboard, then navigate to **Settings > Shipping Providers.**

<figure><img src="../../../.gitbook/assets/6iS5SNhNJ70UnRj5VwHF.jpg" alt=""><figcaption></figcaption></figure>

2. Click on the **Activate/Edit** button on the **Easyparcel** Shipping Provider section.

<figure><img src="../../../.gitbook/assets/n0KzbOmFYnJvfhKrxHuj.jpg" alt=""><figcaption></figcaption></figure>

5\. Once you click the button, you will be taken to a page for you to enter the **Integration ID** you just got in step in part 1 before. You can enter the Integration ID in the **API Key** section.

{% hint style="success" %}
You can also tick on **Enable content** to make sure that in your AWB section there is the name of the product purchased by your customers.
{% endhint %}

![](../../../.gitbook/assets/-MgYtUKcfwkWFOAKvA7X.png)

<table data-header-hidden><thead><tr><th width="197"></th><th></th></tr></thead><tbody><tr><td><strong>Test mode</strong></td><td>You can untick this setting to make sure you can use shipping provider Easyparcel. This setting can be used if you are a developer.</td></tr><tr><td><strong>API Key</strong></td><td>You can enter the <strong>Integration ID</strong> you have already obtained from your Easyparcel account.</td></tr><tr><td><strong>Enable content</strong></td><td>You can activate this toggle to make sure the details of the product purchased by the customer are on the AWB order.</td></tr><tr><td><strong>Enable Easyparcel</strong></td><td>You need to activate this toggle to make sure you can use this Easyparcel shipping provider.</td></tr></tbody></table>

6\. Once you have entered all the data, you can click **Save** and the process of setting up your Easyparcel shipping provider is now successful.

![](../../../.gitbook/assets/-MhlAk2NiUQUhNtVyqHt.jpg)

## Part 3: How to use

1\. You can go back to your **Shoppego Dashboard** section.

![](../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Orders.**

![](../../../.gitbook/assets/3GH71QI9UtN2dyOxtc9r.jpg)

3\. Click on any order you want to arrange the shipment.

![](../../../.gitbook/assets/lasUUilnpBxcaM16QKJd.png)

4\. Click on the **Arrange shipment** button.

![](../../../.gitbook/assets/8iFJZK2k86EUe0IDT4eN.jpg)

5\. Click on **Create shipment.**

![](../../../.gitbook/assets/Q20cobeJSMXU7EOnh1kh.png)

6\. Next you will be able to see the capital/pop up as shown below.

![](../../../.gitbook/assets/eijwKIp7loSpaSpKqnwj.jpg)

7\. You can select the Shipping courier you want to use in the **Choose service column.**

![](../../../.gitbook/assets/7UgrpIvA3lGlaK5MfKmY.png)

8\. Once done click **Submit.**

![](../../../.gitbook/assets/lzXjLIWwTGoazq0u1UB8.png)

9\. If you want to send a tracking number to the customer, you can click on the **Add tracking** button.

![](../../../.gitbook/assets/P0pahq2oeam4KV7xjxgb.png)

## Additional Info

For the **Ultimate** plan, setting your shipping provider will have 2 additional inputs to set.&#x20;

You can refer to the display below for information that you can fill in and how to set it.

![](../../../.gitbook/assets/uDkNagmZM02DDNEY616O.png)

<table data-header-hidden><thead><tr><th width="170.6999364904824"></th><th></th></tr></thead><tbody><tr><td><strong>Default Courier</strong> </td><td><p>You can enter the Courier ID for the shipping courier that you want to use to process the delivery of the customer's order. Among the Courier IDs you can use:</p><ol><li>EP-CR0X for SF Global Express</li><li>EP-CR0B for EMS (Pos Malaysia Berhad)</li><li>EP-CR0A for Poslaju National Courier</li><li>EP-CR05 for Skynet Express (M) Sdn. Bhd.</li><li>EP-CR0Z for CJ Century Logistics Sdn Bhd.</li><li>EP-CR0DE for ZTO</li><li>EP-CR0H for ABX Express (M) Sdn Bhd.</li><li>EP-CR0DP for J&#x26;T Express (Malaysia) Sdn. Bhd.</li></ol></td></tr><tr><td><strong>Auto add tracking code</strong></td><td>You can activate this toggle to ensure that when you Arrange shipment for the customer's order, the <strong>tracking number for the order will be automatically sent</strong> <strong>to your customer</strong> without you having to click on the Add tracking button.</td></tr></tbody></table>
