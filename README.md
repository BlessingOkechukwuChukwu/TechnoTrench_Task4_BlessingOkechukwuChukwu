Security Awareness Training Website
This project consists of multiple HTML pages simulating phishing attacks and providing security awareness tips for users. It is designed as part of a Security Awareness Training exercise where users are guided through different steps, simulating both phishing attacks and providing educational tips on how to avoid such threats in the future.

Project Overview
This project includes the following key components:

Sign In Page: A simple login page that, upon form submission, redirects the user to a simulated "hacked" page.
Security Alert Page: A page warning the user about unusual activity on their account, prompting them to secure it.
Phishing Test Page: A final page informing the user that they have interacted with a simulated phishing test and offering tips to avoid real phishing attacks in the future.
Pages Included
login.html: A sign-in form where any password redirects to a fake "hacked" page (account-hacked.html).
account-hacked.html: A page that informs the user they have been part of a phishing awareness exercise.
security-alert.html: A simulated email alert page warning of unusual account activity and urging the user to secure their account.
File Structure
bash
Copy code
/project-root
│
├── /img/                     # Image assets
│    └── logogo.png            # Company logo used in the email alert template
│
├── login.html                 # Sign-in page
├── account-hacked.html        # Phishing test page
├── security-alert.html        # Simulated email alert
├── README.md                  # Project documentation
└── /assets/                   # Additional assets (if any)
Usage
1. login.html (Simulated Sign-In)
Purpose: Simulates a sign-in form for user training.
Behavior:
Users are required to enter their email and password.
Regardless of what is entered, the form redirects the user to account-hacked.html.

</script>
2. account-hacked.html (Phishing Test Completion)
Purpose: This page informs users they have completed a simulated phishing test.
Content:
A warning that the login page and email interaction were part of a phishing awareness exercise.
Tips for identifying and avoiding phishing attacks.
3. security-alert.html (Simulated Email Alert)
Purpose: Simulates an email alert warning of suspicious account activity.
Behavior:
Displays an alert email-style template warning the user about unusual activity on their account.
Contains a button prompting users to "Secure Your Account," which links back to the login page (login.html).

To run the project:

Clone or download the repository.
Open the login.html file in a browser to start the simulation.
The login will redirect you to the "hacked" page.
Navigate to security-alert.html for the phishing awareness content.
Key Features
Simulated Phishing Attack: Users are tricked into thinking they are logging in to an actual account, but are instead redirected to an awareness page.
Educational Content: After the simulated phishing attack, users are provided with valuable security tips to help prevent real attacks.
Responsive Design: The pages are styled to be responsive and visually appealing across devices.
