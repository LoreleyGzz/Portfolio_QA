Title: [UX] Add Logout Confirmation Modal

Proposal: It is suggested to implement a confirmation pop-up modal when a user clicks "Log out". 
The goal is to prevent accidental logouts, which can occur when users navigate quickly and misclick. 
Offering a confirmation gives the user a chance to cancel an unintended action, improving the overall usability and user experience.

Current Behavior: When the "Log out" link is clicked, the user's session is terminated immediately without any warning, redirecting them to the homepage.

Suggested Behavior: When "Log out" is clicked, a modal window should appear with the text "Are you sure you want to log out?" and two buttons: "Yes, Log Out" and "Cancel". 
The session should only be terminated if the user clicks the affirmative option.
