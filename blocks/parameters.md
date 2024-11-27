# Parameters

Parameters are used to collect information from customers through a series of questions or assign specific values ​​according to conditions to help AI BOT give appropriate responses according to the conversation context.

**For example:** Name, Phone number, Email, Address, Quantity,...

## Get parameters <a href="#wlb5uenpqzl3" id="wlb5uenpqzl3"></a>

Use this block when you need to create input parameters and save input data from customers.

**How to set up**

(1) Drag and drop the Get Parameters block onto the canvas

(2) Click on the “parameters” box to display the configuration interface.

<figure><img src="../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

(3) Set parameters at the display interface

* Enter the parameter name and select the entity type of the parameter \[1]
* Enter AI BOT response content to collect parameters \[2]
* In case the parameter to be obtained is "mandatory", it means AI BOT will only continue the conversation once the parameter has been obtained. Click “mandatory” \[3] and continue to set the following items:

<figure><img src="../.gitbook/assets/image (130).png" alt=""><figcaption></figcaption></figure>



(4) Create a connection from the newly created parameter to the corresponding intent/condition/action block.

<mark style="color:red;">-> In case more than 1 parameter is needed to perform the next step, set as follows:</mark>

(1) Drag and drop the Create Parameters block onto the Canvas

(2) Create parameters that need to be collected by AI BOT. In the example below, the parameters to be collected are "size, color"

(3) Choose to create a connection at the point “**When all parameters are met**” to the corresponding AI BOT response block/intention/condition/action block.

<figure><img src="../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

## Assign parameters <a href="#m0oye661f4uq" id="m0oye661f4uq"></a>

Use this block to conditionally assign a value to the parameter and use it in various responses of the AI BOT.

**How to set up**

(1) Drag and drop the Assign parameters block to the Canvas

(2) Enter the parameter name and the value assigned to that parameter

(3) Select Add to add a new parameter

<figure><img src="../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To set up parameter assignment conditions, drag and drop the “Conditions” block onto the canvas and set it according to the instructions in the section “Conditions"
{% endhint %}

## Tags

Use this block to create/remove object classification tags or create action codes corresponding to the intent (ACTION CODE).

**How to set up**

(1) Drag and drop the Tag block onto the Canvas \[1]

(2) Enter the tag value and press enter to save \[2]

(3) Create a connection with the corresponding USER intent that wants to create a classification tag \[3]

**For example**

* The agree\_to\_buy intention corresponds to the make\_order tag
* The intention refuse\_to\_buy corresponds to the tag no\_demand label

{% hint style="info" %}
Tags can be assigned in English. For example: "in need", "VIP guest"...
{% endhint %}

<figure><img src="../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>
