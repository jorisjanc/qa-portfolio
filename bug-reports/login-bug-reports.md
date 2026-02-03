### Bug-01: Login fails when username contains trailing space

Environment:
- Browser: Chrome
- OS: Windows

Steps to reproduce:
1. Open login page
2. Enter valid username followed by a space character
3. Enter valid password
4. Click Login button

Actual result:
Error message "Your username is invalid!" is displayed

Expected result:
User is logged in successfully or trailing spaces in username are trimmed automatically

Severity: High
Priority: High

### Bug-02: Error message is displayed even when both fields are empty

Environment:
- Browser: Chrome
- OS: Windows

Steps to reproduce:
1. Open login page
2. Leave username field empty
3. Leave password field empty
4. Click Login button

Actual result:
Error message "Your username is invalid!" is displayed

Expected result:
Validation messages should be displayed indicating that username and password fields are required

Severity: Medium
Priority: Medium
