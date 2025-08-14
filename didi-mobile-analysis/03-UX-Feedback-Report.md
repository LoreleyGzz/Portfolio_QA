Title: [UX] "Delete Messages" button lacks visual feedback and affordance

Platform: DiDi Mobile App (Android)

Steps to Reproduce:
  1.- Open the DiDi application on an Android device.
  2.- Navigate to "My Profile" and then to "Messages".
  3.- Select the "Conversations" tab.
  4.- Ensure there are messages marked as "unread".
  5.- Tap the "Delete all unread messages" text located at the top of the screen.

Actual Result:
  Upon tapping the text, the unread messages are correctly deleted, but the user interface provides no immediate visual feedback (such as an animation, color change, or message). This leaves the user uncertain as to whether their action was registered or if the element was interactive at all.

Expected Result:
The interaction should be clearer in two phases:

  Design (Affordance): The "Delete all unread messages" element should be styled to look like a button or a hyperlink to better signify that it is interactive, rather than appearing as plain text.
  Interaction (Feedback): Upon tapping it, the button should provide instant visual feedback (e.g., a "pulse" animation or an opacity change). After the action is successfully completed, a discrete, temporary confirmation message (e.g., "Messages successfully deleted") should be displayed.

Evidence:
  https://drive.google.com/file/d/1tM4ps0MbqerPInXUiKR3ZaHhsry9iJ8D/view?usp=sharing
