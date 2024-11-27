# Trigger

The tool allows the creation of triggers for actions corresponding to any condition or intent.

## Email

Enable sending notifications to email addresses with custom messages.

**For example**

When the intention agree\_to\_buy appears, AI BOT responds to get the corresponding parameters (Quantity: quantity, color: color) and then sends a notification email with the content and parameters just taken.

**How to set up**

(1) Drag and drop the Email block onto the Canvas & configure email sending as shown \[1]

(2) Create connections to corresponding intents/conditions/action blocks \[2]

\


<figure><img src="../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

## Support Agent <a href="#id-8aeret31hrob" id="id-8aeret31hrob"></a>

Calls can be set to redirect to the support agent as follows:

### Create agent list

It is necessary to create a list of agents in advance before activating call forwarding

#### Create a department list

(1) Select Advanced Settings -> select AI Voicebot -> Select Support Agent

(2) Select Create new

(3) Enter the department name (Example: Customer Service - Customer Care)

(4) Select Save to complete

<figure><img src="../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

#### Add Agent

(1) Select the newly created department list

(2) In the display frame, select "Add"

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

(3) Enter the employee name and redirect the phone number

(4) Select Save to complete

<figure><img src="../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

### Activate call transferring

(1) Drag and drop the Support Agent block onto the Canvas

(2) Select the department list

(3) In the display frame, select the employee who needs to redirect the call

* Select <img src="../.gitbook/assets/image (11).png" alt="" data-size="line"> If you want to add a new extension number; select <img src="../.gitbook/assets/image (10).png" alt="" data-size="line">if you want to delete the extension.

(4) Select Save to complete

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

(5) Create connections with corresponding conditions/intents/action blocks

{% hint style="info" %}
You should use the switchboard's extension number instead of your number to redirect and support customers more effectively
{% endhint %}

## Webhook <a href="#jz75se4x3rdl" id="jz75se4x3rdl"></a>

Webhooks allow the system to access APIs from another application/system in real-time, support integration, or access calculation formulas from information data provided by customers.

<figure><img src="../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

**How to set up**

(1) Drag and drop the Webhook block onto the Canvas

(2) Click to select the Webhook block to display the configuration interface

* Enter the access path to API \[1]
* Choose API access method \[2]
* Response Mapping: Set up the mapping of the return value from the API to the variable after processing. Use this variable in AI BOT response settings. \[3]

(3) Create connections with corresponding conditions/intents/action blocks

## Scripts code <a href="#nvqadlgjp6y5" id="nvqadlgjp6y5"></a>

Enable running complex logic code for AI BOT in the context of a conversation, allowing AI BOT to perform advanced tasks.

**How to set up**

(1) Drag and drop the Scripts code block into the Canvas \[1]

(2) Click to select the Scripts code block to display the configuration interface

(3) Enter the Scripts \[2]

(4) Select Save to complete \[3]

![](../.gitbook/assets/17)

(4) Create connections with corresponding conditions/intents/action blocks

<figure><img src="../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

### &#x20;<a href="#id-96l92hs1ajz4" id="id-96l92hs1ajz4"></a>

