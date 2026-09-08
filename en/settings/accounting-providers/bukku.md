# Bukku

{% hint style="success" %}
This feature is available for **Ultimate** plans only.
{% endhint %}

## On this page:

* [Settings that need to be configured](bukku.md#settings-that-need-to-be-configured)
* [Settings at Bukku](bukku.md#settings-at-bukku)
* [Settings at Shoppego](bukku.md#settings-at-shoppego)
* [How to Perform a Manual Sync](bukku.md#how-to-perform-a-manual-sync)

## Settings that need to be configured:

* Complete your details in your Bukku account.
* Ensure you have entered the TIN and SSM details in your store's Location settings.
* Make sure your customers also have TIN information
* [Obtain the **Access Token** and **Company Subdomain** for your Bukku account.](bukku.md#settings-at-bukku)
* [Do the setting in the Shoppego dashboard](bukku.md#settings-at-shoppego)

{% hint style="danger" %}
**If you or your customers do not have TIN and SSM information, the purchase data will not be synced to your Bukku dashboard.**
{% endhint %}

{% hint style="warning" %}
**You can obtain all the information and settings mentioned above by contacting Bukku.**
{% endhint %}

## Settings at Bukku

1. Log in to your Bukku account

<figure><img src="../../../.gitbook/assets/56sogLRuw9KzVtvzJ31h.jpg" alt=""><figcaption></figcaption></figure>

2. Click on "**Control Panel**".

<figure><img src="../../../.gitbook/assets/VoBTEIIUTZqB9QXex9mD.jpg" alt=""><figcaption></figcaption></figure>

3. Click on "**Integrations**"

<figure><img src="../../../.gitbook/assets/1R9uBmR8LSjlOYvx2yu5.jpg" alt=""><figcaption></figcaption></figure>

4. You can tick the "**API Access**" option. Next, you will be able to view the "**Access token**" and "**Subdomain**" for your Bukku account. Save the "**Access token**" and "**Subdomain**" so you can enter them into the settings section of the Shoppego dashboard.

<figure><img src="../../../.gitbook/assets/IuJrYue3ovoTZFFtPsIr.jpg" alt=""><figcaption></figcaption></figure>

## Settings at Shoppego

Once you have all the information required for the integration, you can follow the steps below to set it up in your Shoppego account.

1. Log in to your Shoppego account.

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **Accounting providers**

<figure><img src="../../../.gitbook/assets/SkN6PTJscDylyOTwFNU8.jpg" alt=""><figcaption></figcaption></figure>

4. Click **Edit/Activate** on **Accounting provider Bukku**

<figure><img src="../../../.gitbook/assets/3icFSMc2mCtkpFnUBWjw.jpg" alt=""><figcaption></figcaption></figure>

5. Then, you can enter all that information into the available fields and click **Save**.

**After entering the "Access Token" and "Company Subdomain" information, you can click the "Test connection" button first to allow the system to retrieve your "Sales account" and "Deposit account" details.**

<table><thead><tr><th width="193">Parameters</th><th>Description</th></tr></thead><tbody><tr><td><strong>Test mode</strong></td><td>You can enable this toggle if you are using a developer account from Bukku itself.</td></tr><tr><td><strong>Access Token</strong></td><td>You can enter the <strong>Access Token</strong> for your Bukku account.</td></tr><tr><td><strong>Company Subdomain</strong></td><td>You can enter a <strong>Subdomain</strong> for your Bukku account.</td></tr><tr><td><strong>Auto-sync paid orders</strong></td><td>You can enable this toggle if you want every paid order placed through your website to be automatically transferred to your Bukku account.</td></tr><tr><td><strong>Include shipping as line item</strong></td><td>You can enable this toggle if you wish to import the customer's order shipping information into your Bukku account.</td></tr><tr><td><strong>Sandbox mode</strong></td><td>You can toggle this switch if you wish to test your integration.</td></tr><tr><td><strong>Sales account</strong></td><td>You can select a Sales account for your Bukku account.</td></tr><tr><td><strong>Deposit account</strong></td><td>You can select the Deposit account for your Bukku account.</td></tr><tr><td><strong>Default tax code ID</strong></td><td>You can enter your tax code (if applicable).</td></tr><tr><td><strong>Tax mode</strong></td><td>You can select your tax mode.</td></tr><tr><td><strong>Invoice default status</strong></td><td>You can set the status for the invoices that will be imported into your Bukku account.</td></tr><tr><td><strong>Enable Bukku</strong></td><td>You need to enable this toggle to ensure you can use this Bukku integration.</td></tr></tbody></table>

<figure><img src="../../../.gitbook/assets/N3aP9QGEdwlnqWnWfz2N.jpg" alt=""><figcaption></figcaption></figure>

6. The integration setup process with the Bukku platform is now complete and successful.

<figure><img src="../../../.gitbook/assets/6oohVFgC07QQ9QFJ4jNP.jpg" alt=""><figcaption></figcaption></figure>

## How to Perform a Manual Sync

The setup tutorial in this section guides you on how to manually sync any order you choose to the Bukku platform.

1. Log in to the **Shoppego Dashboard** -> **Orders** on the left panel.

<figure><img src="../../../.gitbook/assets/3GH71QI9UtN2dyOxtc9r.jpg" alt=""><figcaption></figcaption></figure>

2. **Select** and **click** on the order you want to do the manual sync

![](../../../.gitbook/assets/lasUUilnpBxcaM16QKJd.png)

3. Press the **More button and select Re-sync to Bukku**

![](../../../.gitbook/assets/Mz1Nbvj8AZja7HIIjWmh.jpg)

4\. Once completed, your order should be visible in the Bukku platform

![](../../../.gitbook/assets/MyRtuJOwRGOOguxxSPLt.jpg)

You can view every order received from Shoppego on the Bukku platform under the following section:

**Bukku Dashboard > Sales > Invoice > All**
