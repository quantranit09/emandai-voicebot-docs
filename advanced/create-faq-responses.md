# Create FAQ responses

The FAQ response feature helps AI Bot answer customer questions outside of the main scenario, providing additional information from its built-in knowledge base to flexibly answer questions and minimize response potential. not in accordance with the customer's intention.

The FAQ response feature is applied to the [User Says ](https://docs.emandai.net/em-and-ai-voicebot-ai/blocks/luot-hoi-thoai)and User Says Advanced blocks.

## Create FAQ intent

### Step 1: Create FAQ intent

Select the Context tab (HOME / SCRIPT BUILDING / SCRIPT (V1.0) / CONTEXT), click the CREATE NEW button.

<figure><img src="../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

### Step 2: Install Create new FAQ intent

1. From the Create New page, click Intent at (1).
2. Click on the FAQ box at (2)

<figure><img src="../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

1. Enter the FAQ Intent name at (3) to name the FAQ intent
2. Enter the Node Title name at (4)
3. Check the box Return to the flow of this intention after answering a FAQ in (5) (Optional)
4. Enter Description at (6) (Optional)

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

1. Scroll to the bottom of the page, and click the SAVE button to save the FAQ note.

### Step 3: Add sample sentences for FAQ intent

1. From the Context page, tap the FAQ intent that needs to add a sample sentence or tap the Pencil icon.

<figure><img src="../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

2\. Click Template at (03) to add a sample sentence for the FAQ intent

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

3\. Click the CREATE NEW button at (4) to add sample sentences on the Sample Sentence Pop-up as shown below.

4\. Enter the content of the sample sentence in the Content box at (5)

5\. Click to add an intention to the sample sentence just created in (6) if desired. (Optional)

6\. Click the SAVE button at (7) to save the sample sentence.

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

### Step 4: Add responses to the FAQ intent

This configuration step allows the bot to automatically respond when an FAQ intent is triggered during the conversation. Users can set up one or multiple response blocks with custom conditions. Please follow the instructions below:

**Add a New Response Block (Optional)**

<figure><img src="../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>

* Click **ADD BLOCK** at section.
* Click the arrow at "block 1" to open the detailed settings for that response block.

**Add Conditions to Trigger the Response Block (Optional)**

<figure><img src="../.gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>

* Select **"Condition"**, then choose **"Rule"** to create a new condition.
* Users may also configure **AND/OR** logic to combine multiple conditions for more complex scenarios.

**Configure Parameters When the Block Is Triggered (Optional)**

<figure><img src="../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

Allows users to configure parameters and their values. When the response block is activated, the system will automatically record the parameter name and its assigned value.

**Add Responses (Optional)**

<figure><img src="../.gitbook/assets/image (140).png" alt=""><figcaption></figcaption></figure>

* Click **"Add New Response"** to create a new bot response.
* Responses applied to FAQ will appear under **"Selected Responses"**.
* Users can also reuse existing responses by dragging them from **"Available Responses"** to **"Selected Responses"**.

**Note:**

* If multiple responses are added under **Selected Responses**, the system will deliver **each response sequentially** when the FAQ is triggered.
* If you want to use multiple variations for a single response, click **"Add"** to insert additional message templates.

<figure><img src="../.gitbook/assets/image (141).png" alt=""><figcaption></figcaption></figure>

## Create FAQ responses

### Step 1: Enable FAQ responses:

1. From the toolbar (left), drag and drop the User says/ User says (advance) block into the Canvas.
2. Click on the block, and the system will display the General Configuration settings. (See picture 1)

<figure><img src="../.gitbook/assets/image (147).png" alt=""><figcaption></figcaption></figure>

### Step 2: Select FAQ response

Tick the FAQ Response box at (01) to show the FAQ Response setting. (See picture 2)

* To deselect FAQ Response, click (1), and the FAQ setting at (2) & (3) will disappear.

### Step 3: Customize the number of FAQ repetitions

Enter only numbers in FAQ response repetitions at (2) or/and  (3) to limit the number of times the bot responds to the FAQ.

* If the user leaves the number of repetitions blank, the bot will respond to unlimited FAQs.

### Step 4: Enter the question again

Enter the question again at (4), the number of characters is limited to 1000.

* If the re-ask content is left blank, the bot will finish answering the FAQ and not respond to the repeated content but will continue to wait for the customer to respond again in the context of an ongoing conversation.
* If you want to add additional question content, please click (5). When creating many different ask-back content, these responses will be randomly selected to respond to customers in the actual conversation.

<figure><img src="../.gitbook/assets/image (148).png" alt=""><figcaption></figcaption></figure>

To configure the output flow when the FAQ limit is reached or when the conversation falls back to the default flow, users can add a **“Condition” block** connected to the default response and configure it as follows:

* **fallbackType = NORMAL**: Trigger this path when the number of intent occurrences reaches its limit.
* **fallbackType = FAQ**: Trigger this path when the total number of FAQ occurrences reaches the overall limit.
* **fallbackType = SINGLE\_FAQ**: Trigger this path when the occurrence count of a specific FAQ reaches its limit.

### Step 5: Save FAQ settings

The user clicks the Save button at (5) to save the FAQ Response settings. (See picture 2)

* Any block that has FAQ Response settings saved will display "FAQ Response" right below the intent selection tag.
* Added Copy/Paste block feature to V2: The feature allows users to use the key combination Ctrl C, and Ctrl V to copy and paste a block while designing a conversation flow.

The copy-paste dialogue block feature allows users to copy and paste any dialogue block within the scope of V2 script building. This feature is intended to help users save time creating scenarios and complete scenarios at a faster speed.

Copy and paste is applied to all dialogue blocks on V2 scripting.

<br>
