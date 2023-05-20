# Technical-Questionnaire---Software-Product-Design-Intern
# User Interface Specification for User Management Screen

## Requirements
The user management screen is designed to allow administrators to manage user accounts. It should provide functionality to create new users, hide or display disabled users in the saved users list, and view a list of saved users.

## UI Components

### New User Info Section
On the right side of the screen, there should be a section to enter new user information. It should include the following fields:

- **Username**: Text input field for entering the username.
- **Display Name**: Text input field for entering the display name.
- **Phone**: Text input field for entering the phone number.
- **Email**: Text input field for entering the email address.
- **User Roles**: Dropdown/select field for selecting the user roles (options: Guest, Admin, Superadmin).
- **Enabled**: Checkbox to indicate whether the user account is enabled or disabled.

### Saved Users Table
On the left side of the screen, there should be a table to display the list of saved users and each columns should have sorting option. The table should have the following columns:

- **ID**: Unique identifier for each user.
- **Username**: Display the username of each user.
- **Email**: Display the email address of each user.
- **Enabled**: Display whether the user account is enabled (True) or disabled (False).

### Buttons
- **New User Button**: Located in the upper left corner of the screen. Clicking this button should clear the new user info section and allow the user to enter details for a new user.
- **Hide Disabled User Button**: Located in the upper left corner of the screen, next to the New User Button. Clicking this button should hide or show disabled users in the saved users table.
- **Save User Button**: Located in the upper right corner of the screen. Clicking this button should save the new user or update the details of an existing user, based on the information entered in the new user info section.

## Initial Page State
When the user management screen is loaded, the saved users table should be populated with existing user data. The new user info section should be empty, with no pre-filled values.

## Behavior
- Creating a New User:
  1. Fill in the required details in the new user info section.
  2. Click the Save User Button to save the new user.
  3. The saved user should appear in the saved users table.

- Hide/Display Disabled User Account:
  1. In the saved users table, click the checkbox for the disabled user .
  



