# Take-Home-Challenge-Submission-SQA

## Here are 10 use cases of WhatsApp Desktop listed in order of priority using Gherkin syntax:

1. Scenario: Sending a text message
```bash
Given I open WhatsApp Desktop
When I select the contact to whom I want to send a message
And I type the text message
And I press the send button
Then The message is sent successfully
```

2. Scenario: Sending a voice message
```bash
Given I open WhatsApp Desktop
When I select the contact to whom I want to send a voice message
And I record the voice message
And I press the send button
Then The voice message is sent successfully
```

3. Scenario: Sending an image
```bash
Given I open WhatsApp Desktop
When I select the contact to whom I want to send an image
And I click the button to select an image
And I select the image to send
And I press the send button
Then The image is sent successfully
```

4. Scenario: Receiving a text message
```bash
Given I open WhatsApp Desktop
When I receive a text message from a contact
Then The text message is displayed successfully
```

5. Scenario: Receiving a voice message
```bash
Given I open WhatsApp Desktop
When I receive a voice message from a contact
Then The voice message is displayed successfully
```

6. Scenario: Receiving an image
```bash
Given I open WhatsApp Desktop
When I receive an image from a contact
Then The image is displayed successfully
```

7. Scenario: Changing status
```bash
Given I open WhatsApp Desktop
When I click on the option to change my status
And I type the new status
And I save the changes
Then The status is successfully changed
```

8. Scenario: Deleting a message
```bash
Given I open WhatsApp Desktop
When I open the conversation with a contact
And I click on the message that I want to delete
And I select the option to delete the message
And I confirm to delete the message
Then The message is successfully deleted
```

9. Scenario: Searching for a conversation
```bash
Given I open WhatsApp Desktop
When I click on the icon to search for a conversation
And I type the keyword to search for a conversation
And I press the search button
Then The search results are displayed successfully
```

10. Scenario: Managing a group
```bash
Given I open WhatsApp Desktop
When I open the group that I want to manage
And I click on the option to manage the group
And I add or remove group members
And I save the changes
Then The group is successfully managed
```
