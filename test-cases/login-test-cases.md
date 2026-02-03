### TC-01: Login with valid credentials
Precondition: User is on the login page
Steps:
1. Enter valid username
2. Enter valid password
3. Click Login button
Expected result:
User is redirected to the secure area and a success message is displayed

### TC-02: Loign with invalid username
Precondition: User is on the login page
Steps:
1. Enter invalid username
2. Enter valid password
3. Click Login button
Expected result:
Error message is displayed and user is not logged in

### TC-03: Login with invalid password
Precondition: User is on the login page
Steps:
1. Enter valid username
2. Enter invalid password
3. Click Login button
Expected result:
Error message is displayed and user is not logged in

### TC-04: Login with empty username field
Precondition: User is on the login page
Steps:
1. Leave username field empty
2. Enter valid password
3. Click Login button
Expected result:
Validation message is displayed and login is not performed

### TC-05: Login with empty password field
Precondition: User is on the login page
Steps:
1. Enter valid username
2. Leave password field empty
3. Click Login button
Expected result:
Validation message is displayed and login is not performed
