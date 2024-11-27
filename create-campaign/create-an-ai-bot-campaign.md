# Create an AI BOT campaign

Only 4 steps to start a mass calling campaign for AI BOT

* Step 1: Create a new campaign
* Step 2: Install the script
* Step3: Add customer list
* Step 4: Advanced settings, set call code parameters

See automatic reports at 5. Reports

## Create a new campaign

(1) Select the "Campaigns" tab

(2) Select "Create new "

(3) Enter the Campaign name and campaign code

(4) Select "Call Script"

(5) Select "Start campaign" to move to step "Install call script"

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

## Install the script&#x20;

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

(1) Select a virtual assistant voice.

(2) Result code (Action code)

The result code is identified by Voicebot AI after the call ends. Set the result corresponding to the call status according to the following note.

<table><thead><tr><th width="270.9868627455859">Call status</th><th width="216.03530640214058">Call status</th><th>Result code</th></tr></thead><tbody><tr><td>USER_HANGUP</td><td>Customer hung up the phone</td><td><p>{code}</p><p>⚠️</p><p>The result code is the call code set in the script.</p></td></tr><tr><td>BOT_HANGUP</td><td>Bot hangs up</td><td><p>{code}</p><p>⚠️</p><p>The result code is the calling code set in the script.</p></td></tr><tr><td>BUSY</td><td>Busy</td><td>BS</td></tr><tr><td>NOANSWER</td><td>Customer did not pick up the phone</td><td>NA</td></tr><tr><td>SHORT_CALL</td><td>Short calls (less than 5s)</td><td>SC</td></tr><tr><td>AGENT_NOT_PICK_UP</td><td>The investigator did not pick up the phone</td><td>ANP</td></tr><tr><td>DIAL_HANGUP </td><td>The interviewer hung up the phone</td><td>AHU </td></tr><tr><td>CHANNEL_UNAVAILABLE</td><td>Channel not available</td><td>CU</td></tr></tbody></table>

{% hint style="info" %}
The result code is pre-set in case of using a pre-built AI voicebot.
{% endhint %}



(3) Select "Continue" to go to the "Add customer list" step.

## Add customer list

<figure><img src="../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

(1) Select "Upload customer list"

(2) Select File to upload the available list

{% hint style="info" %}
Select "Download" the customer list template
{% endhint %}

(3) "Upload" customer list

{% hint style="info" %}
Once uploaded, the contact can be edited or deleted
{% endhint %}

<figure><img src="../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

(4) Select "Continue" to go to "Advanced Settings"

## Advanced settings

(1) Fill in the email to receive reports after the campaign ends

(2) Select campaign period

* Campaign start - end date
* Campaign start time (Can set multiple time frames during the day)

(3) Set conditions for AI BOT to automatically call back customers

* 1\) Select "+Add condition"&#x20;
* 2\) Select one or more callback conditions in the display section
  * Busy: Call back when the line is busy
  * No answer: Call back when the customer does not answer the phone
  * Unable to connect: Call back when the connection fails
  * Action Code (Result code): Callback depending on the call result code

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

(4) Click “Continue” to go to the campaign running and reporting step

## Run the campaign

In section 5. Report, select “Run” to start the campaign
