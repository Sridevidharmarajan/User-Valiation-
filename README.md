Head Section:
Contains a centered <h1> heading "Welcome to Validation Checking" and a horizontal line (<hr>) spanning 50% of the page width.
Includes JavaScript code embedded within <script> tags that defines a validation() function to check user input.
Form:
Structured within a <table> element aligned to the center (align="center").
Uses the <form> tag with the onsubmit attribute calling the validation() function to validate inputs before submission.
Form Fields:
Username: <input type="text" name="un" required> allows users to enter a username, which must be at least 6 characters long and start with an alphabet.
Password: <input type="password" name="pw"> for entering a password, with a minimum length of 6 characters.
Confirm Password: <input type="password" name="cpw"> to confirm the password, ensuring it matches the password entered above.
Email: <input type="text" name="email"> for entering an email address, which is validated to ensure it follows a standard format (username@domain.com).
Validation JavaScript:
Checks include ensuring the username starts with an alphabet, both passwords match and are of sufficient length, and the email address format is valid.
Displays alerts for specific validation failures and a congratulatory message upon successful submission.# User-Valiation-
