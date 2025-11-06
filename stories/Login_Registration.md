# Story 1: Account Registration

### Title:
As a user, I want to register with my name, username, age, and country, so that I can create an account and access the habit tracking features.

### Acceptance Criteria:

1. Registration form includes fields for name, username, age, and country.

2. All required fields must be filled before submission.

3. On successful registration, a confirmation message appears.

After registration, the user is redirected to the homepage.

* Priority: High
* Story Points: 3

### Notes:

* Credentials are stored temporarily (not in browser cache).

* User cannot log in with registered details after logout — only via default credentials.

#  Story 2: Account Login

### Title:
As a user, I want to log in using my username and password, so that I can access my account and track my habits.

### Acceptance Criteria:

1. Login form contains fields for username and password.

2. Valid credentials allow access to the homepage.

3. Invalid credentials trigger an error message.

4. Login session ends upon sign out.

* Priority: High
* Story Points: 2

### Notes:

* Default credentials used after logout for re-login.
