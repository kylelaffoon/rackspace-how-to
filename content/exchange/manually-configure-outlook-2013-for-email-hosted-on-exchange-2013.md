---
node_id: 3848
title: Manually configure Outlook 2013 for email hosted on Exchange 2013
type: article
created_date: '2014-01-10'
created_by: Mawutor Amesawu
last_modified_date: '2015-01-19'
last_modified_by: Jered Heeschen
product: Microsoft Exchange
product_url: exchange
---

Use the following steps to set up your Microsoft Exchange 2013 mailbox
with your Outlook 2013 email client.

1. Click the Windows **Start** button, select **Control Panel**, and
then click **Mail** (32-bit).

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step1_0.png" width="620" height="276" />

*Note: Depending on the version of Windows you're running, you might
need to switch to* **Classic view to find the **Mail** entry or it might
be labeled **32-Bit***.*

2. Click **Show Profiles**, click **Add**, enter a name for this
profile, and then select **OK**.

3. On the Auto Account Setup page of the Add New Account wizard, select
**Manually configure server settings or additional server types**, and
then click **Next**.

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step2_0.png" width="694" height="489" />

4. On the Choose Service page, select **Microsoft Exchange or compatible
service**, and then click **Next**.

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step3_0.png" width="694" height="492" />

5. On the Server Settings page, perform the following actions:
     A. In the **Server** text box, type **outlook**.
     B. Select the  the **Use Cached Exchange Mode** check box.
     C. In the **User Name** text box, enter your entire email
address.
     D. Click **More Settings**.

*Note: Outlook 2013 offers the option to limit the amount of data that
is downloaded to your local machine.  This can be adjusted, using the
"Mail to keep offline slider."* **You can select caching for 1 month, 3
months, 6 months, 1 year, 2 years, and &ldquo;all.&rdquo;* By default, Outlook 2013
only synchronizes twelve (12) months of email to your Offline Outlook
Data (.ost) file from the Exchange server. In this example, if you have
email items older than 12 months in your Exchange mailbox, they reside
only in your mailbox on the server.*

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step4_0.png" width="694" height="492" />

6. In the Microsoft Exchange dialog box, click the **Connection** tab
and select the **Connect to Microsoft Exchange using HTTP** check box.
Then, click **Exchange Proxy Settings**.

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step5_0.png" width="354" height="438" />

7. In the Microsoft Exchange Proxy Settings dialog box, perform the
following actions**:
    ** A. In the **Use this URL to connect to my proxy server for
Exchange** text box, enter **mex06.emailsrvr.com**.
     B. Select both the **On fast networks** and **On slow networks**
check boxes.
     C. Under **Proxy authentication settings**, select **Basic
Authentication**.
     D. Click **OK**.

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step6_0.png" width="483" height="411" />

8. In the Microsoft Exchange dialog box, click **Apply** and then click
**OK**.

9\. On the Server Settings page, click **Check Name**, type your
password, and then click **OK**.



*Note: If you receive a pop-up message asking you to select your mailbox
from a list, select your mailbox and click OK.*



Your name will then be highlighted and a line will appear under the
**User Name**  field which indicates your profile has been configured.



*Note: The server name resolves to a unique string that is different
with every mailbox. Do not attempt to replicate this information with
other accounts.*

10\. Click **Next**, and on the next page, click **Finish**.

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step7_0.png" width="694" height="491" />

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/Step8_0.png" width="694" height="490" />

11\. Open Outlook to select your new Exchange profile.

