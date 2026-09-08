# Page Builder

{% hint style="info" %}
Before you follow these steps make sure you :

* Already have the **product you want to make for express cart**
* Already has its **own pages** for you to enter the **express cart function**
* Already subscribed to the **Shoppego Standard plan and above for you to use the page builder function.**
  {% endhint %}

## Get Product Variant ID

1\. Log in to your Shoppego account.

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Products**

![](../../.gitbook/assets/3QYpKlTI5mdyrdLeiYts.jpg)

3\. Click on the Product for which you want to enter the Express Checkout function.

![](../../.gitbook/assets/i3S3XPC8L5SjJS1W4hLs.jpg)

4\. Click on **Express checkout**

![](../../.gitbook/assets/bqs406u5zwylQ0lJnPQ6.jpg)

5\. Select the variant that you want your customers to continue to buy and save the link

![](../../.gitbook/assets/iA6m613XvwBy9vep3yLN.jpg)

6\. Based on the url link, you only need to save the product variant ID.For example the link you get is **<https://mirfaith.myshoppegram.com/cart/57085:1>**

So you need to save **57085** only to use in the next step.

### Settings on Page Builder <a href="page-builder.md#penetapan-pada-page-builder" id="penetapan-pada-page-builder"></a>

1\. Log in to your Shoppego account.

![](../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg)

2\. Click on **Online Store** -> **Pages**

![](../../.gitbook/assets/YW5MKHAFthkHAX6ApmOw.jpg)

3\. Click on the Edit button on the pages where you want to enter the Express Checkout function.

![](../../.gitbook/assets/-MCttEX0SDOWDHKQJMB1.png)

4\. Klik on **Edit with Builder**

![](../../.gitbook/assets/6Ciuq7MNuHo6Vk382w6t.png)

5\. Next, you will be taken to your page builder page. To set the express checkout, you can drag the Button element to the space provided.

![](../../.gitbook/assets/-MCtu97i3dGXrIXrW7bZ.png)

![](../../.gitbook/assets/-MUMbvfcKeFEwZTkkOtu.png)

6\. Click on the Button element that you just dragged and insert into your body content. Type the text you want to appear on the Button element.

![](../../.gitbook/assets/-MUMbvfcKeFEwZTkkOtu.png)

7\. In the URL section you can enter/cart/add? Id = **enter the ID you obtained in step 1**&#x20;

(Example: [https://mirfaith.myshoppegram.com/cart/add?id=57085](https://mirfaith.myshoppegram.com/cart/57085:1))

{% hint style="info" %} <mark style="color:red;">**Attention**</mark>: Make sure to include **add?id=** in your URL.
{% endhint %}

8\. In the **Target column** you can select the **Same Tab** or **New Tab** option while, in the other settings column you can set according to your design.

9\. When done you can click **Preview** to experiment with setting the button.

![](../../.gitbook/assets/-MUMcBoPZtIWDpZnnO1W.jpg)

## Additional Info

If you want to make your customers continue to enter 3 products directly into their cart you can separate each product variant ID with a comma symbol.

For example: /cart /add? Id = **57085,12345**

{% hint style="info" %}
**\*\*A maximum of only&#x20;**<mark style="color:red;">**3 ID variants**</mark>**&#x20;can be entered.**

\*\*If you want to **add quantity** in your **Express Cart**, make sure you modify it and press the **Update Cart button.**
{% endhint %}
