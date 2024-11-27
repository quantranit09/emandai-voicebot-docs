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

1. Scroll down to the bottom of the page, click on Response at (8)
2. Click the ADD BLOCK button at (9)

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

3. Click the arrow at (10) to go to detailed settings for response
4. Click the CREATE RESPONSE button at (11) to display the Response pop-up
5. Enter the response name in the NAME box at (4.4)
6. Enter response content in the TEXT box at (4.5)
7. Press the SAVE button at (4.6) to save the response.

<figure><img src="../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

8. Press the X to close the pop-up.
9. Press the SAVE button to save the settings.

## Create FAQ responses

### Step 1: Enable FAQ responses:

1. From the toolbar (left), drag and drop the User says/ User says (advance) block into the Canvas.
2. Click on the block, and the system will display the General Configuration settings. (See picture 1)

<figure><img src="../.gitbook/assets/image (65).png" alt=""><figcaption><p>Figure 1: Enable the General configuration setting - FAQ response.</p></figcaption></figure>

### Step 2: Select FAQ response

Tick the FAQ Response box at (01) to show the FAQ Response setting. (See picture 2)

* To deselect FAQ Response, click (1), and the FAQ setting at (2) will disappear.

### Step 3: Customize the number of FAQ repetitions

Enter only numbers in FAQ response repetitions at (2) to limit the number of times the bot responds to the FAQ. (See picture 2)

<figure><img src="../.gitbook/assets/image (67).png" alt=""><figcaption><p>Figure 2: Install and save FAQ response settings.</p></figcaption></figure>

* If the user leaves the number of repetitions blank, the bot will respond to unlimited FAQs.

### Step 4: Enter the question again

Enter the question again at (3), the number of characters is limited to 1000. (See picture 2)

* If the re-ask content is left blank, the bot will finish answering the FAQ and not respond to the repeated content but will continue to wait for the customer to respond again in the context of an ongoing conversation.
* If you want to add additional question content, please click (4). When creating many different ask-back content, these responses will be randomly selected to respond to customers in the actual conversation.

### Step 5: Save FAQ settings

The user clicks the Save button at (5) to save the FAQ Response settings. (See picture 2)

* Any block that has FAQ Response settings saved will display "FAQ Response" right below the intent selection tag.
* Added Copy/Paste block feature to V2: The feature allows users to use the key combination Ctrl C, and Ctrl V to copy and paste a block while designing a conversation flow.

The copy-paste dialogue block feature allows users to copy and paste any dialogue block within the scope of V2 script building. This feature is intended to help users save time creating scenarios and complete scenarios at a faster speed.

Copy and paste is applied to all dialogue blocks on V2 scripting.

\
