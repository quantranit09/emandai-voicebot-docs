# Task Oriented

{% embed url="https://www.youtube.com/watch?index=8&list=PLY8p3TDIsCEWIPo84LkR53wjZNHVvMS_z&v=J-SGP079c2E" %}
Setting Task Orriented
{% endembed %}

Task-Oriented is a feature that allows users to set some advanced settings for bot responses.&#x20;

Defining specific keywords can help the bot provide more intelligent responses. Whenever customers mention those keywords, the Bot can identify and respond accordingly. The content of the Bot's responses can be generated from the trained knowledge base or fixed text. Add more keywords to your bot will enhance its intelligence and improve the quality of it&#x20;

**Instruction to set up Task-Oriented**

Click on the **'+ Add**' button at the top left of the screen, the system displays a popup to proceed new task.

<figure><img src="../.gitbook/assets/image (726).png" alt=""><figcaption><p>Click on the <strong>'+ Add</strong>' button to proceed a new task</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (727).png" alt=""><figcaption><p><strong>ADD TASK</strong> pop-up</p></figcaption></figure>

**Enter  name of task:** The user should choose a short, precise, and clear name that represents the task for easy storage and search.

<figure><img src="../.gitbook/assets/image (553).png" alt=""><figcaption><p>Enter name of task</p></figcaption></figure>

After entering the name -> Click '**Add'** button to save the created task -> the created task will be appear on the **Task-oriented** screen

<figure><img src="../.gitbook/assets/image (763).png" alt=""><figcaption><p>List of created tasks</p></figcaption></figure>

On the Task-oriented screen, click on the created task -> the system will display the task setting screen.

<figure><img src="../.gitbook/assets/image (764).png" alt=""><figcaption><p>The task setting screen</p></figcaption></figure>

At this screen, you need to set some criteria such as:

* Enter keywords (on customer talks)
* Set up Bot responses
* Capture entity (optional)
  * Select the parameter of the entity to collect information
  * Bot's response when all information has been collected according to the set parameters
  * Send collected information to email

**Enter keywords (on customer talks)**

<figure><img src="../.gitbook/assets/image (559).png" alt=""><figcaption><p>Enter keywords </p></figcaption></figure>

Keywords are predetermined words or phrases that customers enter to help the Bot classify and analyze feedback, leading to more accurate responses.

* In the text input field: type a word/phrase then press 'enter' for the system to recognize.
* If you need to delete the typed words, simply press the 'x' just to the right of the word/phrase to be deleted

<figure><img src="../.gitbook/assets/image (561).png" alt=""><figcaption><p>Enter keywords </p></figcaption></figure>

After entering the words/phrases, the system will check whether the customer's response contains these words/phrases, if the customer's interaction contains these words, the Bot will have responses based on the following conditions set in the Bot responses setting

**Bot responses setting**

<figure><img src="../.gitbook/assets/image (765).png" alt=""><figcaption><p><strong>Bot responses setting</strong></p></figcaption></figure>

In this section, you will learn how to set up response methods for bots when certain keywords are found in customer feedback.

* **Literal Text**: The bot will reply with fixed text according to what the user has entered
* **Prompt**: To control how the bot responds, you will input a command. The Bot will utilize the content in the knowledge base as a reference data source to analyze and generate appropriate responses that correspond to the content of the question

**Capture Entity**

<figure><img src="../.gitbook/assets/Component 11 (1).png" alt=""><figcaption><p>Capture entity</p></figcaption></figure>

Entities are subjects related to full name/phone number/address/email... mentioned in customer's responses throughout the conversation

'Capture entity' is a feature that allows collecting information provided by customers in conversations according to predefined parameters

When you activate this feature in the task's conditions of the task-oriented function, it means that the bot will respond to the user's settings after recognizing the customer feedback's intent containing the set keywords. Additionally, the bot will activate the entity information collection function for subsequent customer responses.

Default: the 'Capture entity' feature will not be enabled. If you click on the toggle icon, the system will activate this feature, the bot will start recording the mentioned entity information from customer feedback

<figure><img src="../.gitbook/assets/Component 3.png" alt=""><figcaption><p>Activate to capture entity</p></figcaption></figure>

The entity information will be collected by parameters. Entity information will gather from customer response:

* City
* Date
* District
* Email
* Full name
* Number
* Phone number
* Street
* Street number
* Entire user's response
* Time
* Ward

Note: It is not mandatory to install all these parameters. You can optionally set one or several parameters, depending on your needs.&#x20;

Add/remove parameters by tapping the "+", or "-" icon just to the right of the parameter.

**Bot responses setting after recording (after collecting entity information)**

<figure><img src="../.gitbook/assets/image (558).png" alt=""><figcaption><p>Bot responses setting after recording (after collecting entity information)</p></figcaption></figure>

Default: Bot's response setting will not be activated. If you click on the toggle, the system will allow this function to be performed, which means that the bot will respond based on the set conditions when entity information is collected.

In this section, you will learn how to set up the Bot's response methods after the Bot has fully recorded the parameter information:&#x20;

* **Literal Text**: The bot will reply with fixed text according to what the user has entered
* **Prompt**: To control how the bot responds, you will input a command. The Bot will utilize the content in the knowledge base as a reference data source to analyze and generate appropriate responses that correspond to the content of the question

**Send collected information to email**

<figure><img src="../.gitbook/assets/image (106).png" alt=""><figcaption><p>Send collected information to email</p></figcaption></figure>

After activating this feature, all information obtained will be attached to the Google Sheet file and a link will be sent to the email you registered in the **Profile** section.
