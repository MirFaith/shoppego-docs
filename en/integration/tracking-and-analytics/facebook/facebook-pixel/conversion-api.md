# Conversion API

In Shoppego, you can set the **Conversion API** on your **Facebook Pixel**. With this **Conversion API,** the data you will receive through your **Facebook Pixel will be&#x20;**<mark style="color:red;">**more accurate.**</mark>

{% hint style="info" %}
<mark style="color:red;">\*\*Note\*\*</mark>: This Conversion API function is only available on the Ultimate plan.
{% endhint %}

## Get an Access Token

To set up the **Facebook Conversion API**, you only need to enter the **Conversion API token** on the **Shoppego** platform. Very easy!

1. In your pixels section, select the pixels you want to use click on the Open in **Events Manager** tab

![](../../../../../.gitbook/assets/FSiHXv4nvG5lncAv6Hvp.png)

2\. Next, you will be taken to a new site. On this page click on the **Settings** tab

![](../../../../../.gitbook/assets/ivucXpjKSWqlbRZ90J3p.png)

3\. On the settings tab, press **Get Started** in the Set up Manually column.

{% hint style="info" %}
<mark style="color:red;">\*\*Note\*\*</mark>: \*If the button <mark style="color:red;">\*\*cannot be pressed\*\*</mark> make sure your email is set in \*\*Ads Manager\*\*.\*
{% endhint %}

![](../../../../../.gitbook/assets/4xpNvfEB57R50vfJVEFR.png)

4. _Click **Continue**._

![](../../../../../.gitbook/assets/IJAzmm5MQRmDIgucPpuk.png)

5\. Tick ​​on the **Purchase event** and **Initiate checkout or Leads.** After you tick both events, you can click **Continue**

{% hint style="info" %}
For websites that use the purchase function, it is recommended that you use the Purchase and Initiate checkout event. For websites that only use the leads"Forms" function, it is recommended that you use the Leads event.
{% endhint %}

![](../../../../../.gitbook/assets/ZrcIahwPbnHNOIVUStWl.png)

6\. Make sure **the setting of event details for your Initiate Checkout event is the same as the picture below**. Once you make sure it is the same, you can click on the **Continue** button

{% hint style="info" %}
For the Leads event, you can still follow all the parameters.
{% endhint %}

![](../../../../../.gitbook/assets/pU0rWUpX4K7jS5oXCswQ.jpg)

7\. Next, make sure the **setting event details for the Purchase event is as shown below**. Once you make sure it is the same, you can click **Continue**

![](../../../../../.gitbook/assets/xpFlA5F84j1RYKmbfvxp.jpg)

8\. On this page, you can make sure it is the same as on your settings display. Once you make sure it is the same you can click **Continue**

![](../../../../../.gitbook/assets/4loA0sQeqIbxXPpcEawf.jpg)

9\. Click **Finish** and then with that your setting is complete.

![](../../../../../.gitbook/assets/KVU2ciTEpaRxQ4sxm09Z.png)

10\. Next, you can click again on the **Settings** tab

![](../../../../../.gitbook/assets/ivucXpjKSWqlbRZ90J3p.png)

11\. Get a token for your API conversion by pressing **Generate access token**. **You need to save this access token for assignment in Shoppego**.

![](../../../../../.gitbook/assets/vl1PzDKHyLE2JCoX8yGA.png)

### Setup in Shoppego <a href="#setup-pada-commerce" id="setup-pada-commerce"></a>

Once you have access to the Conversion API token. You are required to enter the access token into your Shoppego account.

1. Log in to your Shoppego accoun&#x74;**.** Click on **Settings -> General**. Enter your access token in the **Facebook Pixel Access** **Token** field and click the Save button

![](../../../../../.gitbook/assets/btd9gZu6SW0PSXTjCt4C.jpg)

## Perform a Test event on the setting

1\. In your pixels section, select the pixels you want to use click on the Open in **Events Manager** tab

![](../../../../../.gitbook/assets/FSiHXv4nvG5lncAv6Hvp.png)

2\. Next, you will be taken to a new site. On this page click on the **Test events** tab

![](../../../../../.gitbook/assets/Z5hGY7uYJKKkn8HvLgf2.png)

3\. In the **Test server event** tab you can save your **Test event code** by clicking on your test code box.

![](../../../../../.gitbook/assets/cEAeSdvw3gffJFfeLDen.png)

4\. Next, you need to enter this code in the settings in Shoppego. You will need to Log back into your Shoppego account.

![](../../../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

5\. Click on **Settings -> General**. Make sure your Test event code is in the **Facebook test\_event\_code** field and click the Save button

![](../../../../../.gitbook/assets/LIGt5QICVDtt1z6hg2H5.jpg)

6\. Next, you need to return to **Test Events** and enter your store domain in the **Test browser events**. When done click on the Open Website button.

![](../../../../../.gitbook/assets/pF07CTTqfRXeGRLcHIBa.png)

After you click the button, you will be taken to your **website page.** You can **refresh** first to ensure that the **page view even**t can be **triggered** on your **test event settings**. If it can be triggered you can **proceed to another trigger event process**.

If your setting is successful, at the test event you will receive **Initiate checkout** and **Purchase** **events along with deduplication** information that comes from the **Server**.

![](../../../../../.gitbook/assets/vGpe8jLJQjSP4AVM7djC.jpg)

{% hint style="info" %}
**\*\* After you have finished setting this test event. You need to&#x20;**<mark style="color:red;">**delete the facebook test event code**</mark>**&#x20;in your Commerce settings. \*\***
{% endhint %}
