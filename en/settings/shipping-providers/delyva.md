# Delyva

This setup consists of 3 parts, namely:

{% hint style="success" %}
This feature is available for **Premium** and **Ultimate plans**.
{% endhint %}

* **Part 1**: On the Delyva platform
* **Part 2**: On the Shoppego platform
* **Part 3**: How to fulfill an order

## Part 1: Setting up Delyva

Please ensure that you already have a **Delyva account**.

{% hint style="info" %}
[Click here](https://my.delyva.app/customer/signup) to register for [Delyva](https://my.delyva.app/customer/signup). Delyva registration is free.
{% endhint %}

1. Please **log in** to your **Delyva** account.

![](../../../.gitbook/assets/-MgdLFQeW5N0XczyliuB.png)

2\. In the **Dashboard**, click on your Name in the top right corner.

![](../../../.gitbook/assets/-Mgd8zqqdCshPUiMK6wV.jpg)

3. Click on the **Settings** tab.

![](../../../.gitbook/assets/-Mgd9iQxlbwkQKSALX0_.jpg)

3\. Click on the **API Integrations** tab.

![](../../../.gitbook/assets/-Mgd9az3DgHdRVycx74q.jpg)

4. On the **API Integrations page**, you can obtain **all three keys required** to integrate with the Shoppego system.
   1. [Company ID](delyva.md#1-company-id)
   2. [Customer ID](delyva.md#2-customer-id)
   3. [API Key](delyva.md#3-api-key)

### **1 : Company ID**

1\. In the API Integrations page, you can **find your Company ID** value. You can refer to the display below:

![](../../../.gitbook/assets/-MgdC6tg-mHtVokj0LHm.jpg)

### **2 : Customer ID**

1\. On the **API Integrations** page, you can find your **Customer ID** value. You can refer to the display below:

![](../../../.gitbook/assets/-MgdEMDlxN9H5s_VaOH7.jpg)

### **3 : API Key**

1\. On the **API Integrations** page, you can click the "**Add new key**" button.

![](../../../.gitbook/assets/-MgdFXb97xtmQ44PDA9W.jpg)

2\. Then a pop-up will appear for you to **enter a name** for your **API key**.

{% hint style="info" %}
You can just **enter any name** that you prefer as your reference.
{% endhint %}

![](../../../.gitbook/assets/-MgdFbMrvwWrJlUbgQtC.png)

3\. Once done, you can click on the "**Create & View**" button.

![](../../../.gitbook/assets/-MgdFkl2Dnl4kFXgkpT5.jpg)

4.There will be a display showing your **API key**.

![](../../../.gitbook/assets/-MgdFzFKCk9h3VHlF3uC.jpg)

5.You can click on the **Copy button** to copy the **API key** and paste it into the Shoppego system.

![](../../../.gitbook/assets/-MgdG43WOjSVxXWpvML9.jpg)

6\. Once you have entered or saved the **API key**, you can click **Done**.

![](../../../.gitbook/assets/-MgdGHFp4tTyAB00Eyjy.jpg)

## Part 2: Setup in Shoppego

1\. Log in to your **Shoppego Dashboard**, then navigate to **Settings > Shipping Providers.**

<figure><img src="../../../.gitbook/assets/6iS5SNhNJ70UnRj5VwHF.jpg" alt=""><figcaption></figcaption></figure>

2. Click on the **Activate/Edit** button on the **Delyva** Shipping Provider section.

![](../../../.gitbook/assets/GBXIUwyGh8TJ4AlziBEn.jpg)

3. Enter the **Company ID, Customer ID,** and **API key** that you obtained in the Setup step of[ Part 1.](delyva.md#part-1-setting-up-delyva)

![](../../../.gitbook/assets/bjhyk72RwJecx6Ra8OD7.jpg)

4. Once you have entered all the information, click on the **Save** button. Please refer to the image below.

{% hint style="success" %}
Make sure to check the **Enable Delyva (Matdespatch)** box by clicking on it.
{% endhint %}

![](../../../.gitbook/assets/-MgdKuYBguyt7MrLiEgu.jpg)

Now your Shoppego platform is <mark style="color:green;">**ready to be connected**</mark> with the Delyva platform.

{% hint style="success" %}
Make sure your account has **enough credit** to use the **Delyva** system.
{% endhint %}

## Part 3: How to Fulfill an Order

Guide to setting up order management in the Shoppego platform to **generate an Airway Bill** on Delyva without needing to log in.

1. Log in to the **Shoppego Dashboard** and click on **Orders** in the left panel.

![](../../../.gitbook/assets/lasUUilnpBxcaM16QKJd.png)

2. **Select** and click on the order that was made for delivery using **Delyva** and the display will appear as below. Click on the '**Arrange Shipment**' button.

![](../../../.gitbook/assets/8iFJZK2k86EUe0IDT4eN.jpg)

3. Click the blue '**Create Shipment**' button in the upper right corner. Click on '**Select Shipment Provider**' and choose **Delyva**.

![](../../../.gitbook/assets/Snrqd2SFXavpmDkJNkAO.jpg)

4\. Click on '**Choose Services**'. **Click** on any courier service you want to use. The price has been determined according to the address provided in the order.

![](../../../.gitbook/assets/dL3zOiXfkmN22agi99V7.jpg)

5.Next, click on '**Method**' and choose '**Dropoff**' or '**Pickup**'.

{% hint style="info" %}
**Method** :

* **Dropoff** - You will personally go to the nearby post office and send the item.
* **Pickup** - The courier will send a vehicle to pick up the item at the location specified in your Location settings
{% endhint %}

![](../../../.gitbook/assets/vNNJgWxQMXlok1HCGm2z.jpg)

{% hint style="info" %}
**Note**: If you are using **Cash On Delivery (COD)** delivery, make sure you have selected the COD service type and turned on the '**Enable COD**' toggle.
{% endhint %}

<figure><img src="../../../.gitbook/assets/WhMewIhW0XYkCKHoNP3V.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Usually, the **Pickup method** will be selected to make it easier for sellers.
{% endhint %}

6. When the **Pickup method** is selected, a schedule will be displayed for choosing the date of pickup by the courier. Click on the desired date and then click the '**Submit**' button. Refer to the image below.

<figure><img src="../../../.gitbook/assets/LmBo0DYgwr9lUYZ68hpu.jpg" alt=""><figcaption></figcaption></figure>

7. After clicking the '**Submit**' button, your order will automatically receive a tracking number as shown in the image below.

{% hint style="info" %}
An **Airway Bill (AWB)** for this order has been automatically generated, and you only need to print the **AWB** from the **Delyva** platform.
{% endhint %}

<figure><img src="../../../.gitbook/assets/o21IcxEDTN7Sf7g0Qk7Y.jpg" alt=""><figcaption></figcaption></figure>

8. After completing the '**Add Shipment**' process, check the **Delyva Dashboard** to ensure that the information that appears is the same.

![](../../../.gitbook/assets/-MBlPjueEZZL-DnOIsfS.jpg)

9. **Update the tracking information** to the customer after the courier has picked up the item. **Click** on that order, and the display will be as shown in the image below. Next, click on '**Add Tracking'.**

<figure><img src="../../../.gitbook/assets/aTPJ6KaspOVaZY2GIL59.jpg" alt=""><figcaption></figcaption></figure>

10. Click on '**Carrier**' and select the name of the **Carrier(1)** for that order, which was set during the Add Shipment process. Click the '**Save' button(2)**.

<figure><img src="../../../.gitbook/assets/L6y2edTzdQi6Ox49ixM7.jpg" alt=""><figcaption></figcaption></figure>

11. When the '**Save**' button is pressed, your customers will **automatically receive their tracking number via email** from the Shoppego system. This tracking number will **also appear** on the **right side of your order** when it is saved.

<figure><img src="../../../.gitbook/assets/Y1xJmZiu7VwK8wIwyXwj.jpg" alt=""><figcaption></figcaption></figure>

12. You can also check the orders list to see that **the tracking number has been assigned** to that order.

{% hint style="info" %}
Click on the **'i'** icon in the Fulfillment to **check the tracking number** for that order.
{% endhint %}

<figure><img src="../../../.gitbook/assets/dB6BJxLn7QIPN2RzeJcs.jpg" alt=""><figcaption></figcaption></figure>

13. **To print the Airwaybill (AWB)**, you need to **log in to your Delyva account** and click on the printer icon to print the AWB.

![](../../../.gitbook/assets/-MBlPjueEZZL-DnOIsfS.jpg)

14. Click on the **print icon** to **print this Airwaybill (AWB)** and display it on your parcel.

![](../../../.gitbook/assets/-MBlPoIT8xIsmEUcxDMN.jpg)
