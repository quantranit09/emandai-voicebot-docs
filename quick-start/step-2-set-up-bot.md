# Step 2 - Set up Bot

On the dashboard screen, you will see a list of all the Chatbots created in the system. To access the specific settings for a Chatbot, simply select it from the list and click on it. The system will then take you to the Bot Settings screen, where you can set up more advanced features and details for your Chatbot.

<figure><img src="../.gitbook/assets/image (176).png" alt=""><figcaption><p>The Bot Settings screen</p></figcaption></figure>

This feature allows you to customize the Bot's orientation settings, information display, and chat interface.

At the Bot Settings feature, the screen is divided into 3 tabs corresponding to the main features in the Bot settings:

* **Prompt**: Bot Control Orientation Settings
* **Theme**: Customize chat interface
* **Advance**: Set rates that affect the content of the Bot's response and perform advanced tasks.

\---

**PROMPT**

A prompt in AI tools is a sentence or paragraph entered by the user to ask the AI chatbot to interact with customers in the given style.&#x20;

AI Chatbot combines artificial intelligence and a diverse knowledge base to analyze natural language input and provide accurate responses.

<figure><img src="../.gitbook/assets/image (177).png" alt=""><figcaption><p>Prompt setting interface</p></figcaption></figure>

**Set up context for bots**

<figure><img src="../.gitbook/assets/image (178).png" alt=""><figcaption><p>Set up context for bots</p></figcaption></figure>

This feature helps to create the context for the Bot

* **Position**: enter a job position for the bot; help the Bot understand its role when advising customers
* **Workplace**: this information helps Bot understand which business he is representing
* **Language**: allows the chatbot to respond to customers in the given language

**Job Description**

<figure><img src="../.gitbook/assets/image (179).png" alt=""><figcaption><p>Enter job description for bot</p></figcaption></figure>

Users can use this feature to configure control commands for the ChatBot. The text field in the feature already contains a default control command for the Bot. You can either customize this command or choose to keep it as the default.&#x20;

Users can refer to the business sample for ideas on designing appropriate commands.

**Select prompt sample**

<figure><img src="../.gitbook/assets/image (180).png" alt=""><figcaption><p>Click on <strong>Select prompt sample</strong> to navigate to <strong>Select prompt</strong> pop-up</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (456).png" alt=""><figcaption><p>Choose prompt templates according to different business fields</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (182).png" alt=""><figcaption><p>Click on checkbox of the selected prompt sample -> click <strong>Apply</strong></p></figcaption></figure>

To select a suitable prompt sample for your job description, simply tick on the checkbox provided. Once you have made your selection, click on the 'Apply' button. The system will then display the content of the chosen prompt in the job description field, which you can further edit to meet your business requirements.

<figure><img src="../.gitbook/assets/image (183).png" alt=""><figcaption><p>Prompt for Sales Consultant (e-commerce)</p></figcaption></figure>

The user can click on <img src="../.gitbook/assets/image (465).png" alt="" data-size="line"> to view the selected prompt in detail and illustrated images of how the Bot response

Moreover, you can refer to the list of prompt samples prepared by the development team by clicking on <img src="../.gitbook/assets/image (728).png" alt="" data-size="line">, you can copy the prompt sample that suits your business requirements and apply it to the **Job description**

**Set up to reply within trained data**

<figure><img src="../.gitbook/assets/image (184).png" alt=""><figcaption><p>Enable/Disable the feature to reply within trained data</p></figcaption></figure>

Enable/disable the feature to **reply within trained data**: this feature is used to control the scope of the Bot's response information to the given knowledge base, or additionally use data that is in chatGPT's default knowledge base

**Set up to Reply with the link in trained data**

<figure><img src="../.gitbook/assets/image (185).png" alt=""><figcaption><p>Enable/Disable the feature to reply with the link in trained data</p></figcaption></figure>

Enable/Disable the feature to reply with the link in trained data: this feature is used to attach the link in the Bot's response when the user created data in the knowledge base with the link attached

After finalizing the prompt setting -> click the **Update** button to save the changed information

<figure><img src="../.gitbook/assets/image (186).png" alt=""><figcaption><p>Click the <strong>Update</strong> button to save the changed information</p></figcaption></figure>

\---

**THEME**

At this screen, you can flexibly design the chat dialog interface, to integrate into your website or other online platforms\


<figure><img src="../.gitbook/assets/image (169).png" alt=""><figcaption><p>Theme interface</p></figcaption></figure>

* Change displaying information: Chatbot Name - Chatbot Description

<figure><img src="../.gitbook/assets/image (170).png" alt=""><figcaption><p>Change displaying information: Chatbot Name - Chatbot Description</p></figcaption></figure>

* Set default messages: Welcome message. The welcome message is a message that is initiated automatically as soon as the user starts using the chatbot feature

<figure><img src="../.gitbook/assets/image (171).png" alt=""><figcaption><p>Set default messages</p></figcaption></figure>

* Background color and text color: you can optionally change the background color as well as the chat text color as you like

<figure><img src="../.gitbook/assets/image (172).png" alt=""><figcaption><p>Set heading colour</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (173).png" alt=""><figcaption><p>Set chatbot message colour</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (174).png" alt=""><figcaption><p>Set user message colour</p></figcaption></figure>

After setting -> click Update to save changed information

<figure><img src="../.gitbook/assets/image (175).png" alt=""><figcaption><p>Click Update to save changed information</p></figcaption></figure>

\---

**ADVANCE**

This feature enables users to adjust the bot's creativity and confidence levels, which affect the content of its response. Advanced tasks can also be configured using this feature.

<figure><img src="../.gitbook/assets/image (153).png" alt=""><figcaption><p>Advance setting interface</p></figcaption></figure>

**Bot's Creativity**

<figure><img src="../.gitbook/assets/image (154).png" alt=""><figcaption><p>Creativity adjustment bar for Bot feedback</p></figcaption></figure>

Bot's Creativity: The level of creativity in the bot's responses can be adjusted by users using a sliding bar with their computer mouse. When the creativity level is set to 0, the bot will generate responses using only the information from its knowledge base. However, if the creativity level is increased above 0, the bot will incorporate external information to provide more contextual and accurate responses to customer questions.

**Confident range**

<figure><img src="../.gitbook/assets/image (155).png" alt=""><figcaption><p>Set up the confident range of data</p></figcaption></figure>

Data confidence rate: represents the AI's estimation of the percentage match between the knowledge base and the customer's question.

The confidence range is the confidence threshold you set. The bot will use training data with a confidence rate within the defined range to respond to customer questions.

If a user sets the confidence rate of the data to above 70%, the bot will only select data from the knowledge base that matches the content of the customer's question to a confidence level of more than 70%. This data will be used to create the response content. However, any data with a confidence rate below 70% will not be used.

**Capture entity**

<figure><img src="../.gitbook/assets/image (156).png" alt=""><figcaption><p>Click on toggle to enable/disable the feature of capturing entity</p></figcaption></figure>

**'Capture entity'** is a feature that allows collecting information provided by customers in conversations according to predefined parameters

Default: **'Capture entity'** feature will not be enabled. If you click on the toggle, the system will activate this function, the bot will start collecting the mentioned information from the customer's messages

**Select entity type**

<figure><img src="../.gitbook/assets/image (158).png" alt=""><figcaption><p>Select entity type to collect information</p></figcaption></figure>

Entities are subjects related to full name/phone number/address/email... mentioned in customer's responses throughout the conversation

Click the drop-down list to select the appropriate parameter and enter the parameter name in the field next to it

Note: It is not mandatory to set all parameters included in the list. You can optionally set a or some parameters, depending on your needs

Add/remove parameters by tapping the "+", or "-" icon just to the right of the parameter

<figure><img src="../.gitbook/assets/image (159).png" alt=""><figcaption><p>Add/Remove parameters</p></figcaption></figure>

**Response**

<figure><img src="../.gitbook/assets/image (160).png" alt=""><figcaption><p>Click on the toggle to enable/disable the 'Response' feature</p></figcaption></figure>

The '**Response**' feature is what the Bot will use to reply once it gathers the information based on the given parameters. By default, this feature is disabled. To activate it, you need to click on the '**Response**' toggle icon.

<figure><img src="../.gitbook/assets/image (161).png" alt=""><figcaption><p>Set Bot's response when it collected the defined entity information </p></figcaption></figure>

This feature allows the Bot to respond according to the predefined text or the Prompt control command (Prompt):&#x20;

* **Literal text**: enter the fixed text you want the bot to respond to
* **Prompt**: To control how the bot responds, you will input a command. By default, there is a control command, but you have the option to customize it or skip this step and use the default. The Bot will utilize the content in the knowledge base as a reference data source to analyze and generate appropriate responses that correspond to the content of the question

<figure><img src="../.gitbook/assets/image (162).png" alt=""><figcaption><p>Enter email to receive captured entity information</p></figcaption></figure>

Enter your email address to receive captured entity information from the conversation

After setting -> click **Update** to save changed information

<figure><img src="../.gitbook/assets/image (163).png" alt=""><figcaption><p>Click <strong>Update</strong> to save changed information</p></figcaption></figure>
