# Domain Troubleshoot

If your domain has any issues or displays Error 1014, CNAME Cross-User Banned or others, you need to re-check your domain settings. There are 3 things you need to check:

## You need to make sure you have re-added the Custom domain to the Custom domain settings in your store.

For this, you can go to:

1. Log in to your Shoppego account

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **Custom domain**

<figure><img src="../../../.gitbook/assets/77sXwFM14M7Ek2MZcs6h.jpg" alt=""><figcaption></figcaption></figure>

4. Click on the **trash can icon** to delete your domain settings.

<figure><img src="../../../.gitbook/assets/gDQMrIKRVU4IYihtwgrP.jpg" alt=""><figcaption></figcaption></figure>

5. Once you have deleted the domain designation, you can click on the **Add existing domain** button.

<figure><img src="../../../.gitbook/assets/0825t9R6BEsAXRrv5UZn.jpg" alt=""><figcaption></figcaption></figure>

6. Then, you can **re-enter your domain name** and click **Connect**

<figure><img src="../../../.gitbook/assets/ZCtFRdcw1oog2Y893cKW.jpg" alt=""><figcaption></figcaption></figure>

## If you manage your DNS on the Cloudflare platform, you need to make sure your Proxy status setting is set to DNS Only.

For this, you can check the section:

1. Log in to your Cloudflare account

<figure><img src="../../../.gitbook/assets/AsU7Yh7Q530lkakw0ZxL.jpg" alt=""><figcaption></figcaption></figure>

2. Click on your domain and access your domain's DNS record settings again.

<figure><img src="../../../.gitbook/assets/GibT8z87j0ASxllfjR0o.jpg" alt=""><figcaption></figcaption></figure>

3. Make sure the Proxy setting of your CNAME record status is set to `DNS Only` and not `Proxied`

<figure><img src="../../../.gitbook/assets/URCP8K53vV96aUfd8zZf.jpg" alt=""><figcaption></figcaption></figure>

## If your setting has just been made, you need to wait until it fully propagates.

In this situation, the domain setting will usually take 24-48 hours to fully propagate. If your settings has just been done, you will need to wait for the period notified.
