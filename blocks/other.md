# Other

## Condition <a href="#id-4tgmcablivlo" id="id-4tgmcablivlo"></a>

Use this block to create rules or action rule sets for the AI ​​BOT

**For example**

Consider the scenario of giving preferential gifts when customers purchase a specific quantity. If the number of customers purchasing more than 3 will be given a voucher worth 1 million VND

<table data-header-hidden><thead><tr><th width="150"></th><th width="349.83589462129527"></th><th></th></tr></thead><tbody><tr><td><strong>Object</strong></td><td><strong>Response</strong></td><td><strong>Intent/Condition</strong></td></tr><tr><td>USER</td><td>So I will order 4 dishwashers</td><td><p>- intent: "agree_to_buy"</p><p>- quantity = 4</p></td></tr><tr><td>AI BOT</td><td>You have reached the spending amount to receive a gift from EM&#x26;AI which is a purchase voucher worth $ 40. Gift voucher will be delivered with the product.</td><td><p></p><p>Response condition: quantity >3</p></td></tr></tbody></table>

According to the above scenario, the setting script will be as follows:

<figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

**How to set up**

(1) Drag and drop the Condition block into the Canvas & select the “Condition name” box to display the configuration interface \[1]

(2) Enter the condition name \[2]

(3) Choose to create Rules/Rule Sets depending on the scenario \[3]

(4) Set conditions for rules \[4]

* And: All rules must be met
* Or: Meets one of the rules

(5) Rule setting \[5]

(6) Select Save to complete \[6]

<figure><img src="../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

(7) Create connections with corresponding conditions/intents/action blocks

## End the conversation <a href="#wzg5647n152" id="wzg5647n152"></a>

Use this block to create the end of a conversation flow.

**How to set up**

(1) Drag and drop the End conversation block onto the Canvas \[1]

(2) Create a connection with the AI BOT intent/response block as the conversation endpoint \[2]
