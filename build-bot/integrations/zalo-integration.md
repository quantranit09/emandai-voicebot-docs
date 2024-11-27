# Zalo Integration

**Step 1:** Create an OA account&#x20;

You need an OA account to use the functions on the OA API system.

&#x20;If you don't have an OA account, you can create a new one [here](https://oa.zalo.me/home).

<figure><img src="../../.gitbook/assets/image (797).png" alt=""><figcaption><p>After clicking "here", you will be redirected to the link as shown above</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (798).png" alt=""><figcaption><p>Click <strong>Create a new Official Account</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (799).png" alt=""><figcaption><p>Select account type according to type of your business or organization</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (800).png" alt=""><figcaption><p>Click <strong>To choose</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (801).png" alt=""><figcaption><p>Click <strong>Register</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (802).png" alt=""><figcaption><p>The system displays the screen to declare information</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (804).png" alt=""><figcaption><p>Fill out information on this area</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (805).png" alt=""><figcaption><p>Click checkbox to agree the term of use and click <strong>Create an OA account</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (806).png" alt=""><figcaption><p>Click <strong>Confirm</strong> to register for an Official Account</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (807).png" alt=""><figcaption><p>A success or failure message will be returned, followed by Authentication start</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (808).png" alt=""><figcaption><p>Here there will be 3 types of authentication, upload the required documents</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (828).png" alt=""><figcaption><p>After uploading the required documents, OA will be in "Waiting for approval" status</p></figcaption></figure>

**Note**\*: After initialization, OA will undergo Zalo system approval before use. Expect activation in 1-7 working days.

**Step 2: Create an app to link to OA**

In order to use the functions of the OA API, OA will be accessed through a specific application that has been authorized to represent it. Depending on the type and purpose of the service required, an OA can authorize multiple applications.&#x20;

To create an app, please access [here](https://developers.zalo.me/) and log in with your Zalo account.

<figure><img src="../../.gitbook/assets/image (810).png" alt=""><figcaption><p>After being transferred at the link above, click "Add new apps"</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (812).png" alt=""><figcaption><p>After clicking 'Add new apps', the user will be directed to the screen shown above, fill in the appropriate information and then click "Create an application ID"</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (815).png" alt=""><figcaption><p>Enter <strong>Contact Phone</strong> and <strong>Contact Email</strong>, then click <strong>Save changes</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (816).png" alt=""><figcaption><p>Click on toggle to activate the application</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (820).png" alt=""><figcaption><p>Click Agree to activate the application</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (819).png" alt=""><figcaption><p>The application is activated successfully</p></figcaption></figure>

* **Get Zalo App ID**

<figure><img src="../../.gitbook/assets/image (823).png" alt=""><figcaption><p>Click to copy Application ID</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (822).png" alt=""><figcaption><p>At the Zalo Integration pop-up, paste the copied text into the Zalo App ID field</p></figcaption></figure>

* **Get App Secret Key**

<figure><img src="../../.gitbook/assets/image (831).png" alt=""><figcaption><p>Click to copy Application Secret Key</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (825).png" alt=""><figcaption><p>At the Zalo Integration pop-up, paste the copied text into the App Secret Key</p></figcaption></figure>

* **Get OA ID**

Access Zalo OA at [here](https://oa.zalo.me/home).

<figure><img src="../../.gitbook/assets/image (826).png" alt=""><figcaption><p>Click to 'Danh sách OA của tôi' to display the OA List</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (827).png" alt=""><figcaption><p>Copy OA ID to integrate Chatbot</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (830).png" alt=""><figcaption><p>At the Zalo Integration pop-up, paste the copied text into the OA ID</p></figcaption></figure>

* **Get Access Token**

<figure><img src="../../.gitbook/assets/image (832).png" alt=""><figcaption><p>Click Application management</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (834).png" alt=""><figcaption><p>At Tool -> select API Explorer</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (835).png" alt=""><figcaption><p>Click and select the right app to integrate</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (836).png" alt=""><figcaption><p>At Type of access token, select OA Access Token</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (837).png" alt=""><figcaption><p>Click Get Access Token -> select your correct OA account</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (838).png" alt=""><figcaption><p>Tick on Agree to allow the application to manage Offcial Account -> click Allow</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (839).png" alt=""><figcaption><p>Click to copy Access Token</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (840).png" alt=""><figcaption><p>At the Zalo Integration pop-up, paste the copied text into the OA Access Token</p></figcaption></figure>

* **Get OA Refresh Token**

<figure><img src="../../.gitbook/assets/image (841).png" alt=""><figcaption><p>Click to copy Refresh Token</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (842).png" alt=""><figcaption><p>At the Zalo Integration pop-up, paste the copied text into the OA Refresh Token</p></figcaption></figure>

* **Get Domain Authentication**

<figure><img src="../../.gitbook/assets/image (843).png" alt=""><figcaption><p>Click on Profile -> Choose appropriate application</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (845).png" alt=""><figcaption><p>Click Domain Authentication on menu side-bar</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (846).png" alt=""><figcaption><p>At the Zalo Integration pop-up, click to copy Callback URL</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (849).png" alt=""><figcaption><p>Paste the copied URL into the Domain, delete the text behind, keep only the domain as shown -> click Accuracy</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (850).png" alt=""><figcaption><p>The system will display a pop-up -> click <strong>Verify now</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (851).png" alt=""><figcaption><p>The system displays a Authenticate pop-up -> at <strong>Upload HTML file to your website</strong> -> click to download file</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (852).png" alt=""><figcaption><p>At the Zalo Integration pop-up, click <strong>Browse Files</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (853).png" alt=""><figcaption><p>Downloaded file has been chosen</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (854).png" alt=""><figcaption><p>Back to screen <a href="https://developers.zalo.me/">https://developers.zalo.me/</a>, the system display messege "Verify successfully" -> Click OK</p></figcaption></figure>

* **Update Webhook**

<figure><img src="../../.gitbook/assets/image (855).png" alt=""><figcaption><p>Click to copy Callback URL</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (857).png" alt=""><figcaption><p>Click <strong>Change</strong> at Webhook screen</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (858).png" alt=""><figcaption><p>Paste the copied URL into the Webhook URL field -> click <strong>Update</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (883).png" alt=""><figcaption><p>The interface is displayed after updating the Webhook URL -> activating the items that need to be displayed</p></figcaption></figure>

When you want to display messages in the form of images, audio, attachments, and stickers from conversations with users in **Livechat**, when integrating with Zalo, you need to activate the following Webhook permissions:

* To **Display Link** -> Activate **Sự kiện người dùng gửi tin nhắn liên kết**
* To **Display text messages** -> Activate **Sự kiện người dùng gửi tin nhắn text**
* To **Display sticker** -> Activate **Sự kiện người dùng gửi tin nhắn sticker**
* To **Display gif** -> Activate **Sự kiện người dùng gửi tin nhắn gif**
* To **Display audio messages** -> Activate **Sự kiện người dùng gửi tin nhắn voice**
* To D**isplay attached files** -> Activate **Sự kiện người dùng gửi tin nhắn đính kèm file**

<figure><img src="../../.gitbook/assets/image (884).png" alt=""><figcaption><p>Search for commands in Webhooks</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (885).png" alt=""><figcaption><p>Status after activating necessary categories</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (860).png" alt=""><figcaption><p>Activate Zalo</p></figcaption></figure>

Click **Save** to complete the integration and fully integrate Zalo.
