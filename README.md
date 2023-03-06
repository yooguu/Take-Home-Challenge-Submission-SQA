# Take-Home-Challenge-Submission-SQA

## Here are 10 use cases of WhatsApp Desktop listed in order of priority using Gherkin syntax:

1. Scenario: Sending a text message
```bash
Given User open WhatsApp Desktop
When User select the contact to whom I want to send a message
And User type the text message
And User press the send button
Then The message is sent successfully
```

2. Scenario: Sending a voice message
```bash
Given User open WhatsApp Desktop
When User select the contact to whom I want to send a voice message
And User record the voice message
And User press the send button
Then The voice message is sent successfully
```

3. Scenario: Sending an image
```bash
Given User open WhatsApp Desktop
When User select the contact to whom I want to send an image
And User click the button to select an image
And User select the image to send
And User press the send button
Then The image is sent successfully
```

4. Scenario: Receiving a text message
```bash
Given User open WhatsApp Desktop
When User receive a text message from a contact
Then The text message is displayed successfully
```

5. Scenario: Receiving a voice message
```bash
Given User open WhatsApp Desktop
When User receive a voice message from a contact
Then The voice message is displayed successfully
```

6. Scenario: Receiving an image
```bash
Given User open WhatsApp Desktop
When User receive an image from a contact
Then The image is displayed successfully
```

7. Scenario: Changing status
```bash
Given User open WhatsApp Desktop
When User click on the option to change my status
And User type the new status
And User save the changes
Then The status is successfully changed
```

8. Scenario: Deleting a message
```bash
Given User open WhatsApp Desktop
When User open the conversation with a contact
And User click on the message that I want to delete
And User select the option to delete the message
And User confirm to delete the message
Then The message is successfully deleted
```

9. Scenario: Searching for a conversation
```bash
Given User open WhatsApp Desktop
When User click on the icon to search for a conversation
And User type the keyword to search for a conversation
And User press the search button
Then The search results are displayed successfully
```

10. Scenario: Managing a group
```bash
Given User open WhatsApp Desktop
When User open the group that I want to manage
And User click on the option to manage the group
And User add or remove group members
And User save the changes
Then The group is successfully managed
```
