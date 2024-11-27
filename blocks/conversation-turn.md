# Conversation turn

## Bot responses (Bot says) <a href="#bot-says" id="bot-says"></a>

Use this block to add AI BOT responses to the conversation flow.

**How to set up**

(1) Drag and drop the Response Bot block onto the Canvas

<figure><img src="../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

(2) AI BOT response can be added in 2 forms:

* Text: AI BOT will respond according to pre-written content

<figure><img src="../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

* Audio: AI BOT will respond by playing the uploaded Audio

<figure><img src="../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

## &#x20;<a href="#users-say" id="users-say"></a>

## Customer response (User says) <a href="#users-say" id="users-say"></a>

Use this block to add USER responses in the conversation flow.

**How to set up**

(1) Drag and drop the Customer Response block onto the canvas

(2) Select the intent to add to the conversation flow

{% hint style="info" %}
Intent is trained before dialogue design (See “NLP Coaching Tools”)
{% endhint %}

<figure><img src="../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

(3) Set up default Reminders and Responses

{% hint style="info" %}
(3) Set up default Reminders and Responses

This is not a required setting. The feature is used to ensure uninterrupted conversation flow in the following cases:

(a) - AI BOT does not understand USER's response

(b) - USER's response does not follow the conversation flow that AI BOT is being trained
{% endhint %}

(3.1) When (a) or (b) occurs, AI BOT will send a Reminder.

**How to set up**

* Click to select the Customer Response block \[1]
* Enter the reminder content \[2] and select the number of repetitions for the reminder \[3]
* Select Save \[4] to complete

<figure><img src="../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>

(3.2) After the AI BOT repeats the reminder enough times, (a) or (b) still occurs. AI BOT will give a default Response.

**How to set up**

* Drag and drop the Response Bot block onto the canvas & enter the response content \[1]
* Create a connection from the Default Response to the newly created Response Bot block \[2]

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

## User Presses Key <a href="#user-pressess-key" id="user-pressess-key"></a>

The IVR scenario can be created as follows:

(1) Drag and drop the "Customer pressed key" block onto the canvas

(2) Add the number of keys corresponding to the scenario

(3) Add a "BOT response" block, enter the corresponding response content, and create a connection with the newly created keypress

Do the same with other buttons

<figure><img src="../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

## User says advanced

In addition to the same function as the Customer Response block which is to identify customer intent and flow the conversation accordingly, the Customer Response block (Advanced) is a combination of the Customer Response block and the Get Parameters block, used to process conversation flows when it is necessary to identify either the entity or the intent in the customer response.

**How to set up**\
Drag and drop the Customer Response block (Advanced) into the Canvas as shown.

(1) Select Intent or Entity in the dropdown list.

{% hint style="danger" %}
Note: If you want the Bot to recognize the entity first, the User needs to prioritize selecting the Entity tag before Intent.
{% endhint %}

(2) For the Intent tag, select Intent to identify at (1).

<figure><img src="../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

(3) Select the entity, enter the parameter name for the entity block, and set the entity type selection

* &#x20;Click the ADD button at (2) to select more Intents or Entities.

<figure><img src="../.gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

* For the Entity tag, click on the drop-down list at the newly added tag, select Entity at (3).

<figure><img src="../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

* Enter the parameter name you want to get at (4).

<figure><img src="../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

* Click on the newly created parameter name at (5) to edit the parameter in the menu bar on the right Get parameter.

<figure><img src="../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

* Click (6) to edit the Parameter name if desired.
* Click (7) to display the drop-down list and select the entity type that matches the parameter name

**For example:** If the parameter name is amount, select the entity type sys.number.

* Click the SAVE button at (8) to save changes.

