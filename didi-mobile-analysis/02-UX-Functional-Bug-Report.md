Title: [UX/Functional] Incorrect error message shown when canceling photo selection on QR scan screen.

Platform: DiDi Mobile App (Android)

Steps to Reproduce:

1.- Open the DiDi application on an Android device.
2.- Navigate to "My Profile".
3.- Tap the "Scan QR" icon located in the top-right corner.
4.- On the camera screen, tap the gallery icon in the bottom-right corner.
5.- When the sliding gallery window appears, immediately cancel the action by swiping the window down.

Expected Result:
The application should close the gallery window and return to the previous screen (the camera view) without displaying any message. A user-initiated cancellation is not an error and should not trigger an alert.

Actual Result:
Immediately after swiping the window down, an error message toast appears at the top of the screen stating "Get Photo Failed".

Additional Notes:
This same erroneous behavior occurs if, in step 5, the user taps the native OS "back" arrow instead of swiping the window down.

Evidence: 
https://drive.google.com/file/d/1GZdMt4dx28PBj2XXR7FW7s7uCHo48eCR/view?usp=sharing
