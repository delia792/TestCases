# TestCases
# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects.

----------------
**Description:** 
Check if the login works when a user enters the correct credentials.

**Steps to Reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add correct user/password 
3. Click "login" button

**Expected result:**
User should be able to login and is redirected to his profile page.

**Test Data:**
user: zinkadesign & parola: parolaPP!

------------------------

**Description:** 
Check if the login doesn't work when a user enters the incorrect credentials.

**Steps to Reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add incorrect user/password
3. Click "login" button

**Expected result:**
User should not be able to login and receive this message "You entered the wrong password or email address. Please fill in again." 

**Test Data:**

user: deliamarinapavel & parola: parolaPP! - With wrong user and correct password 

user: zinkadesign & parola: parola - With correct user and wrong password 

**Pre-conditions**
User should have a valid account.
