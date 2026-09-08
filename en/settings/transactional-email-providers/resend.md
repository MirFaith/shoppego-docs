# Resend

Resend is an email sending platform. It allows you to send your email notifications using your own domain.

For integration with the Resend platform, you can refer to this tutorial provided.

## Before You Begin:

* Make sure you already have your own domain
* Make sure you have access to set DNS records for your domain
* Make sure you have registered for a Resend account

## Add Domain

1. Log in to your Resend account.

<figure><img src="../../../.gitbook/assets/MYgLJqe0w7u9auVgI2R4.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Domains**

<figure><img src="../../../.gitbook/assets/6weGTSFpTu8RBKnm9Owd.jpg" alt=""><figcaption></figcaption></figure>

3. Click **Add domain**

<figure><img src="../../../.gitbook/assets/88N0k1iHtdrQ8FI9CdVY.jpg" alt=""><figcaption></figcaption></figure>

4. Then, you can **enter your domain name** and for the "**Region**" setting you can select "T**okyo (ap-northeast-1)**". Once done click **Add** domain

<figure><img src="../../../.gitbook/assets/yi9pKRW3K7O1TZshMJN6.jpg" alt=""><figcaption></figcaption></figure>

### Verify domain

1. Next, you need to verify the domain.

<figure><img src="../../../.gitbook/assets/cb4BR3x9sZJfg3YnQLm5.jpg" alt=""><figcaption></figcaption></figure>

2. If you manage your domain on **Cloudflare**, you can directly click "**Auto configure**". For **other platforms**, you need to do **Manual setup**.\
   \
   For this tutorial, we will continue to do the setting by "**Manual setup**".

<figure><img src="../../../.gitbook/assets/pElMw9z0mWxgcLVLLhPd.jpg" alt=""><figcaption></figcaption></figure>

3. Then, you need to follow all the settings they ask you to make on your domain's DNS record. You only need to set "**Domain Verification**" and "**Enable Sending**".

<figure><img src="../../../.gitbook/assets/7DpMAZfSNR1oJY1D7r2k.png" alt=""><figcaption></figcaption></figure>

4. You can click on "**Forward instruction**" at the bottom and **enter your email**.

<figure><img src="../../../.gitbook/assets/tActekLduQjTPWRZ39H6.jpg" alt=""><figcaption></figcaption></figure>

5. **After you have made the desired settings for your domain's DNS records**, you can click on "**Verify DNS Records**"

<figure><img src="../../../.gitbook/assets/J5NFmdK0ObqH93kHblua.jpg" alt=""><figcaption></figcaption></figure>

6. Then, you need to **wait until all verification processes are reviewed by their system**.\
   \
   If all your settings are complete and there are no issues, you will see a display like the one below.

<figure><img src="../../../.gitbook/assets/lbnGqjSNuDZI0ELoYceD.png" alt=""><figcaption></figcaption></figure>

## Create API Key

1. Log in to the Resend dashboard

<figure><img src="../../../.gitbook/assets/MYgLJqe0w7u9auVgI2R4.jpg" alt=""><figcaption></figcaption></figure>

2. Click on the **API Keys** tab

<figure><img src="../../../.gitbook/assets/qTcF5Lp1hnxac83QxpGU.jpg" alt=""><figcaption></figcaption></figure>

3. Click **Create API Keys**

<figure><img src="../../../.gitbook/assets/uyBoGvI1xp1BIWI0lOte.jpg" alt=""><figcaption></figcaption></figure>

4. Later you will be able to see 1 popup:\
   \- Enter your API Keys name.\
   \- Then, you can set "Permission" to "Full access".\
   \- For domain settings, you can choose whether you want to set it to only 1 domain or all of your domains.\
   \
   When finished click **Add**

<figure><img src="../../../.gitbook/assets/yuCJDR21FMxCK8modkQ8.jpg" alt=""><figcaption></figcaption></figure>

5. Then, you can **copy and save your API key** to use in the settings on the Shoppego dashboard later.

<figure><img src="../../../.gitbook/assets/lDfStIAhUyEIrAgsinFc.jpg" alt=""><figcaption></figcaption></figure>

## Settings in Shoppego

1. Log in to your Shoppego account

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **Transactional email providers**

<figure><img src="../../../.gitbook/assets/qPlS7UVCv05zHOfQ0wXy.jpg" alt=""><figcaption></figcaption></figure>

4. Click **Activate/Edit** on the **Resend** tab.

<figure><img src="../../../.gitbook/assets/pEyN2p2Fjgft2lgPUaoX.jpg" alt=""><figcaption></figcaption></figure>

5. **Enter your API key** and **tick the Enable toggle**. Then, you can **Save** the setting.

<figure><img src="../../../.gitbook/assets/gzpynbHgRUwBh9JvBcSp.jpg" alt=""><figcaption></figcaption></figure>

Now your integration setting is complete.

## Additional Information

Make sure you have entered the correct notification email for sending your email notifications later.

You can check the setting in the section:

1. Log in to your Shoppego account

<figure><img src="../../../.gitbook/assets/lCN7aw3FznaFFoOAyya2.jpg" alt=""><figcaption></figcaption></figure>

2. Click on **Settings**

<figure><img src="../../../.gitbook/assets/VsK9zs6aZtUfKK1hcCiM.jpg" alt=""><figcaption></figcaption></figure>

3. Click on **General**

<figure><img src="../../../.gitbook/assets/anealodqyXwHTuzr4AHU.jpg" alt=""><figcaption></figcaption></figure>

4. Make sure the "**Notification & Reply-to Email**" setting is set to the email that **uses the domain in your Resend account**.\
   \
   For example, in Resend you use the domain kedaisaya.com, so in that setting, you need to enter an email like this: <hello@kedaisaya.com>

<figure><img src="../../../.gitbook/assets/GKrjaWn3Tig16nShP4oj.png" alt=""><figcaption></figcaption></figure>
