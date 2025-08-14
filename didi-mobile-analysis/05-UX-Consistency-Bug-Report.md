Title: [UX/Consistency] Inconsistent confirmation messages when deleting unread messages

Platform: DiDi Mobile App (Android)

Summary of Behavior:
An inconsistency has been observed in the feedback messages when using the "Delete all unread messages" feature. 
When there are no more messages to delete, the application displays a confirmation/notice message in two visually distinct ways and in different positions, without a predictable pattern.

Conditions & Test Scenario:
The erratic behavior occurs when repeatedly tapping the "Delete all unread messages" option, especially while switching between the "Notifications" and "Conversations" tabs within the "Messages" section.

Actual (Inconsistent) Result:
After tapping the option when there are no messages left to delete, the application randomly displays one of two possible messages:

Message A (Informational): A light-gray toast message in the center of the screen stating "Mensajes sin leer".

Message B (Alert/Error): A red toast message at the bottom of the screen stating the same text: "Mensajes sin leer".

Expected Result:
Feedback for the same action should always be consistent. The application should display a single type of message (preferably the informational style, 
not the red one which implies an error) in the same position every time the user attempts the action when no unread messages are left. 
The message text should also be clearer, such as "No messages to delete" or "No unread messages".

Evidence:
https://drive.google.com/file/d/1JC75dpoUZQLHf-RIzEF81mq1tzc64Pmh/view?usp=sharing
