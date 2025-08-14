Title: [Functional/Performance] Server error when force-reloading content on the main screen.

Platform: DiDi Mobile App (Android)

Steps to Reproduce:

  1.- Open the DiDi application on an Android device.
  2.- On the main screen, scroll down to the end of the suggestions list.
  3.- Once at the bottom, perform the "scroll down" gesture again to force more content to load (3 loading dots will appear).
  4.- Repeat step 3 multiple times in quick succession (approx. 5-10 times) until the error manifests.

Expected Result:
The application should handle content loading robustly. Upon reaching the end of the list, one of two behaviors is expected:

  Option A: If there is no more content, the app should not display a loading animation or allow further scrolling.
  Option B: While the app is in the process of loading (loading dots are visible), it should prevent the user from initiating a new refresh to avoid sending multiple requests to the server.

Actual Result:
When force-reloading repeatedly, the application fails and temporarily displays a "Server error. Please try again later." message, after which it returns to normal operation.

Evidence:
https://drive.google.com/file/d/1pVld0UUYz_yKbBKRphBieyG9vPcfUjoL/view?usp=sharing
